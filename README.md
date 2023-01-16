# DigImpro
Simple library coded in TI Basic to help student with the course of Digital Image Processing.
## Implemented functions
- Conv2d(m, k)
- conv1d(f, h)
- bilinear(x,y,m)
- nearestneighbor(x,y,m)
- covariance_vec(x,y,b)
- covariancemat(x,b)
- erode(m,k)
- dilation(m,k)
- open(m,k)
- close(m,k)
- hitormiss(m,b)
## Tested on
- TI-nspire CX II-T CAS
## Paramters of the functions
- Conv2D(m,k)
  - m: matrix
  - k: kernel
- Conv1D(f,h)
  - f: vector 1
  - k: vector 2
- bilinear(x,y,m)
    - x: x coordinate
    - y: y coordinate
    - m: matrix
- nearestneighbor(x,y,m)
    - x: x coordinate
    - y: y coordinate
    - m: matrix
- covariance_vec(x,y,b)
    - x: vector x
    - y: vector y
    - b: bias (0 = no bias / N-1  |   1 = bias / N)
- covariancemat(x,b)
    - x: matrix
    - b: bias (0 = no bias / N-1  |   1 = bias / N)
- Morphological Transformation
    - erode(m,k)
    - dilation(m,k)
    - open(m,k)
    - close(m,k)
        - m: matrix
        - k: structucual matrix (put 1 where you need)
- hitormiss(m,b)
	- m: matrix
	- b: structural element (must be 0,1, or infinite for dont care)
    
## WARNING
in TI BASIC the index of the matrix start from 1, not from 0.