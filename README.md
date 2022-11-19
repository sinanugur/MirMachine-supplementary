# MirMachine-supplementary

[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)

Supplementary document repository for MirMachine, a command line tool to detect miRNA homologs in genome sequences.


The results folder contains, __MirGeneDB__ species prediction results generated by __MirMachine__ and other species predictions mentioned in the MirMachine manuscript.



We  are using the same directory structure and you will see:  
`gff/` __All predicted miRNA families.__  
`filtered_gff/` __High confidence miRNA family predictions after bitscore filtering. (This file is what you need in most cases)__  
`fasta/` __Both high and low confidence predictions in FASTA format.__ 

Note:
The resuls under MirGeneDB predictions have three subdirectories; MirMachine-Train refers to combined model predictions, MirMachine-Train0 refers to proto model predictions and MirMachine-Train1 refers to deturo model predictions.
