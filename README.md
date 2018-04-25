This is the final project for STATS 663 at Duke University. We (Yan Zhao and Rui Wang) implement sparse singular value decomposition algorithm and pack it into a package 'biclustersvd'. You can install it through !pip install git+git://github.com/yzha0802/bicluster.git Also, we optimize this algorithim and apply this algorithim on both simulation dataset and lung cancer dataset.This repository includes following files
Optimization.ipynb
We use JIT, multiprocess and ipyParallel to optimize original python code
lung cancer data plot.ipynb
We use ssvd algorithim on real lung cancer data stored in lung cancer data.txt to visuallize how this algorithim identify coregulated genes.
Simulation.ipynb
Implementation of Biclustering via SSVD
pdf report
