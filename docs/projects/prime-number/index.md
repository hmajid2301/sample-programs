---
title: Prime Numbers in Every Language
layout: default
date: 2018-11-01
last-modified: 2019-01-17
featured-image:
tags: [prime-numbers]
authors:
  - the_renegade_coder
---

A prime number is a positive integer which is divisible only by 1 and itself.
For example: 2, 3, 5, 7, 11, 13

Since every number is divisible by One so, Two is the only even and the
smallest prime number.


## Requirements

Create a file called Prime Number using the naming
convention appropriate for your language of choice.

Write a sample program which accepts an integer on the command line
and outputs if the integer is a Prime number or not.

## Testing

The following table contains various test cases that you can use to verify the 
correctness of your solution:

| Description | Input | Output |
|--------------|-------|--------|
| Negative Case | -7 | Usage: please input a non-negative integer |
| Empty Case | | Usage: please input a non-negative integer |
| Zero Case | 0 | False |
| One Case | 1 | False |
| Two Case | 2 | True |
| Small Composite Case | 4 | False |
| Small Prime Case | 7 | True |
| Large Composite Case | 4011 | False |
| Large Prime Case | 3727 | True |

## Articles

{% include article_list.md collection=site.categories.prime-number %}

## Further Reading

- [Why is the number one not a prime?][2]

[1]: #requirements
[2]: https://primes.utm.edu/notes/faq/one.html
