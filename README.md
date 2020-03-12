# Fizzbuzz *(part 1)*

Makers week 4 pre course challenge. Introduction to Test Driven Development (TDD) and Pair Programming. 

The objective of Fizzbuzz challenge is to create a program with the following specification:

* The program can be passed a number.
* When passed a number that is a multiple of 3, the program returns the message 'Fizz'.
* When passed a number that is a multiple of 5, the program returns the message 'Buzz'.
* When passed a number that is a multiple of both 3 and 5, the program ignores the previous 2 rules and returns the message 'Fizzbuzz'.
* In all other cases, the program simply returns the given number.

After completion of the exercise, a new repository is created with new specifciation. The second part of the challenge can be found here:

[Fizzbuzz - part 2](https://github.com/FayeCarter/fizzbuzz_2)

## How to use ##

```shell
# in irb run
require './lib/fizzbuzz'

# To test a fizzbuzz on a specific Integer *'3'*
fizzbuzz(3)

# To test fizzbuzz accross a range of 1 to 10
(1..10).each { |num| puts "fizzbuzz #{num} --> #{fizzbuzz(num)}" } 
```
