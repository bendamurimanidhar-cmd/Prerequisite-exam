# Prerequisite-exam

How many multiplications and additions do you need to perform a matrix multiplication between a (n, k) and (k, m) matrix? Explain.

For multiplying a matrix of dimensions n x k by a matrix of dimensions k x m, the resulting product matrix will have dimensions n x m. The calculation of each element in this product matrix requires a specific number of multiplications and additions. Specifically, to determine each of the n x m elements, a dot product operation is performed between a row of the first matrix and a column of the second matrix. This dot product involves k individual multiplications and k-1 additions. Therefore, the total number of multiplications needed for the entire matrix multiplication process is n x m x k, while the total number of additions amounts to n x m x (k-1).
