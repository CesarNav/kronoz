**Title:** _Create a task_  
**Primary Actor:** User  
**Success Scenario:**  
    1. The user chooses an ativity to do  
    2. The user creates a name and a time duration for the task  
    3. The system estimates the number of pomodoros according to the time duration.  
**Extensions:** None  
**Preconditions:** None  


**Title:** _Start a pomodoro_  
**Primary Actor:** User  
**Success Scenario:**  
    1. The user chooses a created task.  
    2. The user starts the pomodo timer.   
    3. Once the time is over the system checks the pomodoro and notifies the user.  
**Extensions:** None  
**Preconditions:** Must exist a created task.  

**Title:** _Cancel a pomodro _ 
**Primary Actor:** User  
**Success Scenario:**  
    1. The user cancels a pomodoro.  
    2. The system restarts the pomodoro timer  
    3. The system does not check the pomodoro  
**Extensions:** None  
**Preconditions:** Must exist a pomodoro running.  

**Title:** _Add a pomodoro_  
**Primary Actor:** User  
**Success Scenario:**  
    1. Once all the pomodoros's taks are checked the system must asks the user if the task is done.  
    2. If the task is done the system check the task.  
    3. Else if the task is not done, the system asks the user an estimate time to be the task done.  
    4. The system estimates the number of pomodoros according to the time duration.  
**Extensions:** None  
**Preconditions:** All the pomodoros's task must be checked.  

**Title:** _Check a task_   
**Primary Actor:** User  
**Success Scenario:**  
    1. Once the task is done the user can check the task.  
    2. The system checks the task and archives it.  
**Extensions:** None
**Preconditions:** None