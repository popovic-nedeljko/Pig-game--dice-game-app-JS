# Pig game - dice games

[PigGameApp](https://pig-game-dicegames.netlify.app/)

<img src='/src/img/dice_game.png' width=500 height=400> <img src='/src/img/dice-game-phone.png' width=250 height=400>

Fun game for 2 players.

- GOAL

Get first to the final score.

- FINAL SCORE

Insert number in field "choose score", otherwise default final score is 100.

- ROLL DICE

Rolled dice represents score.(random roll)

- CURRENT SCORE

Score per turn, evry dice is added.

- SCORE

Sum score

### Rules

- Each player starts by clicking button "roll dice",and the dice that is rolled is the score that is added to current score.

- If player rolls a 6 two times in a row then he's score and current score is set to 0, and it is others player turn to play.

- If palyer rolls a 1, then he loses the current score and it is others players turn.

- If player does not want to risk the score he can click hold and the current score is transfered/added to he's score, and is a step closer to final score and winning the game.

- Player who get's to final score wins.

#### Code overview

The Dice game's user interface was built using JavaScript and DOM manipulation, allowing for dynamic updating of scores and game status as players roll the dice and accumulate points.

Through the use of conditional statements, loops, and event listeners, the dice game provides an engaging and interactive experience for two players, with the ability to customize the winning score and start a new game with the click of a button.

The use of a random number generator simulates rolling dice in the game, with a 6-6 roll resulting in the loss of all accumulated points for the active player.

The remaining features include logic for switching players, displaying scores, and determining a winner based on a chosen score threshold.

#### NOTE SETTINGS

Instructions for testing purposes.

_*Inside project root(src)*_

```
'npm instal live-server'
```

```
'nmp run compile:sass'
```

```
'live-server'
```

```
Enjoy 🎲
```
