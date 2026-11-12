# project1-sequence-analysis
NGS sequence analysis 
This project uses python to analyse DNA sequence reads and to compare mismatch patterns between control and treatment groups. 
This project aims to identify mismatches within the seuqence, calculate the frequency and to see if there is any differences between the group. 

**How to run the program**
The program is written in a Google Colab notebook. To run it, open the notebook in Colab and run the cells in order from top to bottom.  

**Inputs and Outputs**
The program uses DNA sequence reads from six samples and a reference sequence to compare them against. The program checks whether the reads are valid and identifies any mismatches. The outputs include percentage of reads containing mismatches, number of mismatch events, most common mismatch positions and the different types of substitutions. There is also a comparision between the control and treatment groups using Welch's t-test. 

**Code Design**
The program is spilt in 5 steps to show each function and its specific job. For example, validate_read() checks whether a sequence read is valid, while find_mutations() identifies the differences from the reference sequence. 

**Testing**
I tested the code using valid and invalid sequence reads to ensure that validation was working correctly. I also checked that mismatch counts and positions were being calculated correctly. In addition, I tested cases where multiple positions had the same number of mismactehs to ensure that the results remained consistent and reliable.






