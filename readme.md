## Function Description:
Complete the functions below. All methods must work with matrices of the double type.

Constraints:

```
0 < m < 10
0 < n < 10

where m - number of rows in matrix 
where n - number of columns in matrix
```

In case of incorrect input values or inability to perform a calculation, the method should throw MatrixProcessorException
exception.

## double[][] transpose(double[][] matrix)
Matrix transpose is an operation on a matrix where its rows become columns with the same numbers.

        [ 1 2 ]         [ 1 3 5 ]    
        [ 3 4 ]  ===>   [ 2 4 6 ]    
        [ 5 6 ]         

## double[][] turnClockwise(double[][] matrix)
The method flips the matrix clockwise.

        [ 1 2 ]         [ 5 3 1 ]    
        [ 3 4 ]  ===>   [ 6 4 2 ]    
        [ 5 6 ]         

## double[][] multiplyMatrices(double[][] firstMatrix, double[][] secondMatrix)
This method multiplies matrix firstMatrix by matrix secondMatrix

See [Matrix multiplication](https://en.wikipedia.org/wiki/Matrix_multiplication)

## double[][] getInverseMatrix(double[][] matrix)
This method returns the inverse of the matrix

See [Invertible matrix](https://en.wikipedia.org/wiki/Invertible_matrix)

## double getMatrixDeterminant(double[][] matrix)
This method returns the determinant of the matrix

See [Determinant](https://en.wikipedia.org/wiki/Determinant)