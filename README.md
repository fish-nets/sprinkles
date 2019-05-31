# sprinkles
Useful little widgets and macros for Twine's SugarCube 2 theme.

### SIP (Simple Iterating Print)
`<<sip [collection]>>`

Prints the contents of a collection (lists, etc.).

### EZ Dice
`<<roll [dice] [sides] [action]>>`

Roll a number of dice with a number of sides and perform some action with the results.

Valid arguments (used when you roll multiple dice only) are:
* **sum** (default): returns the sum of results
* **list**: returns all rolls in an array
* **high**: returns the highest roll
* **low**: returns the lowest roll
