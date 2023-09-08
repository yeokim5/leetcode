![image](https://github.com/yeokim5/leetcode/assets/66398851/50aa5a5d-7507-43c8-ad50-61bc1c2a06ff)# leetcode


### • 7 Encode and Decode Strings
#### Arrays / Solved: Yes
store it as 4#love, decode: Find the position of the '#' symbol, Get the length of the substring before the '#' symbol,Extract the substring with the given length, Add the substring to the list of decoded strings, Update the index 'i' to the position after the current substring
### • 10 Valid Palindrome
#### Two Pointer / Solved: Yes
two ways to solve, 1. reverse array and compare O(n) memory, 2. checkm alphanum lower and two pointer l+=1 r-=1 compare O(1) memory

### • 11 Valid Palindrome
#### Two Pointer / Solved: Yes
l, r = 0, len(s) -1, 2. add num l + r compare target
two ways to solve 1. for loop O(n^2) -> brute force, 2.two pointer -> optimal solution
