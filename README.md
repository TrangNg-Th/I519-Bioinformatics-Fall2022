# I519-Bioinformatics-Fall2022


Challenges of 08-29-2022

1.Determine the frequency of each amino acid in a multi-FASTA protein sequence input file.

2. Remove duplicate entries from a multi-FASTA protein sequence input file (articulate a criterion for "duplicate") and save the duplicate entries in a separate file.

3. a) Determine the maximal length "M" of a run of K or Rs (= positively charged amino acids lysine and arginine) in a multi-FASTA protein sequence input file.

4. ~3.b)  continued: Generate a table showing the frequency of sequences with runs of length M, M-1, M-2, ..., 1, 0.

5. For a multi-FASTA protein sequence input file, generate a table of the most frequent k-mers, where k is an integer input to the program; e.g. k=7.


## Assumption :

1. The challenges require using the native commands of linux & the library ```seqkit````
2. The data used in this directory is ```PD.fasta```. (Please replace it with the data you wish to try on.)

## How to

When cloning the repository, please first execute ```sh prep  ```

Then execute any program ch{id} using ```sh ch{id}```

Once you're done, please execute ```sh prep ```again to clean up the directory


## About the programs
```prep```
This program cleans up the directory, leaving only ```PD.fasta ch1 ch2 ch3 ch5 prep```files in your current directory


## PS:
Please let me know if you have any ideas/comments


```ch1```
This program answers to the question 1

```ch2```
This program answers to the question 2

```ch3```
This program answers to the question 3 & 4. But it doesn't give a table. 
So far, I haven't found a way to create a table.


```ch5```
This program answers to the question 5. It isn't an optimized approach due to the limitation of the available tool and my current level of linux.
Note that with the same input file size,  the smaller the kmer size is, the longer the program will run.



