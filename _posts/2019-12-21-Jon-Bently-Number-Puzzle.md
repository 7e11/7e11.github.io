---
layout: post
title: Jon Bently's Number Puzzle
published: false
---

[Jon Bently](https://en.wikipedia.org/wiki/Jon_Bentley_(computer_scientist)) gave a guest lecture in our algorithms class (CSE 340), 
in the 2019 Fall semester.
He examined the [Traveling Salesperson Problem (TSP)](https://en.wikipedia.org/wiki/Travelling_salesman_problem) 
with us and we wrote an unoptimized algorithm to solve it.
Over the course of the class, we suggested improvements to our program, 
and we gradually increased the number of cities we could solve for in a reasonable amount of time.
I'll discuss the real content of the lecture in another blog post. In this one, 
we'll look at a relatively easy problem he proposed early on in the lecture.

> Find all permutations of 1..9 such that each initial substring of length m is divisible by m


Interesting ideas with computer science:
- More abstraction (or incorrect abstraction) -> less performance.
  - Compare python functional tools with a for loop.
- Difficult to think about things in a funcitonal way.
- While in life we may think that simple is good and fast, this shows that complex solutions may be even faster.
  - Concorde vs. our code.
