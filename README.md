# Python---Space-Shooter-game

![3MzfmbT](https://user-images.githubusercontent.com/77020328/116327982-ef331480-a795-11eb-9d54-2a6f7c9eeb7f.jpg)


![Space-Shooter-Game-in-TypeScript](https://user-images.githubusercontent.com/77020328/116327344-96af4780-a794-11eb-81e1-8ddf0b389ff6.png)

In the main class I have defined all the variables and attributes that would affect and govern the Dynamics of the game, for example initializing clock settings which would help moderate or FPS, defining fonts, defining velocity for the player and enemy ship, as well as for the lasers.

So there are a couple of important methods that I defined in this class, we have a redraw a window method to handle all the drawing and blitting properties for the pie game window, and is responsible for updating the screen 60 times every second.

Then we have a function to calculate and maintain and update the health for the playership and the number of lives remaining and the number of levels a player has cleared.

We have a random method which is used to generate random set of five enemy ships every time a player levels up or if there are no enemy ships left in the enemy queue.

Lastly there is a quick method to determine if the player wants to quit the game at any time by clicking the quit button, if the player clicks the exit button then we set the main method to false and the user is taken back to the main screen in the game.
