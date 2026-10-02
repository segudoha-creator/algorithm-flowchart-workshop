# Question 10 — Discount

## Task

Input the purchase amount. If the amount is greater than 1000, apply a 10% discount and display the final amount.

## Pseudocode

START
INPUT amount

IF amount > 1000 THEN
SET discount = amount * 10 / 100
SET finalAmount = amount - discount
ELSE
SET finalAmount = amount
END IF

OUTPUT finalAmount

END

## Flowchart

```mermaid id="p8k3vz"
flowchart TD
    A([Start]) --> B[/Input amount/]
    B --> C{amount > 1000?}
    C -->|Yes| D[Set discount = amount * 10 / 100]
    D --> E[Set finalAmount = amount - discount]
    C -->|No| F[Set finalAmount = amount]
    E --> G[/Output finalAmount/]
    F --> G
    G --> H([End])
```

## Example

If amount = 1500:

Discount = 1500 * 10 / 100 = 150

Final amount = 1500 - 150 = 1350

If amount = 1000:

Final amount = 1000
