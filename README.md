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

Times:
```
Biotin
100%|█████████████████████████████████████| 12897/12897 [02:21<00:00, 91.39it/s]
[22:48:49] Final unsuccessful reads summary (100.0% reads unsuccessfully processed; 12897 total reads):
   100.0% (  12897 reads) : Tombo data exists in [--corrected-group] and [--overwrite] is not set           
[22:48:49] Saving Tombo reads index to file.
12.33user 6.63system 2:24.47elapsed 13%CPU (0avgtext+0avgdata 119560maxresident)k
1614784inputs+103192outputs (2major+37805minor)pagefaults 0swaps
```
