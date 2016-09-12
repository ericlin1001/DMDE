all:compile run

compile:pde.cpp
	mpic++.mpich  -DALGORITHM=4 -o test pde.cpp

run:test
	mpirun.mpich -n 4 ./test

