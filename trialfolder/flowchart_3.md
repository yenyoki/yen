# Power Calculation Flowchart

```mermaid
flowchart TD
    Start([Start]) --> InputData[/Read x  and y/]
    InputData --> Calculate[ power = x^y ]
    Calculate --> OutputData[/Print power/]
    OutputData --> End([End])
