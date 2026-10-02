
# Question 2 — Total and Average Marks

## Task

Input marks for 3 subjects, calculate the total and average, and display both.

## Pseudocode

START
INPUT mark1
INPUT mark2
INPUT mark3

SET total = mark1 + mark2 + mark3
SET average = total / 3

OUTPUT total
OUTPUT average

END

## Flowchart

```mermaid
flowchart TD
    A([Start]) --> B[/Input mark1/]
    B --> C[/Input mark2/]
    C --> D[/Input mark3/]
    D --> E[Set total = mark1 + mark2 + mark3]
    E --> F[Set average = total / 3]
    F --> G[/Output total/]
    G --> H[/Output average/]
    H --> I([End])
