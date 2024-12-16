# mbshh Fosl2 project

# Installation instructions
1. Get conda. See the tutorial at https://github.com/chavez-lab/protocols/tree/main/Setting_up_your_workstation.
2. Install DESeq2 and other dependencies. The instructions to run this are at the end of [fosl2-de.yml](fosl2-de.yml).
3. Download the [source data](https://1drv.ms/f/c/a836ccc14c371f14/Et_l2PKv3LpNqKWNUd4ne80Bp7_OHk7-akbvq773RUL4tA?e=nA3e52) and put it in $ROOT/data, where $ROOT is the base directory of this project:
```
> tree .
.
├── README.md
├── data
│   ├── counts_exon_uns.txt
│   └── sample_metadata.txt
├── deseq2_glu_bapta.ipynb
├── fosl2-de.yml
└── out
    ...
```
