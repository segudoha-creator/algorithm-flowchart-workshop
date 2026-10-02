# Question 3 — Multiplication Table

## Task

Input a number and display its multiplication table from 1 to 10.

## Pseudocode

START
INPUT number
SET multiplier = 1

WHILE multiplier <= 10
    OUTPUT number * multiplier
    SET multiplier = multiplier + 1
END WHILE

END

## Flowchart

```mermaid
flowchart TD
    A([Start]) --> B[/Input number/]
    B --> C[Set multiplier = 1]
    C --> D{multiplier <= 10?}
    D -->|Yes| E[/Output number * multiplier/]
    E --> F[Set multiplier = multiplier + 1]
    F --> D
    D -->|No| G([End])
