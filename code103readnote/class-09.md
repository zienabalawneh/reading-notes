# FUNCTIONAL PROGRAMMING

# Concepts of Functional Programming in Javascript


## What is functional programming?

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

## What is a pure function and how do we know if something is a pure function?


1. It returns the same result if given the same arguments (it is also referred as deterministic)

2. It does not cause any observable side effects


## What are the benefits of a pure function?
The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts.

## What is immutability?

Unchanging over time or unable to be changed.

## What is Referential transparency?

+ if a function consistently yields the same result for the same input, it is referentially transparent.


1. **toLowerCase:** converts the string to all lower case
2. **trim:** removes whitespace from both ends of a string
3. **split and join:** replaces all instances of match with replacement in a given string


## What is a module?

+ we split our code up into logical  modules we would have different module for a different  bit of code which has a certain functionality in our application  

## What does the word ‘require’ do?

1. we use the require function and that is on the global object in  nogf

2. pass string it is going to be path to the module 


## How do we bring another module into the file the we are working in?

module.exports= count;

