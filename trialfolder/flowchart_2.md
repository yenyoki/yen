# Fuel Mileage Calculation Flowchart

```mermaid
flowchart TD
    Start([Start]) --> InputData[/Read fuel capacity and miles per gallon/] 
    InputData --> Calculate[Calculate total miles = fuel capacity * miles per gallon]
    Calculate --> OutputData[/Print total miles/]
    OutputData --> End([End])
