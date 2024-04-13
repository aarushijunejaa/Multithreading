# Multithreading

# Threaded Matrix Multiplication

This Python script demonstrates parallel matrix multiplication using threading. It multiplies 100 random matrices of size 1k x 1k with a constant matrix of the same size and reports the average execution time for different numbers of threads.

# Key Features:

Leverages NumPy: Utilizes NumPy's efficient matrix operations for fast calculations.
Thread-based Parallelization: Employs threading for concurrent execution, potentially improving performance on multi-core processors.
Random Matrix Generation: Generates 100 random matrices for each thread run, simulating a realistic workload.
Performance Analysis: Calculates and displays the average execution time for each tested number of threads, helping you assess the impact of parallelization.

# Requirements:

Python 3.x
NumPy library (install using pip install numpy)

# Output:

The script will generate a table showing:

Thread Count (T): The number of threads used for parallel execution.
Average Execution Time (seconds): The average time it takes to multiply the matrices using the specified number of threads.


# Understanding the Results:

The execution time generally decreases as the number of threads increases, up to a certain point where thread management overhead might outweigh the benefits. The optimal number of threads depends on your hardware configuration and workload size.
