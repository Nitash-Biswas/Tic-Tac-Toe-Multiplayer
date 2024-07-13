# Tic-Tac-Toe Multiplayer
> Starter project for a multiplayer tic-tac-toe game using Colyseus and Phaser 3.50

## Overview

Basic multiplayer tic-tac-toe game using Colyseus as the multiplayer backend server and Phaser 3.50 as the frontend.

## Implemented Features:
- Shared game state with Colyseus Schema
- Sync clients based on server state
- Enforce server authority
- Handle player taking turns
- Algorithm to detect a winning move
- Using Colyseus match-making to join new games

## Getting Started

Clone this repository with `git` and run:

```bash
  git clone https://github.com/Nitash-Biswas/Tic-Tac-Toe-Multiplayer.git
```
Install Dependencies (using --force for few older versions) :

```bash
  npm install --force
```

Start the colyseus multiplayer server
```bash
  npm run start-server
```

In another terminal window to start the Phaser game (you need 2 windows in browser to play the game)

```bash
  npm run start
```
