# hse_hw2

Cell line DOHH2, histone mark H3K4me3.

[Colab](https://colab.research.google.com/drive/1xkBMFOYPGhX4Hs7gmPRdoaYu4vKWXkNj?usp=sharing)


## FastQC

1st ChipSeq replica | 2nd ChipSeq replica | Control
--- | --- | ---
[ENCFF545NBQ](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/ENCFF545NBQ_fastq.html) | [ENCFF002BAK](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/ENCFF002BAK_fastq.html) | [ENCFF002AYR](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/ENCFF002AYR_fastq.html)

### ENCFF545NBQ
![NBQ1](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/NBQ1.png)
![NBQ2](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/NBQ2.png)

### ENCFF002BAK
![BAK1](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/BAK1.png)
![BAK2](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/BAK2.png)

### ENCFF002AYR
![AYR1](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/AYR1.png)
![AYR2](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/AYR2.png)

We do not need to crop reads due to the appropriate number of them.


## Alignments

Chromosome 17.

Number of Reads | Unique | Non-unique | Unaligned
--- | --- | --- | ---
8422794 | 393616 (4.67%) | 619566 (7.36%) | 7409612 (87.97%)
27694840 | 1322950 (4.78%) | 2867911 (10.36%) | 23503979 (84.87%)
34229117 | 1326647 (3.88%) | 4412257 (12.89%) | 28490213 (83.23%)

The alignment percentage is low because we aligned the reads to a single chromosome, which represents only a small portion of the genome.

## Venn Diagrams

![Intervene_venn_1](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/Intervene_venn_1.jpg)
![Intervene_venn_2](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/Intervene_venn_2.jpg)
![Intervene_venn_3](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/Intervene_venn_3.jpg)
![Intervene_venn_4](https://github.com/ilyagerman52/hse_hw2_chip/blob/main/data/Intervene_venn_4.jpg)

There were also few intersections due to alignment to a single chromosome.
