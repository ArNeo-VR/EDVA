-- Set Application path {TXT:App_EDDiscovery} in command '(((MAIN))) Settings'

Set text [~~MyProcess] to 'EDMarketConnector'

-- ↓ Application is running
Begin Text Compare : [{PROCESSEXISTS:~~MyProcess}] Equals '1'
    
    -- ↓ Close Application
    Begin Text Compare : [{CMDSEGMENT:0}] Equals 'Close'
        Close window '{TXT:~~MyProcess}'
        Play sound, '{VA_SOUNDS}\Malic Profile\Alert Sounds\Windows Hardware Remove.wav'
    Else
    End Condition
    
    -- ↓ Start Application
Else If : [{CMDSEGMENT:0}] Equals 'Start' OR [{CMDSEGMENT:0}] Equals 'Open'
    Run application '{TXT:App_EDMC}' - wait until it starts
    Play sound, '{VA_SOUNDS}\Malic Profile\Alert Sounds\Windows Error.mp3'
    Pause 0,5 seconds
End Condition

-- ↓ Move Application
Begin Condition : ([{CMDSEGMENT:0}] Equals 'Move' AND [{PROCESSEXISTS:~~MyProcess}] Equals '1') OR ([{CMDSEGMENT:0}] Equals 'Start' AND [{PROCESSEXISTS:~~MyProcess}] Equals '1') OR ([{CMDSEGMENT:0}] Equals 'Open' AND [{PROCESSEXISTS:~~MyProcess}] Equals '1')
    Move window '{TXT:~~MyProcess}' to (1600,880)
    DISABLED - Display window '{TXT:~~MyProcess}' as [Show No Activate]
End Condition