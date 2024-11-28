# Algorithm-Analyser
This project specifically focusing on the performance of various sorting algorithms. It includes implementations of fundamental sorting techniques and a benchmarking system to measure their performance.
## Features
1. Sorting Algorithms:

Bubble Sort
Selection Sort
Insertion Sort
Merge Sort
Quick Sort
2. Random Array Generation:

Generates an array of random integers of configurable size and value range.
Facilitates benchmarking on realistic data.
## Performance Analysis:

Uses the <chrono> library to measure the execution time of each sorting algorithm.
Reports the runtime in microseconds for precise comparison.
##Interactive Code Example:

A self-contained main function that generates a random array, sorts it using different algorithms, and outputs timing results to the console.
## working of projects
1. The program generates a random array using the generateRandomArray function.
2. Each sorting algorithm is applied to the array.
3. The analyzeSort function measures the runtime for each algorithm.
4. Timing results are printed to the console for comparison.
## Sample Output
Array Size: 1000
Bubble Sort took 50321 microseconds.
Selection Sort took 41890 microseconds.
Insertion Sort took 39245 microseconds.
Merge Sort took 11876 microseconds.
Quick Sort took 10432 microseconds.
