

# MISSION TACTICS

Mission TACTICS is a stategy board game. It is played by two players on a 10x8 board, each controlling 24 pieces. Each piece has a military rank that is hidden from the opponent. One of the pieces is the Flag. The objective of the game is to eliminate or capture the Flag of the opponent, or to maneuver one's Flag to the far edge of the board of the opponent. Just like in chess, a piece can challenge another piece and the lower ranked piece is killed. The project aims to be played both on mobile and browser.

## Content

- [Objectives and victory conditions](#Objectives-and-victory-conditions)
- [Pieces](#Pieces)
- [Board layout](#Board-layout)
- [Gameplay](#Gameplay)- 
- [Features](#Features)
- [Scope](#Scope)

#### Objectives and victory conditions
1. Eliminate the opponent's Flag
2. Maneuver one's Flag to the opposite edge of the board 
3. The Flag, if challenged, is eliminated by any opposing piece, including the opposing and challenging Flag. The Flag that challenges the opponent's Flag wins the challenge and the game.
4. At the end of a match and a victor is determined, all surviving pieces in the board are revealed.

#### Board Layout
The game is played on a board with 80 squares arranged in 10 squares columns and 8 rows.

To start the game, each player can position its 24 pieces in any of the nearest 3 rows (30 squares) to the player's side, leaving 6 squares open.

Allowing players to position their pieces in the allowed squares is part of the strategy.

#### Gameplay
Each player is randomly assigned light or dark pieces. The players in light pieces goes first. Players take their turns alternately. 

Each player can move only one piece per turn. All pieces can only move one square with the the direction either going forward, backward, or sideways inside the board. A piece can't move towards the square of another friendly piece. Diagonal moves are not allowed.

Each piece can challenge an opposing piece located front, behind, or to either side of it. Identical to the way it moves. A player initiates a challenge by placing their piece on the same square where an opposing piece is located. Regardless of which piece initiated the challenge, their ranks determine which piece is to be eliminated and removed from the board.

#### Pieces
Each player has 24 pieces with a hierarchy of ranks and abilities. A higher-ranking piece will eliminate any lower-ranking piece. with some special exceptions; 

The special exceptions are:
1. The Assassin can eliminate anyone except for the Spy.
2. The Spy can be eliminated by all pieces except the Flag, Medic and Assasin. It's the only piece that can eliminate the Assassin.
3. The Medic can be eliminated by all pieces except the flag.
4. The Flag can only eliminate an opponent's flag.

| Pices      | No. of Pieces | Eliminates                                    | Eliminated by                            | 
| :--------- | :------------ | :-------------------------------------------- | :--------------------------------------- |
| Assasin    | 2             | All pieces except Spy                         | Spy                                      |
| General    | 2             | Same or lower ranked pieces, Flag, Spy, Medic | Assasin                                  |
| Major      | 2             | Same or lower ranked pieces, Flag, Spy, Medic | Assasin, Higher ranked pieces            |
| Captain    | 2             | Same or lower ranked pieces, Flag, Spy, Medic | Assasin, Higher ranked pieces            |
| Lieutenant | 2             | Same or lower ranked pieces, Flag, Spy, Medic | Assasin, Higher ranked pieces            |
| Sergeant   | 2             | Same or lower ranked pieces, Flag, Spy, Medic | Assasin, Higher ranked pieces            |
| Infantry   | 6             | Same ranked piece, Flag, Spy, Medic           | Assasin, Higher ranked pieces            |
| Spy        | 4             | Assassin, same piece, Medic, Flag             | All pieces except, Assassin, Medic, Flag |
| Medic      | 1             | Same piece, Flag                              | All pieces except Flag                   |
| Flag       | 1             | Same piece                                    | All pieces                               |

#### Features
- Home - screen that has a button play (with other players or AI if there are no players) or to play with friends (create/join a game); button to other main screens: rules, rankings, settings, spectate 
- Play - board game screen; shows players with each assigned light or dark pieces, pieces in board (player view only shows own pieces rank to self), captured pieces (player view shows opponent captured pieces rank to self), expressions (user has list of expressions with sound to use in-game, ex. "Well, played", "Hurry up")
- Rules - explain board, piece ranks and abilities, piece movements, game objectives, 
- Rankings - list of all-time player rankings, players are ranked every game see ranking points for details.
- Spectate - list of matches are available for public viewing, max displayed games in list is 20, randomly chosen. Games played with friends has option to be private with the game creator has the option to disable public viewing.
- Settings - adjust background music, game music, view controls, language
- Player Profile - player rank, win-lose tally, location, username, profile avatar
- Cross platform - game is playable both in desktop browser and mobile. Cross platfrom playing is allowed. Mobile browser players are directed to mobile game (directed to install, if game is not yet installed)

#### Scope 
Other game details that are within the scope of the project
- Ads -  every game ends, an ad is displayed
- Player matching - Player to player (PVP) matching is prioritized. Players is not match by rankings. If there is no available player, player is assigned to AI.
- AI Game - players who play AIs are randomly assigned an AI level - beginner, intermediate, master 
- Ranking points -  every player win whether its a fellow player or AI gets 4 points. Loser gets 1 point. AI don't get points. Players that are disconnected or who exit the game don't get points.

#### Roadmap
- Scheduled tournaments - users can join an official tournament and win game coins
- Versions - users can play on different board and pieces of the game ex. feudal Japan-themed board with pieces like ninja, samurai, etc.
- Coins - user can use to buy in shop
- Shop - user can buy avatar, board designs, ad-free subscription
- Paid subscription - no ads, and other perks
