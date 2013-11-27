---
layout: hw
title: Homework 24 - Radix sort vs built in sort
published: true
---

### Part 1

Get your Radix sort working. Remember, you have to cast to copy the stuff from the ArrayLists back into the array: ```a[i]=(Integer)buckets[j].get(k)```.


### Part 2

Java has a built in sorting routine for Arrays. Try the following in a Driver -

    int[] a = {5,3,67,2,11,787,3,6,1};
	System,out.println(Arrays.toString(a);
	Arrays.sort(a);
	System,out.println(Arrays.toString(a);

You want to compare the Radix sort you wrote to the built in Arrays.sort().

Try data sets that are both different sizes and different numbers of digits to see when the two sorts are basically the same and when one is slower or faster than the other.

You might try:
 * An array of 10,000 3 digit numbers
 * An array of 100,000 3 digit numbers
 * An array of 1,000,000 3 digit numbers
 * An array of 10,000 20 digit numbers (you might have to move from int to long to do this)
 * An array of 100,000 20 digit numbers
 * An array of 1,000,000 20 digit numbers

etc.


You don't have to submit anything to GitHub but write down your
results. We'll discuss them no Monday.

Enjoy the holiday weekend!!!!
