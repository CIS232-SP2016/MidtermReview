# MidtermReview
Labs to help review for the midterm

##Lab #1
Write a file that contains the following content:

```
Bob;200;20.0
Carl;100;12.0
Denise;92;10.0
```

Name it people.ssv (semi-colon separated values).

Write a program to display the average of the 3rd values and display the name of the person with the highest 2nd value.

**This file only has 3 entries, but it could have any number of rows with the same format**

##Lab #2
Import the project from https://github.com/CIS232-SP2016/PolymorphismExample/

Modify the MainApplication class to eat a random item from the items array instead of eating all items in order.

Design a new class that implements Food. You have some creative freedom here. Add at least one of your new Food to the items array in the MainApplication class.

##Lab #3
File Encryption Filter
Write a program that inputs a String message from the user and then asks the user for a key between 1 and 100.
Your program should encrypt the message by adding the key to each character value into a new encoded String.
Create a binary file that stores the key and the encoded String called "secret.msg".

Write a second program that displays the contents of "secret.msg" by reading the key value and the encoded String value.  Then subtract the key from each character to get the original message.
