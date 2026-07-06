flowchart TD
    START([START])
    INPUT1[/Enter Hourly Rate/]
    INPUT2[/Enter Hours Worked/]
    PROCESS[Gross Pay = Hourly Rate * Hours Worked]
    OUTPUT[/Display Gross Pay/]
    END([END])

    START --> INPUT1
    INPUT1 --> INPUT2
    INPUT2 --> PROCESS
    PROCESS --> OUTPUT
    OUTPUT --> END