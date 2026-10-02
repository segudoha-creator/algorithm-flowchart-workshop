# Question 5 — Simple Interest

## Task

Input Principal (P), Rate (R), and Time (T), then calculate and display Simple Interest.

## Pseudocode

START
INPUT P
INPUT R
INPUT T

SET SI = (P * R * T) / 100

OUTPUT SI

END

## Flowchart

```mermaid
flowchart TD
    A([Start]) --> B[/Input P/]
    B --> C[/Input R/]
    C --> D[/Input T/]
    D --> E[Set SI = (P * R * T) / 100]
    E --> F[/Output SI/]
    F --> G([End])
