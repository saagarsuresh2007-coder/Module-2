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
<img width="811" height="419" alt="image" src="https://github.com/user-attachments/assets/77756ae3-9159-4454-b248-ae8c5d98d0e5" />

## Output
<img width="818" height="182" alt="image" src="https://github.com/user-attachments/assets/849919b3-0c4e-4960-852a-017fdcc24ed5" />

## Result
<img width="818" height="182" alt="image" src="https://github.com/user-attachments/assets/ddf0c71e-1978-4ae0-a095-472119770e8d" />
