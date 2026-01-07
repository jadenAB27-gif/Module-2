## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
<img width="814" height="321" alt="image" src="https://github.com/user-attachments/assets/94fd6f30-6a6a-4290-a4d9-188ac052b5b7" />

## Output
<img width="521" height="112" alt="image" src="https://github.com/user-attachments/assets/0081b92b-69be-4ea8-aabc-4422afad2a24" />

## Result
<img width="521" height="112" alt="image" src="https://github.com/user-attachments/assets/f8ef1bca-3163-4448-9d34-9665153b51af" />
