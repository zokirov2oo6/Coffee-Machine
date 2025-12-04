# Coffee Machine Simulator ☕

A realistic coffee vending machine simulation written in pure Python.

## Features
- Three drinks available:
  - **Espresso** – $1.50
  - **Latte** – $2.50
  - **Cappuccino** – $3.00
- Automatic resource checking (water, milk, coffee)
- Coin processing (quarters = $0.25, dimes = $0.10, nickles = $0.05, pennies = $0.01)
- Change calculation (rounded to 2 decimal places)
- `report` – displays current resources and total profit
- `off` – shuts down the machine (maintenance mode)

## How to Run
```bash
python main.py

Example Usage
What would you like? (espresso/latte/cappuccino): latte
How many quarters?  20
How many dimes?     0
How many nickles?   0
How many pennies?   0
Here is $2.5 in change.
Here is your latte ☕. Enjoy!

What would you like? (espresso/latte/cappuccino): report
Water: 100ml
Milk: 50ml
Coffee: 76g
Money: $2.5

Requirements

Python 3.6+
No external packages needed!

