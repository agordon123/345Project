# 345Project
## **"24" , produeced by Leonel Barrientos, Adam Gordon, and Bryan Gonzalez, 4/2021**
### Release v1.0
### Part A) Repository information
This repository contains a Java program using JavaFX libraries to play a math based challenge game. We used special methods on the fxml controller to manipulate images
to randomly generate pictures of playing cards, and challenge the user to figure out the expression that solves the puzzle. It was our semester project for BCS345 in Spring 2021.
### Part B) Using the program
You must have the latest Java SDK kit as well as the JavaFX 2 plugins, and add them to a new library using the menu.
In order to run the program, you must have a IDE that supports java and javafx, such as netbeans.You must set your classpaths to your local javafx packages on compile,
and module path on run under the properties, as well was going to VM options and adding --add-modules javafx.controls,javafx.base,javafx.fxml 
You must do these steps or you won't be able to run the game
### Part C) Game Tutorial
Using JavaFX, this program is a Math based challenge game, where 4 cards are displayed, at random.
Each card has a value, depending on card face, from 1-13(Ace to King).
The object of the game is to figure out the equation of the 4 values that equals 24, or report No Solution.
The main interface of the game consists of a JavaFX scene, with 4 ImageView boxes to hold the cards. Upon load up,
an alert box pops up asking if you're up to the challenge.  Clicking OK proceeds to the game, click cancel exits the program.
The main screen consists of these items :
### 1. Start Timer (button)
Press this button to start recording time, which
### 2. Reset Timer (button)
Click this button to refresh the clock
### 3. Refresh Cards
Click this button to generate 4 new cards
### 4. Solution TextField(Top)
This is where the solution is displayed if you can't solve the puzzle and click the Show Solution Button
### 5. Show Solution
This button displays the solution to the current game in the top TextField.
### 6. Expression TextField (bottom)
This is where you enter your guess
### 7. Verify Button
This button verifiess whether you have the correct answer or not, if you don't have the correct answer an alert box will pop up saying you're answer is incorrect.
if your answer is correct, you will get another alert box telling you how long it took you to solve the puzzle, and a prompt to play again.
### 8. Quit Button(Top Left Corner) 
Red X in the top left corner to exit the program, with a confirmation alert
