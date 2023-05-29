"# lp5" 
for HPC to install GCC: sudo apt install gcc \n
Configuring OpenMP: echo |cpp -fopenmp -dM |grep -i open \n
sudo apt install libomp-dev \n
Compile: gcc -o gfg -fopenmp geeksforgeeks.c \n
Execute: ./gfg



