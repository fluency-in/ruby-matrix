# Ruby: Matrix

Write a program that, given a string representing a matrix of numbers, can return the rows and columns of that matrix.

So given a string with embedded newlines like:

> 9 8 7
> 5 3 2
> 6 6 7

representing this matrix:

```plain
    0  1  2
  |---------
0 | 9  8  7
1 | 5  3  2
2 | 6  6  7
```

your code should be able to spit out:

- A list of the rows, reading each row left-to-right while moving
  top-to-bottom across the rows,
- A list of the columns, reading each column top-to-bottom while moving
  from left-to-right.

The rows for our example matrix:

- 9, 8, 7
- 5, 3, 2
- 6, 6, 7

And its columns:

- 9, 5, 6
- 8, 3, 6
- 7, 2, 7

The tests use the Minitest testing framework. To install it run the command:

    gem install minitest

Run the tests with the `ruby` command:

    ruby matrix_test.rb

## Resources

If you have never used Minitest, check out [Intro to TDD][tdd] tutorial from Jumpstart Lab.

[tdd]: http://tutorials.jumpstartlab.com/topics/testing/intro-to-tdd.html

## Source

Warmup to the `saddle-points` warmup. [http://jumpstartlab.com](http://jumpstartlab.com)

This exercise is from the [Ruby][ruby] track on [Exercism][exercism]

[exercism]: http://exercism.io
[ruby]: http://exercism.io/languages/ruby



