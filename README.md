
# Setup
```
pip3 install numpy matplotlib mpi4py
```

For parallelized code, it is required to install OpenMPI (Windows), mpi (linux)

# Run parallelized

Open parallelized_sliding_lid.ipynb

Run the 2nd cell (start up the clusters)

Run the 4th cell (Parallelize the lattice Boltzmann and save the results as ux.npy and uy.npy)

## Load and display the parallelized results

Run the 5th cell (load ux.npy and uy.npy and graphed it)

## Changing lattice dimensions

Change NX and NY in 4th cell line 5 + 6 
	                5th cell line 8 + 9

## Changing omega

Change omega in 4th cell, line 258

## Changing domain decomposition grid

Change n in 2nd cell, line 2

# Running serialized code

Open serial_lattice.ipynb

Run the imports and corresponding milestones