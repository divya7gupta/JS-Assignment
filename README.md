# JS Assignment 

## Question 1: Digit Gatekeeper
Logic:
Loop from L to R
Check if number contains digit 0
Check if number is divisible by K
Find sum of digits
Check if sum is prime
Count valid numbers

Complexity:
Time: O(N * digits)
Space: O(1)

## Question 2: Roll-Seed Lock
Logic:
Repeat 3 times:
If even → divide by 2 and add seed
If odd → multiply by 3 and subtract seed
Check if result is 3-digit number
Check if middle digit equals seed

Complexity:
Time: O(1)
Space: O(1)

## Question 3: Mirror Corridor
Logic:
Try values of X from 0 to 100000
Check if N + X is palindrome
Check if divisible by K
Print smallest X

Complexity:
Time: O(N)
Space: O(1)

## Question 4: Fare Calculator
Logic:
Calculate base fare
Add late fee if needed
Add 10% if distance > 10
Adjust based on seed (odd/even)
Round up to nearest multiple of 5

Complexity:
Time: O(1)
Space: O(1)

## Question 5: Skipping Numbers
Logic:
Add numbers from 1 onwards
Skip numbers divisible by (seed + 2)
Stop when sum ≥ N

Complexity:
Time: O(m)
Space: O(1)

## Question 6: Contest Score Judge
Logic:
Calculate score using formula
Handle negative score
Apply penalty if total answers > 50
Decide PASS or FAIL

Complexity:
Time: O(1)
Space: O(1)
