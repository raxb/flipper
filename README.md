# flipper

Card Flipping 
Given a list cards where “U” represents face up, and “D” represents face down, determine the minimum and maximum number of moves to flip all cards such that they are face up given the following constraints:
1.	Cards are placed sequentially from left to right
2.	You can only choose to flip a card which is face down
3.	When you choose to flip a card, the card to the immediate right is also flipped. i.e [D, D] -> [U, U] or [D, U] -> [U, D]

Example 1
Input = D, D, D, D, D

Output: 
Minimum number of moves = 3
Maximum number of moves = 120
	Example 4
Input = U, U, D, D, D, U

Output:
Minimum number of moves = 5
Maximum number of moves = 9


Example 2
Input = U, U, U, U

Output: 
Minimum number of moves = 0
Maximum number of moves = 0
	
Example 5
Input = D, D, U, U, D, D, D

Output:
Minimum number of moves = 6
Maximum number of moves = 123


Example 3
Input = D, D, D, U, D, U

Output: 
Minimum number of moves = 9
Maximum number of moves = 31
	
Example 6
Input = D, U, D, D, D, U, D, U

Output: 
Minimum number of moves = 13
Maximum number of moves = 730




