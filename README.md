# HackerRank

## Sock Merchant

[https://www.hackerrank.com/challenges/sock-merchant/problem](https://www.hackerrank.com/challenges/sock-merchant/problem)

John works at a clothing store. He has a large pile of socks that he must pair by color for sale. Given an array of integers representing the color of each sock, determine how many pairs of socks with matching colors there are.

For example, there are `n = 7` socks with colors `ar = [1, 2, 1, 2, 1, 3, 2]` . There is one pair of color `1` and one of color `2` . There are three odd socks left, one of each color. The number of pairs is `2`.

## Utopian Tree

[https://www.hackerrank.com/challenges/utopian-tree/problem](https://www.hackerrank.com/challenges/utopian-tree/problem)

The Utopian Tree goes through 2 cycles of growth every year. Each spring, it doubles in height. Each summer, its height increases by 1 meter.

Laura plants a Utopian Tree sapling with a height of 1 meter at the onset of spring. How tall will her tree be after `n` growth cycles?

For example, if the number of growth cycles is `n = 5` , the calculations are as follows:

```
Period  Height
0          1
1          2
2          3
3          6
4          7
5          14
```

## Chocolate Feast

[https://www.hackerrank.com/challenges/chocolate-feast/problem](https://www.hackerrank.com/challenges/chocolate-feast/problem)

Little Bobby loves chocolate. He frequently goes to his favorite 5 & 10 store, Penny Auntie, to buy them. They are having a promotion at Penny Auntie. If Bobby saves enough wrappers, he can turn them in for a free chocolate.

For example, Bobby has `n = 15` to spend on bars of chocolate that cost `c = 3` each. He can turn in `m = 2` wrappers to receive another bar. Initially, he buys `5` bars and has `5` wrappers after eating them. He turns in `4` of them, leaving him with `1`, for `2` more bars. After eating those two, he has `3` wrappers, turns in `2` leaving him with `1` wrapper and his new bar. Once he eats that one, he has `2` wrappers and turns them in for another bar. After eating that one, he only has `1` wrapper, and his feast ends. Overall, he has eaten `5 + 2 + 1 + 1 = 9` bars.

## Find Digits

[https://www.hackerrank.com/challenges/find-digits/problem](https://www.hackerrank.com/challenges/find-digits/problem)

An integer `d` is a divisor of an integer `n` if the remainder of `n / d = 0` .

Given an integer, for each digit that makes up the integer determine whether it is a divisor. Count the number of divisors occurring within the integer.

**Note:** Each digit is considered to be unique, so each occurrence of the same digit should be counted (e.g. for `n = 111`, `1` is a divisor of `111` each time it occurs so the answer is `3`).

## Cut the Sticks

[https://www.hackerrank.com/challenges/cut-the-sticks/problem](https://www.hackerrank.com/challenges/cut-the-sticks/problem)

You are given a number of sticks of varying lengths. You will iteratively cut the sticks into smaller sticks, discarding the shortest pieces until there are none left. At each iteration you will determine the length of the shortest stick remaining, cut that length from each of the longer sticks and then discard all the pieces of that shortest length. When all the remaining sticks are the same length, they cannot be shortened so discard them.

Given the lengths of `n` sticks, print the number of sticks that are left before each iteration until there are none left.

For example, there are `n = 3` sticks of lengths `arr = [1, 2, 3]`. The shortest stick length is `1`, so we cut that length from the longer two and discard the pieces of length `1`. Now our lengths are `arr = [1, 2]`. Again, the shortest stick is of length `1`, so we cut that amount from the longer stick and discard those pieces. There is only one stick left, `arr = [1]`, so we discard that stick. Our lengths are `answer = [3, 2, 1]`.

## Service Lane

[https://www.hackerrank.com/challenges/service-lane/problem](https://www.hackerrank.com/challenges/service-lane/problem)

Calvin is driving his favorite vehicle on the 101 freeway. He notices that the check engine light of his vehicle is on, and he wants to service it immediately to avoid any risks. Luckily, a service lane runs parallel to the highway. The service lane varies in width along its length.

You will be given an array of widths at points along the road (indices), then a list of the indices of entry and exit points. Considering each entry and exit point pair, calculate the maximum size vehicle that can travel that segment of the service lane safely.

For example, there are `n = 4` measurements yielding `width = [2, 3, 2, 1]`. If our entry index, `i = 1` and our exit, `j = 2`, there are two segment widths of `2` and `3` respectively. The widest vehicle that can fit through both is `2`. If `i = 2` and `j = 4`, our widths are `[3, 2, 1]` which limits vehicle width to `1`.

## Caesar Cipher

[https://www.hackerrank.com/challenges/caesar-cipher-1/problem](https://www.hackerrank.com/challenges/caesar-cipher-1/problem)

Julius Caesar protected his confidential information by encrypting it using a cipher. [Caesar's cipher](https://en.wikipedia.org/wiki/Caesar_cipher) shifts each letter by a number of letters. If the shift takes you past the end of the alphabet, just rotate back to the front of the alphabet. In the case of a rotation by 3, w, x, y and z would map to z, a, b and c.

```
Original alphabet:      abcdefghijklmnopqrstuvwxyz
Alphabet rotated +3:    defghijklmnopqrstuvwxyzabc
```

For example, the given cleartext `s = There's-a-starman-waiting-in-the-sky` and the alphabet is rotated by `k = 3`. The encrypted string is `Wkhuh's-d-vwdupdq-zdlwlqj-lq-wkh-vnb`.

**Note:** The cipher only encrypts letters; symbols, such as `-` or `'`, remain unencrypted.

## Library Fine

[https://www.hackerrank.com/challenges/library-fine/problem](https://www.hackerrank.com/challenges/library-fine/problem)

Your local library needs your help! Given the expected and actual return dates for a library book, create a program that calculates the fine (if any). The fee structure is as follows:

1. If the book is returned on or before the expected return date, no fine will be charged (i.e.: `fine = 0` ).
1. If the book is returned after the expected return day but still within the same calendar month and year as the expected return date, `fine = 15 Hackos x (the number of days late)`.
1. If the book is returned after the expected return month but still within the same calendar year as the expected return date, the `fine = 500 Hackos x (the number of months late)`.
1. If the book is returned after the calendar year in which it was expected, there is a fixed fine of `10000 Hackos`.

Charges are based only on the least precise measure of lateness. For example, whether a book is due January 1, 2017 or December 31, 2017, if it is returned January 1, 2018, that is a year late and the fine would be `10000 Hackos`.
