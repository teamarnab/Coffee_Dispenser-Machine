Problem statement

1. Create a program for a coffee dispenser machine.
2. User can have 3 types of coffee. Latte, Cuppaccino and Espresso
3. There would be an inventory with required ingredients (coffee, water and milk)
4. Once user selects what type of coffee they want, machine would check if there is necessary amount of required ingredients.
5. If ingredients are not available then machine should print an error message and ask user to choose another type of coffee.
4. If ingredients are available the program should make the coffee by deducting the required amount of each ingredient from 
the inventory and update amount left in the inventory.
5. Print cost of the coffee and a thank you message.
6. In case a user enteres invalid input they should be given an error message and asked to enter choice again.

Steps followed
1. Created a base class Coffee.
2. Created 3 coffee objects from coffee class i.e. latte, cuppaccino and espresso.
3. Created inventory object from coffee class.
4. Created a function that takes 2 arguments, inventory adn coffee wanted and checks if the amount of proper 
ingredients available to make the required cofee
5. Created a function that will take required amount of required ingredients and update inventory (making the coffee)
6. A while loop so program will be running until user shuts it down.
7. Ask user if they want coffee, check inventory or shut down the machine.
8. Ask user what kind of coffee they want and the make the coffee, then check inventory, print coffee cost and make coffee.
9. Print inventory if the user wants to check inventory.
10. Break from the loop if user wants to continue or repeat from step 7


