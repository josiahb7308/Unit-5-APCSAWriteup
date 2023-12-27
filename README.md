# Process Writeup

## Name: Josiah Benitez
## Course: SEP12
## Period: 7
## Concept: Unit 5

### Overview

In this Unit we learned about different types of methods and also constructors. We also had lessons about Primitive vs Class and how they interact as parameters.
## First Challenge
### Constructor Challenge

On the Unit 5 exam I got question 9 wrong because I didnt realize that the answer I had picked would cause the constructor to continuosly call itself. I picked this choice `this(name, ssn);` because I made the mistake of not realizing that this was the only constructor that took in two strings as parameters so due to this it will just keep calling itself.. The correct answer was `name = n; ssn = s;` this is because this choice sets the name and ssn to the values passed into the constructor.


## Second Challenge
### Overthinking Obstacle

On question 15 I overthought this question so much that I changed the right answer I already selected into the wrong one. The answer I picked last which was wrong is the choice that says the procedure will work fine and nothing will be wrong, I was double checking my answers and I felt as if I picked the wrong answer even though I picked the right one so I changed it. The code in question is 
```java
/**
 * @param score - the student’s test score
 * @return the student’s letter grade
 */
public String closeEnough(int score)
  if (score >= 60) 
  {
    return “D”;
  } 
  else if (score >= 70) 
  {
    return “C”;
  } 
  else if (score >= 80) 
  {
    return “B”;
  } 
  else if (score >= 90) 
  {
    return “A”;
  } 
  else 
  {
    return “F”;
  }
```
The correct answer that I originally picked was that a score of 70 would cause the procedure to not work as expected because it would return a D instead of the C that it should actually return. 


## Third Challenge
### Compile-time 

For this challenge I got one of the two choices correct but I was stuck for the other part of the answer so I ended with the wrong answer. The code being looked at is the following:
```java
public class MyClass 
{
   public MyClass()
   {
     /* Implementation not shown */
   }
   public MyClass(int arg1) 
   {
     /* implementation not shown */
   }
   public MyClass(String arg1, int arg2) 
   {
     /* implementation not shown */
   }
}
```
I chose answer 3 which is correct and answer 2 which is wrong, here is why answer 2 is wrong. The constructor in 2 has a parameter which is of a String type, followed by a parameter which is an int. 



### Takeaways

* When dealing with constructors pay close attention to the type of parameters they require and if there are any other constructors taking in the same parameters. This stems from my first challenge where I answered a question wrong because I didnt do this well.
* Short circuit evaluation is a great way to see the outcome of booleans without having to go through each outcome of the boolean.
* Look over every part of loops when you are trying to find the value of it or its ability to replace other code because one different "-" symbol or anything can make it wrong. I saw this on my mistake with the result string on question 18 and the for loop.
