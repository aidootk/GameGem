#GameGem Tutorial

### How it works


### Accurate 

1. Select a running application process by click ![img](http://www)
2. Specify a data type you want to search, by click ![img](http://www). How to select data type, see "Data Type"
3. Input the value you want to search, at here ![img](http://www)
4. Click search button ![img](http://www).
5. Return to your game , and make change to the number what you searc. eg. HP 583 -> 600
6. Return to GameGem, input the value which were changed in game. eg. HP 600.
7. Click search button .
8. Repeat step 5 - 7, until you get a few results.
9. If you get so a few results, then click the result list button to see all results. ![img](http://http://www).
10. Follow "Lock" or "Modify" tutorial to deal with the result.

### Fuzzy

Fuzzy search is slow than accurate search, because the app will scan all the game data, check "Tips" section to speed up your searching.

1. Select a running application process by click ![img](http://www)
2. Specify a data type you want to search, by click ![img](http://www). How to select data type, see "Data Type"
3. Just click the search button.
4. Return to game, play for a while, make value changes.
5. Return to GameGem, select a compare type. Check "Compare Type" to know more about it.
6. Click the search button.
7. Repeat step 5 - 7, until you get a few results.
8. If you get so a few results, then click the result list button to see all results. ![img](http://www).
9. Follow "Lock & Modify" tutorial to deal with the result.

### Lock & Modify

### Data Type 

There are 8 data types in GameGem.

|  Data Type | Description |
|------------|-----------------|
| Auto 		| Include all following data type, GameGame will detect the data type. But this one is very slow to deal with, especily in fuzzy search model. |
| Any Float 	| Float 32 and 64, eg. 8.0 is a float number. 8 is a int number, not float. |
| Any Int 	| Int 16, 32 and 64 |
| Int 16 		| Intenger, between -32768 and 32767 |
| Int 32  	| Between -2147483648 and 2147483647 |
| Int 64 		| Between -9223372036854775808 and 9223372036854775807|
| Float 32 	| Float type, 4 bit in ram. Range is same as Float 64. |
| Float 64 	| Float type,high precision. The second "float 32" in the list. 8 bit in ram. Range is same as Float 32.|


### Compare Type
There are 4 compare types in GameGem.

|  Compare Type | Description |
|------------|-----------------|
|  > 			| New value is grater than old value.  |
|  < 			| New Value is less than old value. |
|  == 			| New value is equal to old value, not changed. |
|  != 			| New value is not equal to old value, changed. |

### Tips

To improve your searching, you can follow these tips:

* Don't us "Auto", "Any Float", "Any Int" types if you don't have to.
* Use "Int 32" , this is the fastest data type.
* ">" and "<" is better than "!=" in fuzzy mode.
* By click the reset button on "right-top" corner before you start a new search.
* If error occured, restart up GameGem.


















