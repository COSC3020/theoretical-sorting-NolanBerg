[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/9YUeXH71)
# Theoretical Sorting

A Computer Science researcher claims to have come up with a sorting algorithm
that can sort arbitrary elements in $O(n)$ time based on comparisons of two
elements at a time. This would be asymptotically faster than any known general
sorting algorithm. The algorithm itself is proprietary and will be sold by a
company.

How would you verify this claim? You may assume that you have access to a
black-box implementation of the sorting algorithm, i.e. you cannot examine the
source code, but you can use it to sort any list you like. Explain in detail
your method for investigating whether X is correct, including any expected
results you would get.

Also give a theoretical argument for why X could or could not be correct, based
on the complexity of the general sorting problem we covered in class.

Add your answers to this markdown file.

Sources: Used google to help with this assignment

Here are the steps I would take based on the information given:

Generate Test Cases:

   - Create a variety of test cases consisting of lists of different sizes (small, medium, large) and with different characteristics (sorted, reverse-sorted, random) making sure to include edge cases to show the algorithm handles boundary conditions.

Perform Sorting:

   - I would use the black-box implementation of the sorting algorithm to sort each test case and record the time taken to sort each case.

Compare Results:

   - I would then compare the recorded sorting times against the expected time complexity of $( O(n) )$.

Statistical Analysis:

   - The next step would be to compute the average and standard deviation of the sorting times across all test cases, as well as look for any patterns or anything unusual in the results.

Evaluate Stability:

   - Finally I would test the algorithm with increasingly larger input sizes to see how the sorting time scales.

