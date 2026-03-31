## Experiment-9
## Aim: To study and implement the NumPy library in Python.

## Theory:
NumPy (Numerical Python) is a powerful Python library used for numerical and scientific computing.
It provides support for multi-dimensional arrays and a collection of high-level mathematical functions that operate on these arrays efficiently.
Why NumPy is Used?
-Faster than Python lists
-Efficient memory usage
-Used for numerical computations
-Forms the base for libraries like Pandas, SciPy, and Matplotlib
-Declaration of NumPy
-NumPy is imported using import numpy as np
-Arrays are created using np.array()
-NumPy arrays store elements of the same data type, which improves performance

# Array Creation Methods Used
np.array() → creates an array
np.arange() → generates values in a given range
np.linspace() → generates evenly spaced values
np.eye() → creates an identity matrix
zeros() → array of 0s
ones() → array of 1s
ndim → number of dimensions
dtype → data type of elements

# Indexing and Slicing: Access or extract specific elements or parts of an array.
Indexing Syntax : - array[index] & array[row_index, column_index]
Slicing Syntax : - array[start : end : step]
eg.a[0] # first element
a[1:3] # slicing
a[-1] # last element

# Mathematical Operations: Performs element-wise arithmetic operations on arrays.
Functions:
np.add() – Adds corresponding elements of two arrays.
np.subtract() – Subtracts elements of one array from another element-wise.
np.multiply() – Multiplies corresponding elements of two arrays.
np.divide() – Divides elements of one array by another element-wise.

# Dimension of array-Returns number of dimensions (axes) using ndim.
ndim: The number of dimensions (axes) of the array (e.g., 1 for a vector, 2 for a matrix).
eg.import numpy as np
a = np.array([[1,2,3],[4,5,6]])
print(a.ndim)
size: The total number of elements in the array.
eg.a = np.array([[1,2,3],[4,5,6]])
print(a.size)
shape: A tuple indicating the size of the array in each dimension using array.shape command.
eg.import numpy as np a = np.array([[1,2,3],[4,5,6]])
print(a.shape)
dtype: The data type of the elements in the array (e.g., int64, float64) using commnad array.dtype.
eg.import numpy as np
a = np.array([1,2,3,4])
print(a.dtype)

## Built-in Functions Used
np.mean() → calculates mean of array elements
np.median() → calculates median
np.max() → finds maximum value
np.min() → finds minimum value
np.sum() → calculates sum of elements
These functions simplify complex mathematical operations and reduce code length while improving execution speed.

## Conclusion
In this experiment, the NumPy library was successfully implemented to perform various numerical operations. Array creation
methods and built-in functions such as mean, median, maximum, minimum, and sum were studied. This experiment demonstrates that
NumPy provides faster, cleaner, and more efficient ways to handle numerical data compared to traditional Python lists.
