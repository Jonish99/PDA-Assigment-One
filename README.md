# PDA-Assigment-One

## Assigment plan
1. Explain the overall purpose of the package. - Numpy.random
2. Explain the use of the “Simple random data” and “Permutations” functions.
3. Explain the use and purpose of at least five “Distributions” functions.
4. Explain the use of seeds in generating pseudorandom numbers.

# Numpy explanation

Numpy is an open source Python libary which is designed to enable numerical computing. 
It was created in 2005 evolving from the Numeric and Numarray Python libraries. 
https://numpy.org/about/
    
One of the key features of Numpy is it's use of arrays an NDarrays -multidimensional arrays. The random generator outputs random numbers in these numpy arrays.NumPy is the primary array programming library for the Python language. It has an essential role in research analysis pipelines in felds as diverse as physics, chemistry, astronomy, geoscience, biology, psychology, materials
science, engineering, fnance and economics. https://www.nature.com/articles/s41586-020-2649-2.pdf
More over, these arrays are vectorised meaning that writing code in numpy is simpler.
 
Consider this example, : 
 ```
    a=np.array([1,2,3])

    b =np.array([1,2,3])
  ```
here we wish to multiply the values of the same index in arrays *a* and *b*. 

Compare numpy code
  
  ```
  c = a * b
  ```
  
  to
  
  regular python code 
   ```c = []
for i in range(len(a)):
    c.append(a[i]*b[i]) 
 ```
 
 to achieve the same result:
 ``` 
 c = [1,4,9]
 ```
 https://www.activestate.com/resources/quick-reads/what-is-numpy-used-for-in-python/

The same simple expression can be used if *a* and *b* were ndarrays, where as the regular python code 
  
## random() is package within the numpy library.

  
### Contents of the notebook 
#### 1 . Simple random data functions 
1.1 integers

1.2 random

1.3 choice

1.4 bytes
 
##### 2. Permutations

     
2.1 shuffle

2.2permuations
     
    
  
##### 3. numpy distribution functions

     Normal
     Uniform
 
##### 4. Seeding and pseudo random numbers?
     