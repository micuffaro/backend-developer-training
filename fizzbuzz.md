# Fizzbuzz problem

I want a program that will print the numbers from 0 to 100.

But :)

- When the number is a multiple of 3, instead of the number, it should print the word "Fizz".
- When the number is a multiple of 5, instead of the number, it should print the word "Buzz".
- If the number is a multiple of both 3 and 5, the program should not print the number, but it should print the word "FizzBuzz"

Example:
```
./fizzbuzz
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
// etc etc until 100
```

To check whether a number is a multiple of another, you can use the modulo operator, %.

The modulo operator in C will give the remainder that is left over when one number is divided by another. For example, `23 % 4` will result in `3` since `23` is not evenly divisible by `4`, and a remainder of `3` is left over.

`15 % 4` equals to `3`, because `4` fits in `15` 3 times (12), with a remainder of 3
`16 % 4` equals to `0`, because there is no remainder

Therefore if the result of a modulo operator is equal to 0, it means that number is a multiple of the other.
