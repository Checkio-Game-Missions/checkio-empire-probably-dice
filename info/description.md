Typically, when using multiple dice, you simply roll them and sum up all the result.
To get started with your investigation of dice probability, write a function that takes the number of dice,
the number of sides per die and a target number and
returns the probability of getting a total roll of exactly the target value.
The result should be given with four digits precision as &plusmn;0.0001.
For example, if you roll 2 six-sided dice, the probability of getting exactly a 3 is 2/36 or 5.56%,
which you should return as &asymp;0.0556.

![Image](distribution.svg)

For each test, assume all the dice are the same and are numbered from 1 to the number of sides, inclusive.
So a 4-sided die (D4)  would have an equal chance of rolling a 1, 2, 3 or 4.
A 20-sided die (D20) would have an equal chance of rolling any number from 1 to 20.


**Tips:** Be careful if you want to use a brute-force solution -- you could have a very, very long wait for edge cases.
