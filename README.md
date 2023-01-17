# DigImpro
Simple library coded in TI Basic to help student with the course of Digital Image Processing.
## Implemented functions
- Conv2d(m, k)
- conv1d(f, h)
- bilinear(x,y,m,v)
- nearestneighbor(x,y,m,v)
- covariance_vec(x,y,b,v)
- covariancemat(x,b,v)
- erode(m,k)
- dilation(m,k)
- open(m,k)
- close(m,k)
- hitormiss(m,b)
- white_top_hat(m,b,v)
- black_top_hat(m,b,v)
- dft(x)
- idft(x)
- dft_2d(m)
- idft_2d(m)
## Tested on
- TI-nspire CX II-T CAS
## Paramters of the functions
- Conv2D(m,k)
  - m: matrix
  - k: kernel
- Conv1D(f,h)
  - f: vector 1
  - k: vector 2
- bilinear(x,y,m,v)
    - x: x coordinate
    - y: y coordinate
    - m: matrix
	- v: verbose mode
- nearestneighbor(x,y,m)
    - x: x coordinate
    - y: y coordinate
    - m: matrix
- covariance_vec(x,y,b,v)
    - x: vector x
    - y: vector y
    - b: bias (0 = no bias / N-1  |   1 = bias / N)
	- v: verbose mode
- covariancemat(x,b,v)
    - x: matrix
    - b: bias (0 = no bias / N-1  |   1 = bias / N)
	- v: verbose mode
- Morphological Transformation
    - erode(m,k)
    - dilation(m,k)
    - open(m,k)
    - close(m,k)
	- white_top_hat(m,b,v)
	- black_top_hat(m,b,v)
        - m: matrix
        - k-b: structucual matrix (put 1 where you need)
		- v: verbose mode
- hitormiss(m,b,v)
	- m: matrix
	- b: structural element (must be 0,1, or infinite for dont care)
	- v: verbose mode
- Fourier
	- dft(x)
	- idft(x)
	- dft_2d(m)
	- idft_2d(m)
		- x: vector line
		- m: matrix
    
## WARNING
in TI BASIC the index of the matrix start from 1, not from 0.