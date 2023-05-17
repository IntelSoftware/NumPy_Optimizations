## Datasets
- Data are synthesized by the author, bob chesebrough
- California Housing Dataset from scikit-learn is included for some exercises

# NumPy_Optimizations
Exercises to replace loops with NumPy function equivalents to gain 10X to 100sX acceleration over simple minded python loop access

Purpose: Train how to replace low level LARGE loops with NumPy ufuncs, aggregations, broadcasting and fancy slicing. and NumPy where/select clauses to invoke more "C" like performance combined with vectorization SIMD capabilities

Requirements:
 - conda config --add channels intel
 - conda install numpy
 - conda install scipy
 - conda install update pandas

Everything else is core python.