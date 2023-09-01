# WannierTools-2.7.0

The WannierTools 2.7.0 from Github, and fixed some bug. The arpack-ng code been add to the source file, so it not dependent on the arpack lib.

# Install

Install Intel OneAPI and module load the OneAPI modulefiles  

1. tar -zxvf wanniertools-2.7.0-v1.0.tar.gz  
2. module load compiler/latest  
3. module load icc/latest  
module load mkl/latest  
module load mpi/latest  
4. cd wanniertools-2.7.0-v1.0  
5. cd src
6. make  

then the wt.x will be in the dirctory bin  