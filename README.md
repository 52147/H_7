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

If we don't use sleep() to boserve the multi thread program and Single Thread program, there is no difference between these two because run time too fast.

|  | Single Thread  | Multi Thread |
| ------------- | ------------- | ------------- |
| run time | 3s  | 4s  |

If we use sleep() in multi thread program, we can observe that five thread print genome sequence at the same time then keep iterating until create 100 genome sequence which means 5 thread execute concurrently.   
## Output
### `Single Thread`

```
CGCATGAATC main
GGTGCAGTGT main
GCACCCCACC main
CCAGTGAGGT main
GCGACGGTGC main
AGTACACTTT main
ACCCTGCGGG main
ACCCTGGTGA main
TCGTTCACAC main
GTTCACCACC main
TGGGTGGAAA main
GTAGCCAGAG main
GAGCCACATC main
GTACCACCTA main
TACGGACACA main
AAGTAAGATT main
CACTTGGCCT main
TCTTCCTTCC main
CGTACCTGCA main
AACGCCGTAG main
TAACATGCTA main
TCCCCGCTGG main
GCTCTTTGTT main
AAGAAAATCC main
AAATTTGATT main
ATCCGAGCAT main
ACTAGAGAGA main
GTCATCTCGG main
CTTATAGCTC main
TCGAATGTCT main
AACCAGTAGC main
GGCACATGAG main
GCATGTTGAA main
TGGTAATTCT main
CACCGAGCTT main
CCCGCGCCTT main
GGGTAGGGAT main
ACTCAATTCG main
TCAATAAGTG main
TAGCAGTCAT main
AGACACCTAG main
TCGTCTCACG main
AAATTGATCC main
TGCTAGACAT main
CCGGGGACCC main
CATAATGGCT main
TGGCAAGGTG main
GGTGGTAGCT main
GGGTTAATAA main
CAGCCCGCCC main
CTTGCCGATC main
TTTGCTCTGG main
CTACCCAGGG main
TCTCGCGCCG main
ACGCGCCGAG main
CGCGTGCAGA main
TTGCACTTTT main
AACGACTGCA main
AAGTGTTACC main
GGACATCCCA main
GTTTTGCCTA main
CTTGCAACTA main
AACGATACCT main
CGGGTTTGTA main
GAAGTTACTA main
ATTCTCAGTG main
ATTCGACGTT main
AGGAGCACTA main
GCGCGAAAAA main
TGGTCTAACA main
GCTCGATTTG main
CTGTGGATCT main
AGGGATGAGA main
CCGTTTCCAA main
GATTGCCTAA main
TCCCCCCCTA main
CAGGCCGTGC main
TAATACGACT main
GTATAAAAGA main
GTTCGATGTG main
AGGTTGCGGA main
ATGCCGGCTA main
AGTCGCATTA main
CATTTCGGTC main
CGTAACACGA main
AGTGTGTCGG main
TTTAGCTGAA main
GGTCGAGGGG main
TTCGCGCATT main
CACCAGGCAC main
CTTACATCTA main
CGGCTCAACT main
CAAGTCGTGG main
TATCAGGCGT main
GGTGAGACTT main
GCATCAATTG main
TCGGTAAATC main
ATAGTGGCGA main
CTACGACAAA main
ACTCCTTGAA main
main Elapse Time 3

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
## Notice
In single thread program, we don't need to extends Thread class because we already have one main thread in class.      
Every java program have at least one thread called main thread, which invokes the main().



## Reference
https://stackoverflow.com/questions/22051031/is-java-main-method-a-thread
https://stackoverflow.com/questions/23282319/java-creating-a-string-of-length-x-with-random-chars   
https://www.baeldung.com/java-measure-elapsed-time    
https://www.geeksforgeeks.org/java-program-to-run-multiple-threads/   
https://www.geeksforgeeks.org/how-to-get-the-id-of-a-current-running-thread-in-java/      
https://pediaa.com/what-is-the-difference-between-single-thread-and-multi-thread-in-java/
