# PCA-Demonstrate-Matrix-transposition-on-shared-memory
## Aim:
To Comparing the Performance of the Rectangular Shared Memory Kernels with  grid (1,1) block (16,16)
## Procedure:

### Step 1
Include the required files and library.

### Step 2
Define the block size to be 16 .

### Step 3
Intoduce a void function to print the data.

### Step 4
Introduce global functions to set and read the row & column. In the function , decalre a shared memory , map thr thread index to global memory index , perform store operation and wait for all threads to complete and them perform load operation.

### Step 5
Introduce the main function, in the main method set up the device ,array size and declare the execution configuration. Allocate the device memory and finally free the host and device memory followed by reseting the device.

### Step 6 :
Save and execute the program.

## Program:
```cuda

```
## Output:

## Result:
The Matrix transposition on shared memory with grid (1,1) block (16,16) is demonstrated successfully.


