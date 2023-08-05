# Gaussian_elimination
Libraries: The code includes several header files and defines some constants.

Function Prototypes: The code declares function prototypes for functions used in the main program.

Main Function: The main function takes a command-line argument matrix_size, which specifies the size of the square matrix to be processed. It then allocates memory for three matrices: A, U_reference, and U_mt. The A matrix is populated with random values, and its contents are copied to U_reference and U_mt matrices.

Gaussian Elimination Using Reference Code: The main function performs Gaussian elimination using a reference (single-threaded) code and measures the CPU run time.

Check for Success: The code checks if the Gaussian elimination using the reference code is successful by verifying that the principal diagonal elements of the upper triangular matrix are 1.

Gaussian Elimination Using OpenMP: The main function needs to call the gauss_eliminate_using_omp function to perform Gaussian elimination using OpenMP. This is the missing part that you need to implement.

Check Results: After Gaussian elimination using OpenMP, the code compares the results obtained with the reference solution using the check_results function to ensure they match within a specified tolerance.

Memory Cleanup: The main function frees the memory allocated for the matrices before exiting.
