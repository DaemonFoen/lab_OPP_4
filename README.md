# lab_OPP_4

Parallel implementation of the Jacobi method in a three-dimensional domain using mpi

build: mpicxx -Wall -Wpedantic -Wextra -O3 main.cpp -o out -lm

run: mpiexec -n 16 ./out
