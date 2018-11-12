# Gannon Lab RNAseq
#### Experiment: 
 (1) RIN>5. send your sample to the core for quality check, and discuss with the core for the RIN requirments. (2) Extract RNA, sequence together.  (3). n>=3
#### Computational resources:
 (1). workstation with all software installed or (2) accre acount 
#### Time (plan your experiment):
 (1). RNA extraction 30min-4 hrs
 (2). accre requires 3 training, 1-3 weeks
 (3). sequencing requires 1 month
 (4). Data analysis < 1 week (data transfer might take 2 days)
#### Steps
##### Biology
(1). standard RNA extraction
(2). submit request for QC through ilab
##### Analysis
(1). transfer the results to accre or your computer, eg: <br>
rsync -arv  --progress  /Volumes/2234/ &nbsp;&nbsp; zhux12@login7.accre.vanderbilt.edu:/scratch/zhux12/newData <br>
(2). check the sequencing quality, submitting:fastqc_check.slurm


