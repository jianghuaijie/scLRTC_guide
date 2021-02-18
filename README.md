# scLRTC_guide
The detailed guide(manual).pdf has shown how to use our demo and downstream analysis after imputation. If you don't use matlab or R, you can refer to this guide.pdf.<br>
## Dataset:
Usoskin, Zeisel dataset can be download from https://hemberg-lab.github.io/scRNA.seq.datasets/mouse/brain/.<br>
Pollen dataset can be download from https://hemberg-lab.github.io/scRNA.seq.datasets/human/tissues/.<br>
Yan dataset can be download from https://hemberg-lab.github.io/scRNA.seq.datasets/human/edev/.<br>
PBMC dataset can be download from https://support.10xgenomics.com/single-cell-gene-expression/datasets/2.1.0/pbmc4k.<br>
Mouse dataset can be download from https://github.com/ttgump/scDeepCluster/tree/master/scRNA-seq%20data.<br> 
Loh dataset can be download from this github.<br>
Petropoulos dataset can be download from https://www.ebi.ac.uk/arrayexpress/experiments/E-MTAB-3929/.<br>

## Downstream analysis dependences
Downstream analysis is implemented in R (>=3.6.2). Please install R (>=3.6.2) and all dependencies before downstream analysis.<br>
The analysis code can be found in https://github.com/jianghuaijie/scLRTC/tree/main/analysis.<br>
The SC3 package was downloaded from R Bioconductor (http://bioconductor.org/packages/release/bioc/html/SC3.html).<br>
The TSCAN package was downloaded from R Bioconductor(http://www.bioconductor.org/packages/release/bioc/html/TSCAN.html).<br>
The SEURAT package was downloaded from (https://satijalab.org/seurat/).<br>
The Splatter package was downloaded from R Bioconductor (http://www.bioconductor.org/packages/release/bioc/html/splatter.html).<br>
