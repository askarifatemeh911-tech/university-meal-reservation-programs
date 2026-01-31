flowchart LR
    Start((Start))
    Login{User logged in?}
    Register[Register User]
    Dashboard[Go to Dashboard]
    CreateRepo[Create Repository]
    End((End))

    Start --> Login
    Login -- No --> Register
    Register --> Dashboard
    Login -- Yes --> Dashboard
    Dashboard --> CreateRepo
    CreateRepo --> End

