# Data


- `001MoDe_R1.csv`: 2D positions in a circular movement task
    - Line 0: hardware, task and software information
    - Line 1: date and time
    - From line 4 :
        - Column 0: timestamps
            - sampling rate: ~195.92 Hz (19592 samples for 100 sec)
        - Column 1: x component
            - unit: pixel
        - Column 2: y component
            - unit: pixel
        - Column 3: target reaching information
            - unit: binary

- `001MoDe_R1.markers.csv`: 2D positions in a circular movement task
    - Line 0: hardware, task and software information
    - Line 1: date and time
    - From line 4 to 17: task completion information
    - From line 18 to 26: summary of task performance