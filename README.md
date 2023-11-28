# Process Writeup

## Name: Wilson Huang
## Course: APCSA
## Period: 7
## Concept: Unit 3 

### Introduction
In APCSA (Advanced Placement Computer Science A), we are learning about Java. Learning Java is somewhat similar to Javascript; so learning Java has so far been easier due to my background knowledge in JavaScript. In unit 3 we are learning boolean expression and if staements. This has been challenging so far because I also had trouble with for and while loops during JavaScript in this writeup I will take you throught some of the cahllenges I had.  


### Challenge 1
Another challenge that I had is with truth tables; I found this topic to be confusing and challenging to learn. In the truth table `!False` would equal to true and `!True` would equal to false. For this topic I came up with a method. `!` is negative, `false ` is negative, and `true` is positive. For example `!False` would equal to `- -` this would equal to a positive since negative multipled by a negative would equal to a postive. In the exam I got a question wrong similar to this. 
```js
!A || !B = -+ || -- = True


```
### Challenge 2
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
For this question I answered equal since I thought Car(4, 2) == Car(4, 2). However I was wrong because they are not the same object. It is like having a physical Honda and Mercedes they are both a car but they are different kinds and looks.

### Challenge 3
In this challenge I will show what I got wrong on my exam.
```
A|B
1 1 = 1
1 0 = 1
0 1 = 1
0 0 = 0
```
I had to plug in the values in the equation as 1 = True and 0 = False. I got this question wrong and the correct answer is A || (A || !B). Below I will show you my work

```
True || ____ = True //Used short circut method
True || ____ = True //Used short circut method
False || True = True
False || False = False
```
### Takeaways
* If you have trouble memorzing something, come up with a unique way in which you can memorize it. For example I didn't understand truth value so I imagined `!` and `false` as negatives and `true` as postive.
* Always plug in values when you can so you know it is 100% right
* Review your notes and project stem before a test
