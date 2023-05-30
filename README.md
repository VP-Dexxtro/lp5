"# lp5" 
##for HPC to install GCC: sudo apt install gcc 

Configuring OpenMP: echo |cpp -fopenmp -dM |grep -i open 

sudo apt install libomp-dev 

Compile: g++ -o gfg -fopenmp geeksforgeeks.cpp

Execute: ./gfg

### CUDA Program 
nvcc -o program_name program_name.cu

Execute: ./program_name

### for Deep Learning
for Lab1 https://github.com/richardwarepam16/BE_DL_Practicals
download the .ipynb file and load it to jupyterBook
and for writing the pdf are their


