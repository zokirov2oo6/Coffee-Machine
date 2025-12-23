# Coffee Machine 

A fully object-oriented coffee machine simulator written in Python, based on the famous "Day 16" project from the **100 Days of Code** course.

## Features
- Pure OOP design with 4 main classes  
- Menu management (latte / espresso / cappuccino)  
- Resource tracking (water, milk, coffee)  
- Coin-operated payment system (quarters, dimes, nickels, pennies)  
- `report` command to show current resources and profit  
- `off` command to turn the machine off  
- Clean and readable console interface  

## Classes Implemented
| Class          | Responsibility                                      |
|----------------|-----------------------------------------------------|
| `MenuItem`     | Holds name, cost and ingredients of a drink         |
| `Menu`         | Manages available drinks and searching              |
| `CoffeeMaker`  | Tracks and deducts resources, makes coffee          |
| `MoneyMachine`| Handles payments, calculates change and profit      |

## How to Run
```bash
python main.py
Available commands:

espresso / latte / cappuccino → order a drink
report → show remaining resources and total profit
off → turn the machine off

Example Usage
text
