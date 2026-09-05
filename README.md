## Project Summary
This is a micro-project focused on Partial Differential Equations (PDE) simulation. 
This project simulates 1D image blurring 
using the heat equation and Fourier series 
in Python. It demonstrates how sharp edges 
turn into smooth gradients over time, 
acting effectively as a mathematical low-pass 
filter to analyze signal degradation.

## Group Members and Contributions


**Sidharth S**(Group Leader ):
* Developed the model for 1D heat equation for isotropic pixel intensity propagation through a digital line scan.
* Derived the analytical Fourier sine coefficient, bn for the step function initial intensity profile.
* Authored the core theoretical LaTeX sections for separation of variables and quantization of spatial eigenvalues.

**Sourav R**:
* Developed the numerical Python script (NumPy) for evaluating the infinite Fourier series through N=150 terms.
* Generated the time evolution spatial plots (Matplotlib) for visualizing the spatial blurring process.

**Thomas Mathew**:
* Directed the project organization, group management, and authored the final report for Phase 1 analytical and Phase 2 numerical solutions.
* Formulated the mathematical proof for the exponential decay of higher spatial harmonics.

**Shaheem Ahammed**:
* Implemented the log scale harmonic decay analysis for assessing the continuous low-pass filtering effect across the spatial modes (n=1, 3, 5, 9, 15).
* Analyzed the physical manifestation of Gibbs phenomenon at the step discontinuity (t=0).

**Sivapriya K G**:
* Enforced homogeneous Dirichlet boundary conditions (I(0,t)=I(L,t)=0) for deriving the spatial eigenfunctions.
* Compiled the engineering conclusions and physical interpretations of spatial blurring and reference list.
