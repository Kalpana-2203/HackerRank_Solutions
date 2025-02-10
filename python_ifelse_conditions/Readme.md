This Python program classifies a given integer n as 'Weird' or 'Not Weird' based on specific conditions.
The program checks if the number is odd or even, and further categorizes even numbers within certain ranges (2-5, 6-20, or greater than 20) with corresponding outputs. 
This solution is designed to print whether a given integer n is "Weird" or "Not Weird" based on specific conditions. The solution uses conditional statements (if, elif, and else) to categorize n into the following ranges:

Odd number (n % 2 == 1): If the number is odd, it prints "Weird".
Even number between 2 and 5 (inclusive) (2 <= n <= 5): If the number is even and between 2 and 5, it prints "Not Weird".
Even number between 6 and 20 (inclusive) (6 <= n <= 20): If the number is even and between 6 and 20, it prints "Weird".
Even number greater than 20 (n > 20): If the number is even and greater than 20, it prints "Not Weird".

Sample Input 0

3
Sample Output 0

Weird
Explanation 0
n = 3

n is odd and odd numbers are weird, so print Weird.

Sample Input 1

24
Sample Output 1

Not Weird
