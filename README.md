# go-exercises

![CodeQL](https://github.com/zkoppert/go-exercises/workflows/CodeQL/badge.svg) ![Go build](https://github.com/zkoppert/go-exercises/workflows/Go%20build/badge.svg) ![Lint Code Base](https://github.com/zkoppert/go-exercises/workflows/Lint%20Code%20Base/badge.svg)

## fizzbuzz
**Problem**

Print the numbers from 1 to 20. However
- if the number is divisible by 3 (say, 9), print the word "fizz" instead of the number.
- if the number is divisible by 5 (say, 10), print the word "buzz" instead of the number.
- if the number is divisible by both 3 and 5 (say, 15) print "fizz buzz" instead of the number.

[Solution](fizzbuzz/fizzbuzz.go)

## even-ended numbers
**Problem**

An even-ended number is a number with the same first and last digits (ex: 1, 11, 121)
How many even ended numbers result from multiplying two four-digit numbers?

[Solution](even-end/even-end.go)

## Maximal value
**Problem**

Given an unordered slice of values called nums, print the maximal value in the slice.

[Solution](max-val/max-val.go)

## Word Count
**Problem**

Given some text, print out how many times each word appears in the text. This should count while being case insensitive.

[Solution](word-count/word-count.go)

## Get URL content type
**Problem**

Write a function that gets a URL and returns the value of Content-Type response HTTP HEADER or error if a GET request cannot be performed.

[Solution](get-url-content-type/get-url-content-type.go)

## Circle
**Problem**

Define a circle struct which has two fields, centerof type point and length of type int. Also create a function the creates circle and returns a pointer to a new circle. A move method should also be created so that points can be moved, and an area method to calculate the area.

[Solution](circle/circle.go)

