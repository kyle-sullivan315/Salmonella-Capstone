# Salmonella-Capstone
This code is part of my senior capstone research project in which I attempt to detect pathogenicity using bioinformatic methods. 
The code in this repository is incomplete, it just to show the genreal process and logic I used to test my hypotheses. 

Using the NCBI pathogen detection database, I was able to obtain five complete Salmonella Enterica genome assemblies. 
Of the five genomes, two were clinical isolates,two were environmental isolates, and one was a reference genome. 
My original goal was to find some sort of difference between the clinical and environmental isolates. 
To do this, I extracted all of the open reading frames from each genome and found the codon usage rates for each open reading frame. 
I ran a principal component analysis on all of the 19,000 open reading frames and their codon usage rates. 
I ended up finding a bimodal distribution of open reading frames in the PCA and spent the rest of the time trying to explain that distribution. 
I discovered that there did not appear to be any difference between the genomes, leading me to conclude that the cause of the bimodal distribution must be within the genomes.
I went on to examine the relationship between the PCA and location of the open reading frames, whether or not the open reading frames are part of a Salmonella Pathogenicty Island (SPI), and the GC content of the open reading frame. 
Ultimately, I wasn't able to find an explaination for the bimodal distribution of codon usage in the PCA, but I was able to disprove mulitple hypotheses and get some potential future directions. 
