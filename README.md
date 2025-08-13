# expt-8-multidimensional-array

Lab Experiment 8 – Multidimensional Arrays in C++

Aim:
To study and implement C++ multidimensional arrays with various matrix operations.

Apparatus:
VS Code or any C++ Compiler 

Theory

A multidimensional array is an array of arrays, commonly used to represent data in a tabular (rows and columns) form.

2D arrays are widely used for matrix representation in mathematics, scientific computing, graphics, and data analysis.

Storage: Stored in row-major order in memory for efficient access.

Access: Constant time  using indices [row][column].

Algorithm 

Program 1: Take Input and Display a 3×3 Matrix

Algorithm:

1. Declare a 3×3 integer array.


2. Read elements using nested loops.


3. Display elements in matrix form.

Program 2: Addition of Matrices

Algorithm:

1. Input dimensions (same for both matrices).


2. Read elements of both matrices.


3. Add element-wise: sum[i][j] = mat1[i][j] + mat2[i][j].


4. Display result.

Program 3: Multiplication of Matrices

Algorithm:

1. Read dimensions for both matrices.


2. Ensure columns of first = rows of second.


3. Multiply using formula

Program 4: Matrix Transpose

Algorithm:

1. Read dimensions and matrix elements.


2. Swap indices: transpose[j][i] = mat[i][j].

Program 5: Sum of Diagonal Elements

Algorithm:

1. Read square matrix elements.


2. Sum mat[i][i] for main diagonal.


3. Optionally, sum mat[i][n-1-i] for secondary diagonal.

Program 6: Compare First Row and Second Row Elements

Algorithm:

1. Read matrix elements.


2. Compare mat[0][j] with mat[1][j] for each column.


3. Display relation (>, <, =) for each position.




Applications:

Scientific computing and simulations

Graphics transformations (rotation, scaling)

Machine learning data representation

Game development (2D grids, tile maps)

Conclusion:

In this experiment, we successfully implemented various operations on multidimensional arrays in C++ such as matrix input/output, addition, multiplication, transpose, diagonal sum, and row comparison. The programs demonstrated the use of nested loops, index-based element access, and dimension validation.

