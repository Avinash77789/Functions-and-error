**Airport Checkpoint**

**Description:**
The Airport Checkpoint smart contract is designed to manage luggage checking for passengers at an airport. It ensures that each passenger can only have one piece of luggage taken for checking and restricts certain prohibited items from being transported via luggage.

**Features:**
1. **Owner Management:** The contract allows for an owner to be designated, who has exclusive access to certain functions.
2. **Luggage Tracking:** It tracks whether a passenger's luggage has been taken for checking or not.
3. **Item Validation:** Certain prohibited items are restricted from being transported through luggage.

**Functions:**
- **checkLuggage:** Passengers can call this function to check their luggage. It ensures that each passenger can only have one luggage taken for checking.
- **checkNumberOfItems:** This function is used to verify that the number of items a passenger has does not exceed a certain limit (10 items).
- **validateItem:** This function checks whether an item is allowed to be transported through luggage. It restricts items like knives, guns, firecrackers, and batteries.

**License:**
This smart contract is licensed under the MIT License, which permits unrestricted use, distribution, and modification, subject to certain conditions.

**Author**

Avinash R

avinashreddy777890@gmail.com


