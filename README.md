# Process Writeup

## Name: Josiah Benitez
## Course: SEP12
## Period: 7
## Concept: Unit 5

### Overview

In this Unit we learned about different types of methods and also constructors. We also had lessons about Primitive vs Class and how they interact as parameters.
## First Challenge
### Constructor Challenge

On the Unit 5 exam I got question 9 wrong because I didnt realize that the answer I had picked would cause the constructor to continuosly call itself because there are no other constructors that take two string parameters. I picked this `this(name, ssn);`


## Second Challenge
### Short Circuit Evaluation 

On question 6 it mainly came down to not having enough time and panicking to getting an answer down. Looking at this question now it definitely was one of the easier ones on the exam for me but I didnt have enough time so I messed up. This was the code:

    
 ```java 
    if (a < b && c != d)
{
  System.out.print("True");
}
   ```

I know already that booleans evaluate left to right and if a < b is false then automatically it makes the boolean false because it is using "&&" so if one is wrong then automatically both of them cant be right making it false. Another example would be:

```java
  if(chickens == cows || chickens == dogs)
{
System.out.print("True");
}
```
This example would automatically be true if chickens == cows and it would be false if chickens and cows werent equivalent as well as chickens and dogs not being equal. This is because it uses an "or" type of boolean so if one of the two booleans are true then the output is true and the condition is met.
### Takeaways

* Read keywords of questions on an exam so you can evaluate if you have the knowledge and time to fully and correctly complete the question or if it would be best to go to another question, this takeaway comes from my loss of a point on question 6 because I didnt have enough time.
* Short circuit evaluation is a great way to see the outcome of booleans without having to go through each outcome of the boolean.
* Look over every part of loops when you are trying to find the value of it or its ability to replace other code because one different "-" symbol or anything can make it wrong. I saw this on my mistake with the result string on question 18 and the for loop.
