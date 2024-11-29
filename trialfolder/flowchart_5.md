# File Transfer Time Calculation Flowchart

```mermaid
flowchart TD
    Start([Start]) --> InputData[/Read file size in bytes/]
    InputData --> InitializeRate[Declare and initialize rate = 960]
    InitializeRate --> CalculateTime[ time taken = file size / rate]
    CalculateTime --> CalculateDays[ days = time taken / 86400]
    CalculateDays --> CalculateHours[ hours = time taken / 3600]
    CalculateHours --> CalculateMinutes[ minutes = time taken / 60]
    CalculateMinutes --> OutputData[/Print time taken in days, hours, minutes and seconds/]
    OutputData --> End([End])
