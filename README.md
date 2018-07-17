
## Demo
```	python
	>>> import TicTacToeMaster as ttt

	>>>  board, nextMove = ttt.getRandomBoard()
	>>> ttt.printBoard(board)
	>>>
	_   _   _   
	O   X   _   
	O   O   X   

	>>> bestMove = ttt.getAIMove(board, nextMove, nextMove)
	>>> print(nextMove+" should play at: " + str(bestMove[0]) + " index")
	>>> 
	X should play at: 0 index

	>>> board = [" ", " ", "X", " ", "O", " ", "X", " ", " "]
    >>> bestMovePosition = ttt.getAIMove(board, "O", "O")[0]
    >>> print("O should play at: " + str(bestMovePosition) + " index")
    >>> 
	O should play at: 1 index

```

## Installation

Just Copy the TicTacToeMaster.py in your project and you are good to go

## Dependencies

None, pure python code.

