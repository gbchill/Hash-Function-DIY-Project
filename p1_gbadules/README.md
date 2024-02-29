# Hash Function DIY Project for CSE 310

## Team Information

- **Members**: George Badulescu
- **Team Alias**: gbadules
- **Course**: CSE 310 - Data Structures and Algorithms
- **Semester**: Spring 2024
- **Instructor**: Yiran "Lawrence" Luo

## Project Overview

This project focuses on the design and implementation of a custom hash function and hash table in C++. It employs chaining as a collision resolution strategy. The primary goal is to achieve an efficient distribution of string tokens from an input file across the hash table slots, demonstrating effective hashing techniques.

## Compilation and Execution

Ensure you are on the `general.asu` system or a similar Unix-like environment for compiling and executing this project. Follow the steps below:

1. **Navigate to the Project Directory**:

   ```bash
   cd path/to/CSE310
   ```

2. **Compile the Program**:
   Use the provided `Makefile` for easy compilation:

   ```bash
   make
   ```

   This creates an executable named `encoder`.

3. **Run the Program**:
   Execute with an input file as follows:
   ```bash
   ./encoder < inputs/sample_input.txt
   ```
   Replace `sample_input.txt` with your specific input file path.

## Project Structure

- `main.cpp`: Main driver of the hash table application.
- `hash.cpp`, `hash.h`: Implement the hash table and the custom hash function.
- `Makefile`: Contains commands for compiling the project.
- `inputs/`: Directory for sample input files.
- `README.md`: Documentation of the project (this file).

## Features

- **Hash Function**: Implements a custom function to map strings to hash table indices.
- **Chaining**: Handles collision using linked lists at each index of the hash table.
- **Output Information**: Displays the first five slots' contents, all slots' lengths, and the standard deviation of the slot lengths.

## Usage Notes

- Ensure input files are correctly formatted as per project specifications.
- Adheres to the specific C++ standards and restrictions provided by the course.

## Additional Information

For questions or assistance, please contact georgebadulescu123@gmail.com.
