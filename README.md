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

## Preview
![game_preview](https://github.com/kojiado/four-in-a-row/assets/127887180/604f1f53-f1d9-4670-9510-e960bd123ad3)


## Token Colors

The red player is represented by a circle with the color code `#FF0000` (red).<br><br>
![redCircle](https://github.com/kojiado/four-in-a-row/assets/127887180/ce9b9800-33ac-42d8-91fd-45779c8e01ed)
<br><br>
The yellow player is represented by a circle with the color code `#FFFF00` (yellow)<br><br>
![yellowCircle](https://github.com/kojiado/four-in-a-row/assets/127887180/f6e614ad-4b1d-4f56-ba33-02939153de14)

## Gameplay
The game is played by two players, represented by the colors yellow and red. Players take turns dropping their colored tokens into one of the seven columns on the game board.

To move left or right, use the arrow keys `<` `>`.<br>
To drop a token into the selected column, press the `Space` key.<br>
The game will alternate between the two players until one of them successfully connects four tokens in a row or the game board becomes full, resulting in a draw.

During the game, you can save the current game by clicking the `Save Game` button.<br>This will store the current state of the game for future continuation.

To load the last saved game, click the `Load Game` button.<br>The game will load the last saved state automatically.
