# Telegram Game Bot Engine

## Overview

This project is a [Telegram](https://telegram.org/) game engine bot that allows developers to create and run text-based RPGs within the Telegram app, even using a basic text editor like Notepad. With intuitive inline buttons and callback data, players can explore uncharted worlds, make groundbreaking discoveries, and engage in exciting adventures through the depths of space. The game engine is highly customizable, allowing developers of all skill levels to create immersive games with branching storylines, multiple endings, and unique gameplay mechanics. Experience a whole new level of gameplay right in your Telegram chat with our game engine bot.

## Features

- Highly customizable game engine
- Branching storylines and multiple endings
- Unique gameplay mechanics and challenges
- Intuitive inline buttons
- Easy to use and integrate into Telegram chats

## Getting Started

To get started with the Telegram game engine bot, simply clone this repository and follow the instructions in the `example-source` file. Then, customize and modify the game to fit your needs, and start building your own text-based RPGs.

## How It Works

This sample source is a simple text-based RPG that takes the player on a superhero adventure. The game is played entirely through text-based choices, presented through inline buttons and callback data in the Telegram app. 

The game engine is built with functions that are called by the inline buttons. The `startgame` function is the starting point of the game, and it presents the player with a choice to accept or decline the challenge of saving the city from Dr. Destruction. Depending on the player's choice, the game moves on to the `intro` function. 

The `intro` function presents the player with another set of choices, depending on the action they took in the previous function. Each choice leads to a different action, and each action moves the game to a different chapter of the story. 

The `chapter1` and `chapter2` functions follow the same pattern as `intro`, with different choices leading to different actions and chapters. Finally, the `ending` function is called when the player reaches the end of the game. 

Overall, this sample source demonstrates the basic structure of a text-based RPG using the Telegram game engine bot. Developers can use this structure to create their own games with unique storylines, choices, and actions. The game engine bot makes it easy to create and run these games within the Telegram app, opening up a new world of gameplay possibilities for Telegram users.

## Usage

To use the Telegram game engine bot, simply start a chat with the [Cosmic Compass Games bot](https://t.me/CosmicCompassGamesHelperBot) and send the command /start to begin playing. The game engine supports inline buttons for intuitive gameplay mechanics, and allows players to explore uncharted worlds, make groundbreaking discoveries, and engage in exciting adventures through the depths of space.

To test the source code provided above, please send a message to this [telegram bot](https://t.me/TestGameStarsBot) with the command /start

## Update Tree

- [ ] Saving and updating players
    - [ ] Add player data model
    - [ ] Implement player creation and update methods
    - [ ] Save player data to database
- [ ] Adding and saving variables
    - [ ] Add variable data model
    - [ ] Implement variable creation and update methods
    - [ ] Save variable data to database

## License
This project is unlicensed.
