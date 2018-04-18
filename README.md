# nucleotide-frequencies
calculate the nucleotide frequencies

Running the Perl script on all the fasta files
`for file in `ls *.fa`; do echo $file; calculate_nuc.pl $file; done`

```bash
for file in `ls retrieve-seq_2018-03-01.101*`; do echo $file; perl calculate_nuc.pl $file; done
retrieve-seq_2018-03-01.101106_Upstream.fasta
Length = 418390
A: 80445
C: 127814
G: 131813
T: 78318
Other: 0
GC: 62.05
AT: 37.95
retrieve-seq_2018-03-01.101229_ORF.fasta
Length = 3996979
A: 671441
C: 1288134
G: 1345344
T: 692060
Other: 0
GC: 65.89
AT: 34.11
retrieve-seq_2018-03-01.101329_Downstream.fasta
Length = 242526
A: 44412
C: 75826
G: 79083
T: 43205
Other: 0
GC: 63.87
AT: 36.13
```
