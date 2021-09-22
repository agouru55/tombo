# Tombo Code

Installation steps:
```
conda create tombo python=3.7

conda install -c bioconda ont-tombo
conda install -c bioconda ont-fast5-api

conda config --add channels conda-forge
conda install progressbar33
```
Creating directories:
```
guppy5single
multi_to_single_fast5 -i /mnt/isilon/wang_lab/shared/datasets/CU_data/guppy5/A647/workspace -s /mnt/isilon/wang_lab/shared/datasets/CU_data/guppy5single/A647/workspace
cp /mnt/isilon/wang_lab/shared/datasets/CU_data/Spel_ref/trainseq3.fa /mnt/isilon/wang_lab/shared/datasets/CU_data/guppy5single
```

