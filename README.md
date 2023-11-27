# Process Writeup

## Name: Wilson Huang
## Course: APCSA
## Period: 7
## Concept: Unit 3 

### Introduction
In APCSA (Advanced Placement Computer Science A), we are learning about Java. Learning Java is somewhat similar to Javascript; so learning Java has so far been easier due to my background knowledge in JavaScript. In unit 3 we are learning boolean expression and if staements. This has been challenging so far because I also had trouble with for and while loops during JavaScript in this writeup I will take you throught some of the cahllenges I had.  

### Challenge 1
One challegne I had when learning about for and while loops was telling the difference between both and when to use one over the other. During the quiz we had, there was a question asking when to use for and while loops. The question said `"When would it be more beneficial to use a while loop instead of a for loop?"` and I chose` "Whenever you need to do repeated calculations with a variable"`. This is incorrect because they both can repeat calculations. I realized after the test that while loops are used when you don't know when the loop ends and for loops do it for a certain amount of times. 
#### While loop
```js
while(x != 0){
  System.out.println("Hello world"); // Does this infinity amount of times as long x does not equal to 0
}
```
#### For loop
```js
for(int i = 1; i >= 10; i++){
  System.out.println("Hello world"); // Does this for 10 times and stops when i is greater than 10
}
```

### Challenge 2 -
Another challenge that I had is with truth tables; I found this topic to be confusing and challenging to learn. In the truth table `!False` would equal to true and `!True` would equal to false. For this topic I came up with a method. `!` is negative, `false ` is negative, and `true` is positive. For example `!False` would equal to `- -` this would equal to a positive since negative multipled by a negative would equal to a postive. In the exam I got a question wrong similar to this. 

### Challenge 3
For this challenge I answered a question in the exam wrong. Take a look below
```js
Car Honda = new Car(4, 2);
Car Mercedes = new Car(4, 2);

if (Honda == Mercedes) 
{
    System.out.print("equal ");
} 
else 
{
    System.out.print("not equal ");
}
```
For this question I answered equal since I thought Car(4, 2) == Car(4, 2). However I was wrong because they are not the same object. It is like having a physical Honda and Mercedes they are a car but they are different. 

### Takeaways
* If you have trouble memorzing something, come up with a unique way in which you can memorize it. For example I didn't understand truth value so I imagined `!` and `false` as negatives and `true` as postive. 
