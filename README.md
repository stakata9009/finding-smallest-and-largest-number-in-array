# finding-smallest-and-largest-number-in-array
this simple program uses foreach loop to run through an array of numbers, finding the smallest and largest numbers in the array

This code uses an example array of numbers. We create two int variables to which we assign the values of the first item in the array. After that we run a foreach loop, running through each element in the array comparing the values and thus, finding the smallest and largest number in the array.

It looks like this: foreach (int e in num) - we name each element in the num array as e and then we insert a couple of if statements into the loop: if (min > e) then min = e and basically we compare the current value of min to the current e element from the array. If min is larger than e that means that e is smaller than min. And since we are looking for the smallest number we assign e as the new value of min.

Then we have the else if (max < e) which does the same check but looking for the largest value.
