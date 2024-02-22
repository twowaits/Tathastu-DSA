# Arrays
An array is a collection of similar data items stored at contiguous memory locations. The idea is to store multiple items of the same type together. This makes it easier to calculate the position of each element by simply adding an offset to a base value, i.e., the memory location of the first element of the array (generally denoted by the name of the array).

# Why use arrays

1. Arrays allow random access to elements. This makes accessing elements by position faster.
2. Arrays have better cache locality that makes a pretty big difference in performance.
3. Arrays represent multiple data items of the same type using a single name.

## Declaration and initialisation of an array in C/C++/Java

*datatype arrayname = { the set of values };*

**Example**
int arr[] = {10, 20, 30, 40, 50};<br>
We can access different elements of this array as --> <br>
arr[0] --> means the first element of the array and so on.<br>
Usually, an array of characters is called a ‘string’, whereas an array of ints or floats is simply called an array.


References - GeeksForGeeks <a href="https://www.geeksforgeeks.org/introduction-to-arrays/" color="blue">Visit </a>
