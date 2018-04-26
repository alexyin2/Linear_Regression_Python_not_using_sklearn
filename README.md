# Learning Linear Regression in Python but Not Using sklearn

### Warning: Linear Algebra and Calculus are highly-needed for learning linear regression.

* In this repository, I'll try my best to avoid using sklearn in Python since my goal is to understand how the mathematics work in linear regression.
* But I'll use packages like Numpy, matplotlib, and sometimes Pandas to help me skip trivial obstacles.
* I'll introduce how these packages help in learning regression model:
1. **Numpy**: 
   - Numpy packages can help solve linear algebra questions really fast.
   - In np.array, calculations are element wise, and this is very useful in doing mathematics.
   - Following are some useful codes for calculating linear algebra by using Numpy:
```
# Inverse Matrix
np.linalg.inv()
# Extract a diagonal or construct a diagonal array.
np.diag()
# Calculate the outer product.
np.outer()
# Calculate the inner product.
np.inner()
```

2. **Pandas**: 
   - Pandas can help importing data and do some summary statistics

3. **matplotlib.pyplot**: 
   - Helps for data visualization

* This practice is based on [LazyProgrammer.me](https://github.com/lazyprogrammer)
