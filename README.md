# numpy
import numpy as np 
#Creating arrays
ar1d = np.arange(11,17)
ar2d = np.arange(11,36).reshape(5,5) 
print("1-D array is:")
print(ar1d)
print("2-D array is:") 
print(ar2d)
#Properties
print("ar1d shape, size, dimensions are", ar1d.shape, ar1d.size,
ar1d.ndim) 
print("ar2d shape, size, dimensions are", ar2d.shape, ar2d.size,
ar2d.ndim)
#indexing
print("Indexing on ar1d:", ar1d[2],ar1d[-2]) 
print("Indexing on ar2d:", ar2d[2][1],ar2d[1][1])
#slicing
print("Slicing on ar1d:", ar1d[2:6]) 
print("Slicing on ar2d:") 
print(ar2d[1:4,2:4])# Numpy
