---
layout: post
title: "How a challenge can be an entire course curriculum"
excerpt: "Maybe the way to learn better is to challenge yourself"
---
It started in a supermarket where I met my friend Virgile Virgelot, majored in Applied Mathematics. He explained me that their professor of Number Theory gave them a challenge and he really wants to do it. The teacher said that if one can make a computer program that can factorize a 100-digits number in less than an hour, one can have at least 80 out of 100 as final grade, without doing any homework, any exam, any quiz, ... without going to class. This was a very interesting challenge called integer factorization https://en.wikipedia.org/wiki/Integer_factorization. Let me explain you guys what it really means: if we take 34, we can decompose it into 2 x 17, simple. Notice that 2 and 17 are prime numbers, which means that they can be divided only by 1 or themselves.
https://en.wikipedia.org/wiki/Prime_number
This leads us to the first mathematical theorem we can learn, the fundamental theorem of arithmetic which says that every integer greater than 1 either is prime itself or is a unique product of prime numbers. https://en.wikipedia.org/wiki/Fundamental_theorem_of_arithmetic

Easy, right ? I give you 45 and you can decompose it like ... 3 x 3 x 5. However, if I give you 1457, you will have to focus a bit and get ... <sup>1</sup>. And 123789 ... <sup>2</sup>. You can see that the more the number become large, the more it's difficult to find the prime numbers; and 41263 is quite a big prime number for "normal" people (not geniuses like Gauss, Riemann, ...). In this case, we have to use a computer to help us, this is why Virgile's professor is asking for a computer program. We will have to tell the computer how to do the integer factorization, so that we just give it a 100-digit integer and it returns us the product of prime numbers just like we did above.

## Integer factorization algorithms
In other words, the algorithm tells us the "how to" or how to decompose an integer. There are many algorithms about that. Some of the most popular ones are the Trial division, the Wheel factorization, Pollard's rho algorithm, Williams' algorithm, Lenstra factorization, Fermat's factorization, Euler's factorization, Dixon's algorithm, etc. The normal question to ask after knowing there are a lot of algorithms is "which one is the best?". It can be the fastest or the one which uses less resources. Generally in computer science (my major), we go for the fastest. So for the 100-digits integers, the fastest known algorithm is the Quadratic Sieve algorithm.  https://en.wikipedia.org/wiki/Quadratic_sieve

## The fastest algorithm known is still slow
There is a concept in computer science called time complexity which is the way to evaluate the time an algorithm takes to run. The Quadratic Sieve algorithm is in the category of the exponential time<sup>3</sup>: it means that the time to run grows very rapidly as the integer gets big. So a computer program using this algorithm will take a long time to decompose a 100-digits integer. Now, you know why Virgile's professor insisted about "less than an hour".

## How does the Quadratic Sieve algorithm work ?




## Your computer has a maximum number and it has 19 digits




## The computer program itself



## Challenges as another way of learning


<sup>1</sup> The result is 31 x 47
<sup>2</sup> The result is 3 x 41263
<sup>3</sup> To be accurate, it is in the sub-exponential time category, which means it's slightly better than an exponential one
