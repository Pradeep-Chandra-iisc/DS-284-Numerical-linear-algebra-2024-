# Assignment 3 - Iterative Methods and Applications

## Overview
This assignment explores iterative methods for solving large-scale linear systems and their practical applications.

## Topics Covered
- Jacobi and Gauss-Seidel methods
- Conjugate Gradient method
- GMRES and other Krylov subspace methods
- Preconditioning techniques
- Convergence analysis

## Files in this Assignment
<!-- Add your assignment files here as you complete them -->
- `iterative_methods.py` - Implementation of various iterative solvers
- `conjugate_gradient.py` - CG method with analysis
- `gmres_implementation.py` - GMRES algorithm
- `preconditioning.py` - Preconditioning strategies
- `convergence_analysis.ipynb` - Jupyter notebook with convergence studies
- `assignment_3_report.pdf` - Detailed theoretical and practical analysis

## Requirements
- Python 3.x
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook
- Seaborn (for advanced visualizations)

## How to Run
```bash
# Install dependencies
pip install numpy scipy matplotlib jupyter seaborn

# Run iterative methods
python iterative_methods.py
python conjugate_gradient.py

# View convergence analysis
jupyter notebook convergence_analysis.ipynb
```

## Notes
- Includes theoretical convergence proofs and practical validation
- Performance comparison between different methods
- Analysis of conditioning effects on convergence

## Author
**Pradeep Chandra**  
M.Tech (CDS), Indian Institute of Science, Bangalore  
Course: DS-284 Numerical Linear Algebra  
Academic Year: 2024