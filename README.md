# object-literals
Assignment 5-1 Instructions: Use an object literal with the Change Calculator
In this assignment, you’ll modify a Change Calculator application so it uses an object literal. When you’re done, the application will work the same as it did before. 
	 
1)	Open the starter application(zipped) attached to this Assignment folder:
a)	Evaluations\Assignments\Assignment 5\Part1-change_literal.zip
b)	Note that this application uses two JavaScript files: the main JavaScript file (calculate.js) and the start of a library file (library_coin.js).
2)	In the calculate.js file, note that all of the code for the application is in the handler for the click event of the Calculate button.
3)	In the library_coin.js file, note that just the strict mode declaration has been provided.
4)	In the index.html file, add the script tag for the library file. 
5)	Modify the code in the library file so it defines an object literal named coins. This object should have properties for quarters, dimes, nickels, and cents. In addition, it should have a makeChange() method that accepts the number of cents.
a)	If the number of cents is valid, the makeChange() method should calculate the number of coins for each type and update the quarters, dimes, nickels, and cents properties. Otherwise, it should throw an exception.
6)	Modify the code in the calculate.js file to use the object literal named coins to calculate and display the number of coins for each type of coin. Note that this code should still validate the user entry. That way, this script won’t pass an invalid amount to the makeChange() method, and that method won’t throw an exception.
7)	In index.html, change the text in the <small> tag to your name and student number.

 
Assignment 5-2 Instructions: Use a class with the Change Calculator
In this assignment, you’ll modify a Change Calculator application so it uses a class. When you’re done, the application will work the same as it did before. 
	 
1)	Open the starter application(zipped) attached to this Assignment folder:
a)	Evaluations\Assignments\Assignment 5\Part2-change_class.zip
b)	Note that this application uses two JavaScript files: the main JavaScript file (calculate.js) and the start of a library file (library_coin.js).
2)	In the calculate.js file, note that all of the code for the application is in the handler for the click event of the Calculate button.
3)	In the library_coin.js file, note that just the strict mode declaration has been provided.
4)	In the index.html file, add the script tag for the library file. 
5)	Modify the code in the library file so it defines a class named Coins. This class should have a constructor that defines properties for quarters, dimes, nickels, and cents and initializes them to 0. In addition, it should have a makeChange() method that accepts the number of cents.
a)	If the number of cents is valid, the makeChange() method should calculate the number of coins for each type and update the quarters, dimes, nickels, and cents properties. Otherwise, it should throw an exception.
6)	Modify the code in the calculate.js file to create an object from the Coins class. Then, use that object to calculate and display the number of coins for each type of coin. Note that this code should still validate the user entry. That way, this script won’t pass an invalid amount to the makeChange() method, and that method won’t throw an exception.
7)	In index.html, change the text in the <small> tag to your name and student number.
 
Assignment 5-3 Instructions: Convert the PIG app to objects
In this assignment, you’ll be converting the PIG application from chapter 12 so it uses objects. When you’re done, the application will work the same as it did before, but the code will be organized differently.
	 
To start this game, you enter the names for the two players and click the New Game button. Then, the message below the names indicates whose turn it is. When the game is over, a dialog box announces the winner.
1)	Open the starter application(zipped) attached to this Assignment folder:
a)	Evaluations\Assignments\Assignment 5\Part3-pig.zip
2)	Review the library_die.js file. Note that it contains a class named Die with no properties and a single method that rolls a die.
3)	Review the library_pig.js file. Note that it contains a class named Pig that has a property that’s an object created from the Die class. The Pig class has a constructor() function with five data properties, a read-only accessor property, and three methods.
4)	Review the library_game.js file. Note that it’s an object literal with three data properties, one read-only accessor property, and five methods. The start() method and isValid read-only property are already coded for you, and the other methods have comments indicating what they should do. Now, finish the code for those four methods and make them cascading methods when you can.
5)	Review the pig.js file and note that it supplies the ready event handler and the click event handler of the New Game button. There are also starts for the click event handlers for the Roll and Hold buttons, which you need to finish. These handlers should use the methods of the game object in the library_game.js file. 
6)	In index.html, change the text in the <small> tag to your name and student number.
