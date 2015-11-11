# Abstract #
Many single nucleotide polymorphisms (SNPs) for complex genetic diseases is genotyped by polymerase chain reaction-restriction fragment length polymorphism (PCR-RFLP) in small-scale basic research studies. It is an essential work to design feasible PCR-RFLP primer pair and find out available restriction enzymes to recognize the target SNP for PCR experiments. However, many SNPs are incapable of performing PCR-RFLP to make SNP genotyping become unpractical. A genetic algorithm (GA) had been proposed for designing mutagenic primer to bring available restriction enzymes, but it gives an unrefined solution in mutagenic primers. In order to improve the mutagenic primer design, we propose TLBOMPD (TLBO-based Mutagenic Primer Design) a novel computational intelligence-based method that uses the notion of “teaching” and “learning” to search for more feasible mutagenic primers and provide available restriction enzymes. The proposed method maintains original Wallace’s formula for the calculation of melting temperature, more accurate calculation formulas of GC-based melting temperature and thermodynamic melting temperature are especially introduced. Mutagenic matrix is also reserved to increase the efficiency of judging whether a hypothetical mutagenic primer can bring available restriction enzymes for recognizing the target SNP. Furthermore, the core of SNP-RFLPing version 2 is used to enhance the mining work for restriction enzymes based on the latest REBASE. Twenty-five SNPs with mismatch PCR-RFLP screened from 288 SNPs in human SLC6A4 gene are used to appraise the TLBOMPD. Also, the results are compared with those of the GAMPD. The TLBOMPD is implemented in JAVA and it is freely available at http://tlbompd.googlecode.com/.


## Requirements ##

- JAVA Runtime Environment (JRE) 1.7.0 or later.
> If you can not run TLBOMPD or you are getting an error message, please download and install
> the laster JRE from:
> > http://www.oracle.com/technetwork/java/javase/downloads/index.html


## Database ##

REBASE download from http://rebase.neb.com/rebase/rebase.files.html
at 11. All Enzymes (parsed references) file.
EBASE version 402 updated on Jan 30 2014


## Source Code ##

Full source code for TLBOMPD is available at:


> http://tlbompd.googlecode.com/

Please download TLBOMPD source code and results from:

> https://sites.google.com/site/yhcheng1981/downloads/tlbompd-download


## Check out the latest TLBOMPD source code ##

Use this command to anonymously check out the latest TLBOMPD source code:
You can use this command to anonymously check out the latest TLBOMPD source code
on the Google Code repository:

> svn checkout _http_://tlbompd.googlecode.com/svn/trunk/ tlbompd-read-only


## LICENSE ##

TLBOMPD is implemented and maintained by Yu-Huei Cheng from 2013 to 2015.

TLBOMPD is published under GPLv3 license, please see the LICENSE file.


## Author ##
Yu-Huei Cheng

Email: yuhuei.cheng@gmail.com

Web: https://sites.google.com/site/yhcheng1981/