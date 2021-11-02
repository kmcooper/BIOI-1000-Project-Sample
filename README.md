# BIOI-1000-Project-Sample
A Github repository used as a sample for Coding Projects in project-based BIOI 1000 courses at UNO

# BIOI 1000 Project Sample GitHub Repo
This is a sample GitHub repo for BIOI 1000 students in project-implementing versions of the course to use as a general guide. Refer to the assignment rubric and description for actual project requirements; this sample repository does not necessarily align with assignment expectations.

Code. Your code should work on my machine using instructions you provide for full credit. I will not open or edit your files to make your code work. 
Code should be properly commented with descriptive and consistent style.
If I need any dependencies or libraries installed to make your code work please clearly include those in the README and I will install them if I do not have them already.
Do not hard code any file names or paths that are specific to your machine.

## Configuration instructions.
None

## Installation instructions.
Simple "install", just download the script to your machine and run it from your preferred folder. The script used for this project requires [Python 3.7.12](https://www.python.org/downloads/) or higher to run as well as the [pandas](https://pandas.pydata.org) Python library

## Operating instructions.
Navigate to the folder that contains the script and run the following command, where DNA represents your input and protein represents your output:  
`python3 nucleotide_to_protein.py -i DNA.fa -o protein.fa`  

## Sample Input/Output
You can run the file with the following input and if working correctly should generate the output in prot.fa exactly. You can check if there are differences using the `diff` or `vimdiff` commands.
`python3 nucleotide_to_protein.py -i DNA.fa -o protein.fa`  

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


