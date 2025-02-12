# find files by pattern and concatenate them using commas
FASTQ_DIR=data  
reads1_pat=_R1_  
find -L ${FASTQ_DIR} -name "*$reads1_pat*" -type f | sort | paste -sd, -


[other resources](https://github.com/stephenturner/oneliners?tab=readme-ov-file)
