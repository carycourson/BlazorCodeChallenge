# Coding Challenge

## Solution Overview
This solution is built using **.NET Version10** and **Blazor Server**.

### Implementation Notes
**Commit History:** I have structured my commits to correspond with specific stages of the challenge. Please review the commit history to see the incremental development of the features along with final refinements and improvements.

---

Complete the three small applications below. Each application should accept input via a graphical user interface (not a console app).

**Note:** You are free to use any UI or framework of your choice (i.e., React, Vue, WPF, JavaFX). 

**Note:** Email  specifically reqested that Blazor and C# be used for this.

---

## 1. Fizz Buzz

Write a program that accepts an integer as input and produces an output for every integer from zero to the input number.

The program should display:

* "fizz" for numbers divisible by 3 
* "buzz" for numbers divisible by 5 
* "fizzbuzz" for numbers divisible by 3 and 5 

### Additional Requirements (complete what you can)

1. **Custom Divisors:** Accept input for the divisors. Check and substitute based on these user input divisors rather than 3 or 5.

2. **Custom Phrases:** Allow the substitute phrases to be changed based on input. That is, allow input to specify what should be displayed instead of "fizz" and "buzz", and combine them just like "fizzbuzz".

---

## 2. Fibonacci Sequence

The Fibonacci Sequence is the sequence of numbers such that $F(n) = F(n-1) + F(n-2)$, where $n$ is the nth number in the sequence.

**Example:** $F(6) = 8$, and the sequence $F(6)$ is ```1, 1, 2, 3, 5, 8```.

**Task:** Write a program that accepts user input, $x$, and outputs the sequence $F(x)$.

### Additional Requirements (complete what you can)

1. Accept input for $y$ and $z$, where:$$F(x) = F(x-y) + F(x-z)$$Like the original sequence, if $F(x-n)$ does not exist yet in the sequence, simply output 1.

---

## 3. Combine the Two

Now, combine the two programs. Accept the following inputs:

* The divisors for "fizz" and "buzz" (if the input is left blank, default to 3 and 5).
* The words for "fizz" and "buzz" (if the input is left blank, default to "fizz" and "buzz").
* Input $x$ for the $F(x)$ sequence.
* Input $y$ and $z$ for $F(x) = F(x-y) + F(x-z)$ (if the input is left blank, use defaults $y=1, z=2$).

**Task:** Using these inputs, display the sequence up to $F(x)$, except displaying your substitute phrases for each $F(n)$ in the sequence according to the divisors you set.

**Example:** Using all defaults for input and $x=6$, $F(6)$ would display: ```1, 1, fizz, buzz, 8```.
