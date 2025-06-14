# alumath

A simple Python library for matrix multiplication created by Group 25.

##  Description

`alumathgroup25` is a custom-built Python library for performing **matrix multiplication** with robust error handling and fun custom messages. It ensures that only compatible matrices can be multiplied and provides helpful warnings when dimensions don't match or invalid inputs are used.

## Features

- Matrix multiplication (`multiply_matrices`)
- Custom error handling (`MatrixDimensionError`)

## Installation

You can install the package using pip:

```bash
pip3 install alumathgroup-twenty-five or pip install alumathgroup-twenty-five



## Example usage
'''
from alumathgroup25.main import multiply_matrices

mat1 = [[1, 2],
        [3, 4]]

mat2 = [[5, 6],
        [7, 8]]

result = multiply_matrices(mat1, mat2)
print(result) # Output: [[19, 22], [43, 50]]

-------------------------------------------

mat1 = [[1, 2], [3, 4]]
mat2 = [[5, 6, 7], [8, 9, 10]]
result = multiply_matrices(mat1, mat2)
# Output:⚠️ Warning: Mathias is confused. Reine says no. Orpheus is disappointed. Can't multiply these matrices. ⚠️

'''
