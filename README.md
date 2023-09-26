

### • 7 Valid Sudoku
#### Arrays / Solved: Yes
1.  mapping where keys are tuples (row_index, col_index) ex. ('Alice', 'Math'): 95 2. // : 10//3 = 1
use defaultdict(set) col,row,square, board[r][c] check if in return false trick: square(r//3,c//3)


### • 8 Encode and Decode Strings
#### Arrays / Solved: Yes
store it as 4#love, decode: Find the position of the '#' symbol, Get the length of the substring before the '#' symbol,Extract the substring with the given length, Add the substring to the list of decoded strings, Update the index 'i' to the position after the current substring



### • 10 Valid Palindrome
#### Two Pointer / Solved: Yes
two ways to solve, 1. reverse array and compare O(n) memory, 2. checkm alphanum lower and two pointer l+=1 r-=1 compare O(1) memory

### • 11 Valid Palindrome
#### Two Pointer / Solved: Yes
l, r = 0, len(s) -1, 2. add num l + r compare target
two ways to solve 1. for loop O(n^2) -> brute force, 2.two pointer -> optimal solution

### • 12 3 SUM
#### Two Pointer / Solved: Yes
1. nums.sort() 2. while l < r and the value doesn't contain same value as next one
