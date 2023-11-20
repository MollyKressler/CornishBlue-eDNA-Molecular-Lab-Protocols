## Adapted from Genner Lab's tilapia qPCR protocol 
[https://github.com/genner-lab/Molecular-Lab-Protocols/blob/868019ebafdb5e1de031877ad83f4aa89867e397/tilapia-qpcr-assays.md]

#### Created by Rupert Collins, Andy Saxon, Martin Genner :: March 2022
#### Adapted and used by Molly Kressler, Lucy Whitelegg and Andy Saxon :: November 2023 

### Appendix 3

#### Oligonucleotide sequences for quantification standards

| Species | Assay | Base pairs | Oligonucleotide sequence (5&prime; -> 3&prime;) |
| :--- | :--- | :--- | :--- |
| _Oreochromis leucostictus_ | leuco | 70 | CTCTGCCCTACTGCACTCGAGCACCATAGTCGTAGCCGGCATCTTCCTTCTCATCCGTATAAGCCCCATG |
| _Oreochromis niloticus_ | nilo | 127 | TGGAGGTTTTACCCTACAGACCTTTAGCATTGCTCAAGAAAGTGTCTGACTAATCCTTCCCGCCTGACCTTTAGCCGCTATATGATACATTTCCACACTTGCAGAAACTAACCGAGCTCCCTTCGAC |
| _Oreochromis urolepis_ | uro | 95 | CTAAGCCTCGTGTTAACTCCAGTACCACAAACAACGTCAACAACAACACTCACGCCCCCAACACCAAAACACCTCCACCTGCCGAATACATCAAA |

#### Diluting quantification standards

* [IMPORTANT NOTE] the standards are supplied dried and HIGHLY concentrated, and must be prepared in a separate area and using separate pipettes to those used for DNA extraction and PCR reaction preparation. Bleach the area thoroughly after use.
* All traces of them must be kept seperate from the other reagents because they are indistinguishable from real tilapia DNA and can lead to severe false positive contamination problems.
* Always use TE buffer to dilute the stocks of quantification standards. Ultrapure water can be used for serial dilutions as these will be discarded after use.
* Prepare the standards as follows (initial steps only need to be done once):

1. Spin down the supplied oligo tubes to collect the dried oligonucleotides.
2. If shipped at 4 nmol, add 40 &micro;L of TE buffer to dilute to 100 pmol/&micro;L.
3. Incubate for 5 min at room temperature, and vortex for 1 min.
4. Use the online [NEBioCalculator ssDNA Convertor](https://nebiocalculator.neb.com/#!/ssdnaamt) to calculate the mass of single-stranded DNA given the molarity.
5. Select the "Moles -> Mass" tab, and paste the full DNA sequence (from table above), and set the DNA moles to 100 pmol.
6. The result is a DNA mass of 2.132 &micro;g/&micro;L (= 2132 ng/&micro;L).

| <img src="assets/kressler-moles2mass.png" width="500"> |
| :---: |

7. Now move to the "Mass -> Moles" tab and insert the DNA mass of 2.132 &micro;g.
8. The result is a DNA copy number of 6.021e+13 (or 60 trillion, 210 billion) copies per microlitre.

| <img src="assets/kressler_mass2moles_copynumber.png" width="500"> |
| :---: |

9. To make a 10 ng/&micro;L stock in 1 mL volume, add 4.7 &micro;L of 100 pmol/&micro;L stock to 995.3 &micro;L TE buffer, and vortex thoroughly.
10. Use an [online dilution calculator](http://www.desiquintans.com/dilutioncalc) as follows: 

| <img src="assets/kressler_dna-conc.png" width="500"> |
| :---: |

11. Recalculate the DNA copy number of this 10 ng/&micro;L stock (= 2.824e+11 copy/&micro;L, or 282.4 billion copies).
12. Dilute again down to a 1 billion copy/&micro;L stock by adding 3.5 &micro;L of 10 ng/&micro;L stock to 996.5 &micro;L TE buffer, and vortex thoroughly.

| <img src="assets/billion-copies.png" width="500"> |
| :---: |

13. These stocks should be frozen and kept in different boxes to the PCR reagents.

