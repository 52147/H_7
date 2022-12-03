# H_7
## Thread
Single thread: execute one thread without interruption   
Multi-thread: execute many thread at the same time while sharing resource

## Single thread program
Genome is a sequence that only contains 4 character "A, T, C, G"   
Create 100 random sequence of genome that contain 10 character   
## Multi-thread program
use 5 thread to create 20 genome sequence each

 
##  Difference between single thread and multi thread program:


|  | Single Thread  | Multi Thread |
| ------------- | ------------- | ------------- |
| run time | 3s  | 4s  |

## Output
### `Single Thread`

```
CGGAGCTACT Thread-0
CCTCTGGATA Thread-0
TCAAATAAGA Thread-0
CCAGAATAGG Thread-0
GATTTGGCCT Thread-0
TAACGTAGTC Thread-0
GTCATACACC Thread-0
TTCTATTGCC Thread-0
CCATAGTCGG Thread-0
TAATTCGACT Thread-0
CAGAGCGTAT Thread-0
TGGAACCTAA Thread-0
GTGCGGTGGC Thread-0
CTTAGTAACG Thread-0
GAGACAATTA Thread-0
TTAGCGGGGG Thread-0
CGCTTTTCGC Thread-0
AGTGCTGGTG Thread-0
GATATTGCTT Thread-0
AAGCCGGAAA Thread-0
CGGAGGATAA Thread-0
CTATGGTGCT Thread-0
CAAATAGCCG Thread-0
ACGGCCCCTT Thread-0
AATATTATAG Thread-0
TCTGGCGACT Thread-0
TGCCGCGTGC Thread-0
AACAATTGTT Thread-0
CGTCTAGTTC Thread-0
CTTAATGAGC Thread-0
TTCCAAATCA Thread-0
GGGGGACACT Thread-0
ATGTGAACCC Thread-0
TTCAAAGGAG Thread-0
AAGTGTAGTA Thread-0
AGGATAATGC Thread-0
GAATGGTACG Thread-0
CTACACCACT Thread-0
ACTTGGCGGA Thread-0
TATAGGTACT Thread-0
TTGCTCATGT Thread-0
CGTCCTGATT Thread-0
CCCGTCTGGT Thread-0
AGCCAACCTC Thread-0
TAACTTTATC Thread-0
GCAATACGTC Thread-0
ACCATCACTA Thread-0
ACGGCGCCTA Thread-0
GCCAAGCGGA Thread-0
GGCATACTCA Thread-0
GTCGCGAGTC Thread-0
TTGGGTAAGT Thread-0
TCTATATCAA Thread-0
GCATGGGAGT Thread-0
GTAGATATGC Thread-0
CGCAAAAATC Thread-0
TTGGCAAAGG Thread-0
AAAGCACGTG Thread-0
CAGTACACAC Thread-0
TGGTCTCACT Thread-0
GTTCAGATTG Thread-0
CTCTAGCCTA Thread-0
TTATCGACCG Thread-0
CACATGGCCG Thread-0
TGACGAGCTA Thread-0
GGCGTGCTTC Thread-0
TGAGTGCAAG Thread-0
GGGCTGGGTG Thread-0
CATCTCGTGC Thread-0
TAGCGCATTA Thread-0
TAGTGGTCCA Thread-0
AGTAGGAGCC Thread-0
TCGCCTGGAA Thread-0
TGGCTCATAT Thread-0
TGGAATTAAT Thread-0
TCCCGTTCAA Thread-0
ATCGACGTAA Thread-0
TGTTGCTCCA Thread-0
ACAAGGGGCT Thread-0
CTCGCTTAGT Thread-0
CATATTGTAC Thread-0
CAGGATATTA Thread-0
CTAAGCTACA Thread-0
TTCAAGTTAA Thread-0
AATGACCGGT Thread-0
TCCCAGTCGT Thread-0
GACGTTCTGG Thread-0
TTCCAGAAAT Thread-0
CAAGCAATAA Thread-0
TAGGCTTCTT Thread-0
CGGGGATTAC Thread-0
GATGCATCGG Thread-0
TTTATTCCGA Thread-0
TTGACACTAA Thread-0
GGCAATTAGT Thread-0
CGCGGAGTGC Thread-0
CTAGACTACG Thread-0
CTGGTCGCAG Thread-0
TGCCCTCTAG Thread-0
CGCCTTCGAG Thread-0
Thread-0 Elapse Time 3
```

### `Multi-Thread`
```
GTTGAGACCG Thread-0
GCTAGATTCG Thread-0
GGGGATACCC Thread-0
ATAGACCGCA Thread-1
GCCAGTGATT Thread-4
TTCCCACCCC Thread-4
TTAGGATGTG Thread-4
CTAACTGTAG Thread-3
GATCTGTCCG Thread-3
AACCTTCAAG Thread-2
GTCGTACTCT Thread-3
TAGGGTGTAG Thread-4
TAAACCGTAA Thread-1
TATCAATATG Thread-0
GAGCGTACAC Thread-1
GGTTATCCCA Thread-1
TGGATTCGGT Thread-1
CCTGGTGGGC Thread-4
CTCCACAAAC Thread-3
GGCGCCTCCA Thread-4
CTGGCCAGTA Thread-3
TTTCGCGATA Thread-2
TCATTTCGAG Thread-3
ATCATCGCGT Thread-4
GTAGTAGACA Thread-1
ATAGTGGACT Thread-0
TGGGGTGTTT Thread-1
TTTATATATC Thread-4
CCGATCTATA Thread-3
ACATCAGGTC Thread-2
ACCCAGGAAG Thread-2
CTTACAGGCG Thread-3
ACTGCAGGGC Thread-4
GCGACCCAGA Thread-1
AACGGTGCTT Thread-0
TGAGAGTTTA Thread-4
ATACTAGGAA Thread-4
AACCTGGTCG Thread-3
CCACTAAGTA Thread-2
ACCACAATGT Thread-2
CAGTAAGAGA Thread-3
AACAAGTTAC Thread-4
GCTAGGTGAA Thread-0
TTCAAGAGTC Thread-0
GACCCTATCG Thread-0
GACTAAACAC Thread-0
CTGTAATATA Thread-1
AGCGCCGGGA Thread-1
TCAAGACAAC Thread-1
AACCCAGGAT Thread-0
AAGTGAACTT Thread-4
TTTAACCAGA Thread-3
GGAGTTATAG Thread-2
CGTCGCACAG Thread-2
GAATCACAGA Thread-2
GTTTTAATAG Thread-3
GTTTGGGGCA Thread-4
ATAAGCCTCG Thread-0
CAGCTTTATC Thread-1
TTGATAGCGG Thread-0
GCCACCTCGG Thread-4
CCGCTCGGGA Thread-3
TTAAACCATG Thread-2
GAGAGCGTCA Thread-3
CGTAGGCGGT Thread-4
CACGTACGAT Thread-0
GTTGTATCAC Thread-1
GTTTGTCCCC Thread-0
GAGTCTGGAT Thread-4
CCTAACTATT Thread-3
CCTTTGAGCC Thread-2
CACGGTACGA Thread-3
CGTGGATTCA Thread-4
CGACCTAACA Thread-0
ACTCAGAGCA Thread-1
GCGCAGCTAT Thread-0
CGGTAGATTA Thread-4
TGAGTAATCC Thread-3
AGACAGACTC Thread-2
TCTTAGCCTC Thread-3
TCTAGAGGTA Thread-4
ATGCTGACAA Thread-0
GACAGGGATT Thread-1
TCGAAGTAGA Thread-0
Thread-4 Elapse Time 3
AGGTCGGAGT Thread-3
CAGAATAACA Thread-2
ACCATGAGAT Thread-3
GGCTGCTTCC Thread-0
AAGGCAAGAT Thread-1
Thread-0 Elapse Time 4
Thread-3 Elapse Time 4
AGCCGGCAAC Thread-2
GATGGCTTAT Thread-1
AATGCAACCC Thread-1
TGATACGGAT Thread-2
ACCAAGGTAT Thread-1
GGGTGCATTA Thread-2
TACCCGGCCA Thread-2
CCCTAAGGAG Thread-1
CAAACGTCCA Thread-2
CTTGAGTGCA Thread-2
Thread-1 Elapse Time 4
CGTTCTCTTC Thread-2
Thread-2 Elapse Time 4

```




## Reference

https://stackoverflow.com/questions/23282319/java-creating-a-string-of-length-x-with-random-chars   
https://www.baeldung.com/java-measure-elapsed-time    
https://www.geeksforgeeks.org/java-program-to-run-multiple-threads/   
https://www.geeksforgeeks.org/how-to-get-the-id-of-a-current-running-thread-in-java/      
https://pediaa.com/what-is-the-difference-between-single-thread-and-multi-thread-in-java/
