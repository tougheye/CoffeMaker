# CoffeMaker
One of my early projects which helped me sharpen my understanding of OOP concepts. 
I built this virtual coffeemaker that has separate classes for menu, cash, and the actual coffeemaker.

The CoffeMaker class models the machine that makes the coffee. 
It has functions to print reports of ingredient status, 
to check whether there are sufficient resources to make the order,
and finally to make the order.

The menu file has 2 classes. 
1. MenuItem class contains item name, cost and ingredients.
2. Menu class which is a list of MenuItems. it has functions to print message for the customer to select the order and finding the drink

The MoneyMachine class has functions to -
1. print the cashier report
2. process coins
3. make payment - Returns True when payment is accepted, or False if insufficient.



