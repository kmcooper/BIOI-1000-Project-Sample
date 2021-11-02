# BIOI 1000 Project Sample GitHub Repo
**Purpose**: This is a sample GitHub repo for BIOI 1000 students in project-implementing versions of the course to use as a general guide. Refer to the assignment rubric and description for actual project requirements; this sample repository does not necessarily align with assignment expectations.

## Configuration instructions and dependencies
The script used for this project requires [Python 3.7.12](https://www.python.org/downloads/) or higher to run as well as the [pandas](https://pandas.pydata.org) Python library. This code was developed and tested on a MacOSX with Python 3.7.12 installed using pandas version 1.3.4. (*Note: This code does not actually use pandas, I am just giving an example of how to describe dependencies*)

## Installation instructions
Simple "install", just download the script to your machine and run it from your preferred folder. 

## Operating instructions
Navigate to the folder that contains the script and run the following command, where DNA represents your input and protein represents your output:  
`python3 nucleotide_to_protein.py -i nuc.fa -o protein.fa`  

## Sample Input/Output
You can run the file with the following input and if working correctly should generate the output in prot.fa exactly. You can check if there are differences using the `diff` or `vimdiff` commands.  
`python3 nucleotide_to_protein.py -i nuc.fa -o protein.fa`  

## Files in this directory
- nucleotide_to_protein.py
- LICENSE: The MIT License explaining reuse of this GitHub
- This README
- A sample input file, nuc.fa
- A sample output file, prot.fa

## Contact information 
Author: Kate Cooper, kmcooper [at] unomaha [dot] edu

## Known bugs
None as of 11/02/2021

## References for this Repo
- [Bioinformatics Sequence Manipulation Suite](https://www.bioinformatics.org/sms2/index.html): Stothard P (2000) The Sequence Manipulation Suite: JavaScript programs for analyzing and formatting protein and DNA sequences. Biotechniques 28:1102-1104.


