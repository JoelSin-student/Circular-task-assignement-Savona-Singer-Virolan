# Data


- `.csv`: 2D positions in a circular movement task
    - Line 0: hardware, task and software information
    - Line 1: date and time
    - From line 4 :
        - Column 0: timestamps
            - unit: time in ms since Unix epoch
        - Column 1: x component
            - unit: pixel
        - Column 2: y component
            - unit: pixel
        - Column 3: target reaching information
            - unit: binary

- `marker.csv`: 2D positions in a circular movement task
    - Line 0: hardware, task and software information
    - Line 1: date and time
    - From line 4 to 17: task completion information
    - From line 18 to 26: summary of task performance


`001MoDe_R1` : development data

`Sav` : Lucas SAVONA data

`SiJo` : Joël SINGER data

`214ViMo_R1` : Morgan VIROLAN data