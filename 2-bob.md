## 1. What is the output of the following code snippet?
```java
4: int pig = (short) 4;
5: pig = pig++;
6: long goat = (int)2;
7: goat-=1.0;
8: System.out.println(pig+"-"+goat);
```
A. 4 - 1 *   
B. 4 - 2  
C. 5 - 1  
D. 5 - 2  
E. The code does not compile due to line 7.  
F. None of the above.
---
<br/>  
<br/>  

## 2. What are the unique outputs of the following code snippet? (Choose all that apply)
```java
int a = 2, b = 4, c = 2;
System.out.println(a > 2 ? --c : b++);
System.out.println(b = (a != c ? a : b++));
System.out.println(a > b ? b < c ? b : 2 : 1);
```
A. 1*  
B. 2  
C. 3  
D. 4*  
E. 5*  
F. 6  
G. The code does not compile  
---
<br/>  
<br/>  

# 3. Which is not an output of the following code snippet?
```java
short height = 1, weight = 3;
short zebra = (byte) weight * (byte) height;
double ox = 1 + height * 2 + weight;
long giraffe = 1 + 9 % height +1;
System.out.println(zebra);
System.out.println(ox);
System.out.println(giraffe);
```
A. 2  
B. 3  
C. 6  
D. 6.0  
E. The code does not compile. *
---
<br/>  
<br/>  

## 4. What is the output of the following code?
```java
int sample1 = (2 * 4) % 3;
int sample2 = 3 * 2 % -3;
int sample3 = 5 * (1 % 2);
System.out.println(sample1 + ", " + sample2 + ", " + sample3);
```
A. 0, 0, 5  
B. 1, 2, 10  
C. 2, 1, 5  
D. 2, 0, 5*  
E. 3, 1, 10  
F. 3, 2, 6  
G. The code does not compile.  
---
<br/>  
<br/>  

## 5. The _______ operator increases a value and returns the original value, while the _________ operator decreases a value and returns the new value.  
A. post-increment, post-increment  
B. pre-decrement, post-decrement  
C. post-increment, post-decrement  
D. post-increment, pre-decrement*  
E. pre-increment, pre-decrement  
F. pre-increment, post-decrement  
---
<br/>  
<br/>  

## 6. What is the output of the following code snippet?  
```java
boolean sunny = true, raining = false, sunday = true;
boolean goingToTheStore = sunny & raining ^ sunday;
boolean goingToTheZoo = sunday && !raining;
boolean stayingHome = !(goingToTheStore && goingToTheZoo);
System.out.println(goingToTheStore+"-"+goingToTheZoo+"-"+stayingHome);
```
A. true-false-false  
B. false-true-false  
C. true-true-true  
D. false-true-true  
E. false-false-false  
F. true-true-false*  
G. None of the above  
---
<br/>
<br/>

## 7. Which of the following statements are correct? (Choose all the apply.)  
A. The return value of an assignment operation expression can be void.  
B. The inequality operator `(!=)` can be used to compare objects.*  
C. The equality operator `(==)` can be used to compare a `boolean` value with a `numeric` value.  
D. During runtime, the `&` and `|` operators may cause only the left side of the expression to be evaluated.  
E. The return value of an assigment operation expression is the value of the newly assigned variable.*  
F. In Java, `0` and `false` may be used interchangeably.  
G. The logical complement opereator `(!)` cannnot be used to flip `numeric` values.*  
---
<br/>
<br/>

## 8. Which operator takes three operands or values?  
A. =  
B. &&  
C. *=  
D. ? : *  
E. &  
F. ++  
G. /  
---
<br/>
<br/>

## 9. How many lines of the following code contain compiler errors?  
```java
int note = 1 * 2 + (long) 3;
short melody = (byte) (double) (note *= 2);
double song = melody;
float symphony = (float) ((song == 1_000f) ? song * 2L : song);
```
A. 0  
B. 1*  
C. 2  
D. 3  
E. 4  
---
<br/>
<br/>

## 10. Given the following code snippet, what are the values of the variables after it is executed? (Choose all the apply.)  
```java
int ticketsTaken = 1;
int ticketsSold = 3;
ticketsSold += 1 + ticketsTaken++;
ticketsTaken *= 2;
ticketsSold += (long) 1;
```
A. ticketsSold is 8.  
B. ticketsTaken is 2.
C. ticketsSold is 6.*  
D. ticketsTaken is 6.  
E. ticketsSold is 7.  
F. ticketsTaken is 4.*  
G. The code does not compile.  
---
<br/>
<br/>

