UC Merced AI Project:

Working two-player game: the L game, invented by Edward de Bono. The game consists of a 4x4 grid, one 3x2 L-shaped piece for each player, and two 1x1 neutral pieces. The initial positions are specified. At each turn, a player must first move its L piece to a new position that is free (i.e., within the grid and not overlapping with the other L and the neutral pieces); and then may move one of the neutral pieces to any free position (or may choose not to move any neutral piece). The game finishes when a player cannot move its L piece to any position. The rules of the game are simple, but it does require some strategy.

Features:
- Implemented minimax and heuristic alpha-beta pruning (up to a user-provided depth d, possibly infinite).
- Implemented heuristic evaluation function.
- Defined representation for the states, legal actions and the result of applying a legal action to a state.
- Plotted board and pieces as the game progresses.
- Player vs Computer, Player vs Player, and Computer vs Computer options
- Represented input moves as in the following example: 1 2 E 4 3 1 1 where (1,2) are the (x,y) coordinates of the corner of the L (where (1,1) is the top left grid position, x goes horizontally and y vertically) and E is the orientation of the foot of the L (out of North, South, East, West); and a neutral piece is moved from (4,3) to (1,1). If not moving a neutral piece, omit the part 4 3 1 1.
- Allows the user to provide an initial game state (different from the default one).
    - Represented as in the following example (corresponding to the default initial state): 3 1 W 1 1 4 4 2 4 E (L that moves first, the two neutral pieces, L that moves second).
- Allows the user to select who makes the first move (computer or human).
