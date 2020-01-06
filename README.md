# Inventory-Search-Engine

This program uses a home made Search Engine, using Finite State Machines. It was a Team Project for the class of Discrete Math.
In our class, we used a Finite State Machine to recognize search items. A PNG picture provided in the repo explains the state machines.
A Class Diagram is also provided, it explains the interactions betweens all classes in this Object Oriented Program. 
Using Python, we have implemented a very User-Friendly Interface. 

Requirements to run the program:
    Python version 3.7.3

Run the program:
    Windows:        $python main.py
    MacOs or Linux: $python3 main.py



How to use the program:
    1) Press [1] and enter the name of the .txt file that contains the inventory data. 
        Which is either 'inventaire.txt' or 'Inventaire_grosFichier.txt' *Very Huge File!*
        
    2) Then Press [2] and Enter, it will take you to the Search Engine, where you can look for a specific item!
       The program uses auto-complete feature, so you may write a part of the search and it will suggest you upto 
       10 items on screen and tell you the amout of items that matches your search.

        Search with type-> Available types: A,B,C
        Search with ID  -> Available ID:    6 Characters search, ex: B421AC, but you can type and search with B4, 
        it will suggest you all that starts with B4.
        Search with ID  -> Write the name of the item you would like to take.

        To complete your search, you must select only ONE ITEM. All IDs are unique. So you can complete the search 
        with the ID Number of an item
        and it will display you only ONE item. Then press [5] add the item to cart and continue.
        
    3) You can see your Shopping Cart with [3], remove some items with [4][5] or Confirm your order with [6].
    
    4) Exit the program with [7]
