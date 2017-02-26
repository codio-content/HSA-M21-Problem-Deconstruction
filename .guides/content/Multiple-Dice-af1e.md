Rather than making another dice file, we can re-use the one that we have already made.  The same dice code can be used for as many dice as necessary.  Below is the code to create die1.  Add this and the code to create die2

```
Dice.roll();
die1 = Dice.getValue();


```
By doing this, we have two dice that are separate but based on the exact same code.

Complete the DiceGame.py program so that it will roll two dice and display each die plus each of the die values then the total point value.  Here is the code to print the value of die1.

```
print("die1 = ", die1);
```

{Test Code}(python DiceGame/DiceGame.py)

|||guidance
# Solution
```
import Dice

#Create two dice

Dice.roll();
die1 = Dice.getValue();
Dice.roll();
die2 = Dice.getValue();

#roll both dice




total = die1 + die2;


#print 
print("die1 = ", die1);
print("die2 = ", die2);

print("total = ", total);
```
|||