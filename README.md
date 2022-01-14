# Hyperquicksort

## Example:

To compile:
```
mpicc -O2 hyperquicksort.c -o hqs.o -lm
```
To execute:
```
mpirun -np 4 ./hqs.o input_file res.csv -save
```

Where:
- *input_file*: path input file.
- *res.csv*: path csv file in which to store the sorting times.
- *-save*: flag to save the sorted list int the file *input_file_sorted*.

