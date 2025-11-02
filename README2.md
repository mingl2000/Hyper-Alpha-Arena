# How to debug the backend python in VS code:
    start the app:
        start_arena.ps1
    find the process id for backend process:
        windows command:
            netstat -ano | find "LISTENING"
        find the process id using port 8802

    select the python interpret as backend\script\python.exe
    Place a break point in a python code in backend API
    attach a debug in VS code to the process:
        debug => attach to the process id found above