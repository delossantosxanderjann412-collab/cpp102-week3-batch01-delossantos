```mermaid
flowchart TD
    START([START])
    INPUT1[/Enter Quiz Score 1/]
    INPUT2[/Enter Quiz Score 2/]
    INPUT3[/Enter Quiz Score 3/]
    PROCESS[Average = (Q1 + Q2 + Q3) / 3]
    OUTPUT[/Display Average/]
    END([END])

    START --> INPUT1
    INPUT1 --> INPUT2
    INPUT2 --> INPUT3
    INPUT3 --> PROCESS
    PROCESS --> OUTPUT
    OUTPUT --> END
```
