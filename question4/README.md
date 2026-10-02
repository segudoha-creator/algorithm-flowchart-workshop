# Question 4 — Positive, Negative, or Zero

## Task

Input a number and display whether it is Positive, Negative, or Zero.

## Pseudocode

START
INPUT number

IF number > 0 THEN
    OUTPUT "Positive"
ELSE IF number < 0 THEN
    OUTPUT "Negative"
ELSE
    OUTPUT "Zero"
END IF

END

## Flowchart

```mermaid
flowchart TD
    A([Start]) --> B[/Input number/]
    B --> C{number > 0?}
    C -->|Yes| D[/Output Positive/]
    C -->|No| E{number < 0?}
    E -->|Yes| F[/Output Negative/]
    E -->|No| G[/Output Zero/]
    D --> H([End])
    F --> H
    G --> H
