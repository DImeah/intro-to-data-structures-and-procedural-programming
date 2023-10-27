# intro-to-data-structures-and-procedural-programming

This algoritm solves an array problem when given two sets of elements, it finds the sum of all distinct elements from both set.

It also contains an algoritm which calculates in the variable ps, the dot(scalar) product of v1 and v2 (v1 and v2 are vectors of IR)
Write an algorithm which determines, for n pairs of given vectors, whether two vectors of given IR are orthogonal, by calling the procedure defined in the previous question. The dot product of two orthogonal vectors is zero.

# array_comparator function

1. Line 1 Defines the algorithm as find_distinct_sum.
2. Lines 2 - 7 defines variables (arrays, integers).
3. Lines 9 initilizes the variable sum to zero.
4. Lines 12 - 15 recieves input from the user.
5. Lines 18 - 25 creates a for loop that iterates through set2 by looping through the index of set1. It checks for distinct values in set1 and appends it to an array distinct_elements.
6. Lines 28 - 35 creates a for loop that iterates through set1 by looping through the index of set2. It checks for distinct values in set2 and and appends it to an array distinct_elements.
7. Lines 42 - 44 iterates through distinct_elements and sums up the values of each index in the array.

# dot_product algoritm

1. Line 1 defines the algorithm dot_product.
2. Lines 2 - 5 defines variables (arrays of type integer and integer).
3. Lines 7 - 8 reads values to be processed.
4. Lines 9 calls a product_of_vectors function that receives 2 arguments of type array.
5. Lines 14 defines a function product_of_vectors that receives 2 parameters of type array.
6. Lines 16 defines local variables in the function.
7. Lines
