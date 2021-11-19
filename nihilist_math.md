## Mathematical Analysis

### How many possible keys or codes could there be? 
* Up to 110 keys possible

### How would you attempt to decode this message if you didn't have a key? 
1. Discover the length of the secret key by trying possible key lengths for probable values, such as 4 to 15 characters. 
2. Write the ciphertext for each of the numbers, which will have created tables that have numbers of columns equal to the current lengths of the secret key. 
3. Check the numbers in all of its columns - the numbers in each column should have both tens and ones digits that differ from each other no more than 5. 
4. Only use the tables that satisfy the conditions of:
* Tens digits nad ones digit don't differ from each other more than 5
5. Determine possible key numbers:
* For each column, find all possible numbers, which subtracted from all ciphertext numbers in the column result in numbers from the values 11 to 55. 
* Any numbers that don't satsify the condition should be discarded.
6. For each correct solution, create all possible encrypting keys and subtract them from the ciphertext, which will get you the potential plaintext letters.

### What is the mathematical complexity to solve the code?
* The math complexity for solving the code if you know the key is not difficult:
* After the ciphertext has been created and added to the plaintext numbers to the secret key numbers:
* The recipient, who knows the secret key, subtracts the secret key numbers from the ciphertext numbers. They receive the plaintext numbers, which can be changed into letters using the same table as the sender used for encryption, such as the following:

![Polybius table](https://lh3.googleusercontent.com/proxy/QbQIguUrCUX9L7zGx-darqK61qGRV8IxkHJ8dc0TFbqPiaRDsLcAuCaqeXk6uT1hRuAnDAyp6ANINEPzgY3FadzAsxDgXINzXeknIK28uBnXtX3xUfHp5r7kE2SuQ9K-OgH2KOMpF9y0pWg)
