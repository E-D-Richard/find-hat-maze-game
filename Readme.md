# Find The Hat

### "Find the Hat" is a hat-themed simple maze game


#### Game Setup
- Set Game board/grid size by calling the static method generateField() on the (parent) Field class
- set hight width and holePercentage on generateField(height, width, holePercentage)
- holePercentage must be less than or equal to 30% (and is set using a regular number without the % symbol)
- save all the above to a variable
- create new instance of the Field class element and pass-in the variable that stores the generateField
- call the playGame() method on the newly created class instance and log it to the console 
- type node js/main.js into the console and play game 


#### Game Rules:
- Try to reach the Hat (reperesented by this symbol: ^ )
- Avoid moving out of game grid borders
- Avoid falling into a pit (reperesented by this symbol: O)