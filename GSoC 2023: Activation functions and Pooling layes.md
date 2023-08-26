This wiki page summarises the work I have done during GSoC 2023 at mlpack. The links to PRs are under each header.
## Abstract

This year my proposal on Activation function and Pooling methods was selected for GSoC by mlpack. *mlpack* is an intuitive, fast and flexible C++ machine learning library with bindings to other languages.
\
My project's main focus was to update Mlpack's the ANN library by implementing activation functions and pooling methods like FTSwish,Hyper SinH, Fractional Max pooling 2d etc.
\
In total I implemented 3 activation layers and 2 activation functions.

## Pull Requests

#### Major Additions

1. [mlpack/mlpack#3491](https://github.com/mlpack/mlpack/pull/3491): Implemented Hyper-Sinh activation function.

2. [mlpack/mlpack#3485](https://github.com/mlpack/mlpack/pull/3485): Implemented FTSwish Activation Layer.
​
3. [mlpack/mlpack#3530](https://github.com/mlpack/mlpack/pull/3530): Implemented ShiftedSiftplus actvation function.
​
4. [mlpack/mlpack#3524](https://github.com/mlpack/mlpack/pull/3524): Implemented Fractional Max Pooling 2d.
​
5. [mlpack/mlpack#3498](https://github.com/mlpack/mlpack/pull/3498): Added StarReLU Layer.

## Conclusion

This summer has been a great learning experience and has helped me get a good exposure of test-driven development. I plan to actively contribute to mlpack in the future and try to become a mentor for Gsoc next year. I am grateful to my mentor, [Marcus](https://github.com/zoq) for reviewing my work, giving me valuable suggestions and helping me in bug fix.
