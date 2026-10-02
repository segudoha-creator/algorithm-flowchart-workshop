# Question 9 — Factorial

## Task

Input a number, calculate its factorial using a loop, then display the result.

## Pseudocode

START
INPUT number

SET factorial = 1
SET i = 1

WHILE i <= number
SET factorial = factorial * i
SET i = i + 1
END WHILE

OUTPUT factorial

END

## Flowchart

```mermaid id="n7c4vx"
flowchart TD
    A([Start]) --> B[/Input number/]
    B --> C[Set factorial = 1]
    C --> D[Set i = 1]
    D --> E{i <= number?}
    E -->|Yes| F[Set factorial = factorial * i]
    F --> G[Set i = i + 1]
    G --> E
    E -->|No| H[/Output factorial/]
    H --> I([End])
```

## Example

If number = 5:

Factorial = 1 × 2 × 3 × 4 × 5

Factorial = 120
