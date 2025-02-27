# Research Skill Exercise 14

## Repository Contents
This repository contains the code and the technical report for the selection sort (MaxSort) algorithm. 

## Usage Setup
1. Compilation
```bash
gcc -o run sort.c
```

2. Input Files (format specified in Appendix)
- Configuration File - config.txt
- Input data file that contains the data to be sorted (e.g. data.txt)

3. Execution
```bash
./run
```

4. Output Files (format specified in Appendix)
- Output data file that contains the sorted data (e.g. output.txt)
- A file that contains the number of item swaps - stat.txt
- A file that contains the information of the execution time - time.txt

## Appendix
### Appendix A: Format of Configuration File (config.txt)
1. the file path of the input data file
2. the number of items to be sorted in the input data file
3. parameter 2
4. parameter 3
5. parameter 4

### Appendix B: Format of Input File
The input data file contains the data to be sorted. The data items are in a single line separated by a space.
### Appendix C: Format of Output File (output.txt)
The output data file contains the sorted data. The data items are also in a single line separated by a space.
### Appendix D: Format of Log File (stat.txt & time.txt)
#### stat.txt
stat.txt contains a single integer that represents the number of item swaps.
#### time.txt
Each line in time.txt corresponds to a user time and system time.  
The content of lines in time.txt is as follows: 
```
<user read time> <system read time>
<user sort time> <system sort time>
<user write time> <system write time>
<user overall time> <system overall time>
```
