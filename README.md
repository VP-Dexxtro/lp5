"# lp5" 
##for HPC to install GCC: sudo apt install gcc 

Configuring OpenMP: echo |cpp -fopenmp -dM |grep -i open 

sudo apt install libomp-dev 

Compile: gcc -o gfg -fopenmp geeksforgeeks.c

Execute: ./gfg



