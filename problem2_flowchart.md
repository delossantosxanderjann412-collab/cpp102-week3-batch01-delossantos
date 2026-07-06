flowchart TD
    START([START])
    INPUTL[/Enter Length/]
    INPUTW[/Enter Width/]
    PROCESS[Compute Area = Length * Width]
    OUTPUT[/Display Area/]
    END([END])

    START --> INPUTL
    INPUTL --> INPUTW
    INPUTW --> PROCESS
    PROCESS --> OUTPUT
    OUTPUT --> END