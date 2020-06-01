# LAMMPS
LAMMPS_CODE

To run the script type the following in the terminal:

lmp_mpi -in shockley_edge.lmp

So the command is nothing but:
1. lammps executable file (lmp_mpi); (use whatever the lammps executable file in your system or server) 
2. shockley_edge.lmp is the input lammps file

you can also use the following command if you have "mpi" installed in your system:

mpirun -n 6 lmp_mpi -in shockley_edge.lmp

6 - is the maximum number of processors in my system
