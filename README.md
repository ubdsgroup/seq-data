# seq-data
Benchmark sequence and time series data sets for evaluating anomaly detection algorithms

### Maintained by - 
- Varun Chandola
- chandola@buffalo.edu
- [www.cse.buffalo.edu/~chandola](www.cse.buffalo.edu/~chandola)

Data sets referred in:
> Varun Chandola, Varun Mithal, and Vipin Kumar, A Comparative Evaluation of Anomaly Detection Techniques for Sequence Data, In Proceedings of 2008 IEEE International Conference on Data Mining (ICDM), December 2008,Pisa, Italy.
---
### Format of data:
Each data directory (say xxx) contains following files:
- xxx.train - training sequences (all normal)
- xxx.alpha - alphabet file
- xxx.p.test - test sequences containing normal and anomalous sequences in ratio defined by p.
		-- p = 1 => 1:1 ratio
		-- p = 2 => 1:10 ratio
		-- p = 3 => 1:20 ratio
xxx.p.labels - labels for the corresponding test files. 0 indicates normal and 1 indicates anomalous.
---
### Four sets of data sets:

1. PFAM data sets - protein sequences. hcv,nad,tet,rub,rvp.
2. UNM data sets - operating system call data - snd-cert,snd-unm.
3. BSM data sets - operating system call data - bsm-week1,bsm-week2,bsm-week3.
4. Artifical data sets - generating using HMMs - datasc1--datasc34.
---
