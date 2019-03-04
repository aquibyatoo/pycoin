export conda environment ..
conda env export | grep -v "^prefix: " > environment.yml