# Python homeworks

1. Define a function, that takes string as argument and prints `"Hello, %arg%!"`
2. Define a function `sum()` and a function `multiply()` that sums and multiplies (respectively) all the numbers in a list of numbers. For example, `sum([1, 2, 3, 4])` should return 10, and `multiply([1, 2, 3, 4])` should return 24.
3. Define a function `reverse()` that computes the reversal of a string. For example, `reverse("I am testing")` should return the string "gnitset ma I". Do not use python array reversal, practice a loop.
4. Define a function `is_palindrome()` that recognizes palindromes (i.e. words that look the same written backwards). For example, `is_palindrome("radar")` should return True.
5. Define a procedure `histogram()` that takes a list of integers and prints a histogram to the screen. For example, `histogram([4, 9, 7])` should print the following:

```
****
*********
******
```

(usage of time.sleep(s) is possible for better visualization)

6. Define a function `caesar_cipher` that takes string and `key(number)`, whuch returns encrypted string. More about [Ceasar Cipher](https://en.wikipedia.org/wiki/Caesar_cipher)
7. define a function `diagjnal_reverse()` that takes matrix and returns diagonal-reversed one:

```
1 2 3         1 4 7
4 5 6 returns 2 5 8
7 8 9         3 6 9
```

8. Write a function `game()` number-guessing game, that takes 2 int parameters defining the range. Using `random.randint(A, B)` generate random int from the range. While user input isn't equal that number, print "Try again!". If user guess the number, congratulate him and exit. (use `raw_input()`)

9. Define a function, which takes a string with N opening brackets `("[") and N closing brackets ("]")`, in some arbitrary order.
Determine whether the generated string is balanced; that is, whether it consists entirely of pairs of opening/closing brackets (in that order), none of which mis-nest.
Examples:

```
   []        OK   ][        NOT OK
   [][]      OK   ][][      NOT OK
   [[][]]    OK   []][[]    NOT OK
```

10. Write a function `char_freq()` that takes a string and builds a frequency listing of the characters contained in it. Represent the frequency listing as a Python dictionary. Try it with something like `char_freq("abbabcbdbabdbdbabababcbcbab")`.

11. Write a function `dec_to_bin()` that taces decimal integer and outputs its binary representation. Write custom implementation

12. Create your own [Tree data structure](https://medium.com/the-renaissance-developer/learning-tree-data-structure-27c6bb363051) in Python (or use google to find some). It should be able to add new elements, delete elements, search elements.

13. *hard task* Create a Django App to be able to access your tree to create, delete, update and get element of your tree using REST API using `curl` (Django rest framework) or Templates using your favourite browser (Django templates)
