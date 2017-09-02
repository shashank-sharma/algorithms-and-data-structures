1. Time Complexity Analysis & Space complexity (Notes)

Space complexity is measured in terms of the largest amount of memory used during runtime.
If no additional space being utilised, the space complexity is constant.

If iteration goes i/2 each time then after x iteration - N/2^x. So it iwll be N/2^x < 1 and 2^x > N means x = log(N)

Worst case for searching algorithm always make sure that what if all the values are same.

In for loops if third variable is used inside, always make sure if they are reinitialized or not.


##Data Structures

###Arrays

Pointers: Variables that store address of another variable.

int *p;

p is a variable which will store address of integer type.

p = &a; // p now have address of a

Now if we print p then it will give address of a. If we want value where it points to then we need to dereference it by using *p.

p - Address and p* - value at address


Arrays: Collection or systematic arrangement of similar data type.

Advantages: Easy to access values, accessing or modifying takes O(1) (how? It calculate Address using base address and offset).

Array a = a pointer to first element
A[0] = *A, A[1] = *(A+1), A[2] = *(A+2) ...

