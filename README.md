# 0x1B. C - Sorting algorithms & Big O

# Sorting algorithm

sorting algorithm is an algorithm that puts elements of a list into an order. The most frequently used orders are numerical order and lexicographical order, and either ascending or descending. Efficient sorting is important for optimizing the efficiency of other algorithms (such as search and merge algorithms) that require input data to be in sorted lists. Sorting is also often useful for canonicalizing data and for producing human-readable output.

the output of any sorting algorithm must satisfy two conditions:

1 The output is in monotonic order (each element is no smaller/larger than the   previous element, according to the required order).

2. The output is a permutation (a reordering, yet retaining all of the original   elements) of the input.


# Requirements

General

. Allowed editors: vi, vim, emacs

. All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the opti ons -Wall -Werror -Wextra -pedantic -std=gnu89

. All your files should end with a new line

. A README.md file, at the root of the folder of the project, is mandatory

. Your code should use the Betty style. It will be checked using betty-style.pl  and betty-doc.pl

. You are not allowed to use global variables

. No more than 5 functions per file

. Unless specified otherwise, you are not allowed to use the standard library.   Any use of functions like printf, puts, … is totally forbidden.

. In the following examples, the main.c files are shown as examples. You can us  e them to test your functions, but you don’t have to push them to your repo (  if you do we won’t take them into account). We will use our own main.c files   at compilation. Our main.c files might be different from the one shown in the  examples

. The prototypes of all your functions should be included in your header file c  alled sort.h

. Don’t forget to push your header file

. All your header files should be include guarded

. A list/array does not need to be sorted if its size is less than 2.

. O(1)

. O(n)

. O(n!)

. n square -> O(n^2)

. log(n) -> O(log(n))

. n * log(n) -> O(nlog(n))

. n + k -> O(n+k)