# Parallelisation-of-Sequence-Alignment

## PROBLEM DISCUSSION & AIM 
The aim of this project is to compare serial and parallel implementations of Smith-Waterman algorithm for local sequence alignment on randomly generated nucleotide sequences, to analyse the efficiency between the methods when overhead and size of inputs are increased exponentially, and also to obtain the detected sequence represented in the output of this programme.
The Smith-Waterman algorithm calculates the local alignment of two sequences. It guarantees to find out the best possible local alignment taking into account the specified scoring system. This includes a substitution matrix and a gap scoring method. Scores consider match, mismatch and substitution. To measure the comparison between two sequences, a score is calculated in various ways.

## ALGORITHM
Smith-Waterman algorithm [7-18] calculates the local alignment of two sequences. It guarantees to find out the best possible local alignment taking into account the specified scoring system.
This includes a substitution matrix [1,2,3] and a gap- scoring method [4,5,6]. Scores consider match, mismatch and substitution. To measure the comparison between two sequences, a score be calculated as follows:
Given an alignment between sequences S0 and S1, the following values must be assigned, for each column:

    ● ma = (+5) [Match]
    ● mi = (-3) [Mismatch]
    ● G = (-4) [Gap]

## CONCLUSION 

The graphs tell us that for small lengths of the sequence, serial and parallel programs tend to give the output in almost the same amount of time.
However, as the length increases, the execution time for serial implementation also increases exponentially, hence forming a steep graph.
However, the parallel implementation remains stable with not a high rise in the execution time because of the parallel execution of the task with two threads, making the process faster than its serial counterparts.
