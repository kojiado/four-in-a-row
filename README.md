# Four in a Row

Four in a Row is a classic two-player game implemented in Ruby using the Ruby2D library. The objective of the game is to be the first player to connect four of their colored tokens in a row, either horizontally, vertically, or diagonally.

## Installation

To run the game, you need to have Ruby installed on your system, as well as the Ruby2D gem. If you don't have Ruby installed, please refer to the [official Ruby website](https://www.ruby-lang.org/) for installation instructions.

To install the Ruby2D gem, open your terminal and execute the following command:

```shell
gem install ruby2d
```

## Running the Game

Once you have Ruby and Ruby2D installed, navigate to the main folder of the game in your terminal and run the following command:

```shell
ruby four-in-a-row.rb
```
This will start the Four in a Row game.

## Gameplay
The game is played by two players, represented by the colors yellow and red. Players take turns dropping their colored tokens into one of the seven columns on the game board.

To move left or right, use the arrow keys `<` `>`.<br>
To drop a token into the selected column, press the `Space` key.<br>
The game will alternate between the two players until one of them successfully connects four tokens in a row or the game board becomes full, resulting in a draw.

![game](https://github.com/kojiado/four-in-a-row/assets/127887180/7f45a7f7-1ed4-4e2c-8263-613c8b0951be)

## Token Colors

The red player is represented by a circle with the color code `#FF0000` (red).<br><br>
![redCircle](https://github.com/kojiado/four-in-a-row/assets/127887180/ce9b9800-33ac-42d8-91fd-45779c8e01ed)
<br><br>
The yellow player is represented by a circle with the color code `#FFFF00` (yellow)<br><br>
![yellowCircle](https://github.com/kojiado/four-in-a-row/assets/127887180/f6e614ad-4b1d-4f56-ba33-02939153de14)

# #Info Banners
During gameplay, the following info banners may appear:

![gameLoaded](https://github.com/kojiado/four-in-a-row/assets/127887180/6549cee2-24a1-4787-8484-85003dcbf395)<br>
This banner indicates that a previously saved game has been successfully loaded.<br><br><br>

![gameSaved](https://github.com/kojiado/four-in-a-row/assets/127887180/d02ebf8f-4db0-42f8-b0c8-60d5c43e8bf4)<br>
Game Saved: This banner indicates that the current game state has been successfully saved.<br><br><br>

![player1Wins](https://github.com/kojiado/four-in-a-row/assets/127887180/0826b417-8770-46a9-b348-7351edde28b3)<br>
Player 1 Wins: This banner indicates that Player 1 (yellow) has won the game.<br><br><br>

![player2Wins](https://github.com/kojiado/four-in-a-row/assets/127887180/8514a939-58f2-4854-8058-e881a031913d)<br>
Player 2 Wins: This banner indicates that Player 2 (red) has won the game.<br><br><br>

![DRAW](https://github.com/kojiado/four-in-a-row/assets/127887180/9d469d7f-3581-4f4d-81c9-6ddc8545f81a)<br>
Draw: This banner indicates that the game has ended in a draw.<br><br><br>

![chooseAnotherField](https://github.com/kojiado/four-in-a-row/assets/127887180/35b3d0e1-4108-442d-af76-38d069b377de)<br>
Choose Another Field: This banner indicates that the selected column is already full, and the player needs to choose another column to drop their token.
