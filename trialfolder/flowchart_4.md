# Salary Calculation Flowchart

```mermaid
flowchart TD
    Start([Start]) --> InputData[/input name, base salary, weekly working hours and bonus rate per hour/]
    InputData --> CalculateBonus[bonus payment = weekly working hour * bonus rate per hour]
    CalculateBonus --> CalculateGross[gross salary = base salary + bonus payment]
    CalculateGross --> CalculatePension[pension deduction = gross salary * pension]
    CalculatePension --> CalculateTax[tax deduction = gross salary * tax]
    CalculateTax --> CalculateNet[net salary = gross salary - pension deduction - tax deduction]
    CalculateNet --> OutputData[/Print net salary, bonus payment and gross salary/]
    OutputData --> End([End])
