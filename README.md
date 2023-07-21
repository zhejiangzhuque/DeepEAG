# DeepEAG
DeepEAG: An edge-powered graph neural network using SMILES augmentation for cancer drug response prediction
![image](https://github.com/zhejiangzhuque/DeepEAG/blob/main/model.jpg)
# Requirements
[environment prepare](http://www.cnblogs.com/sxdcgaq8080/p/7894828.html)
# Installation
DeepEAG can be downloaded by  

```git clone git@github.com:zhejiangzhuque/DeepEAG.git```  

Installation has been tested in a Linux/MacOS platform.
# Environment
```conda env create -f DeepEAG.yml```

```conda activate DeepEAG```
# Model implementation
Step 1: Data Preparing

Four types of raw data are required to generate genomic mutation matrix(copy number, Gene mutation, Gene methlation, Gene expression )

Data of the same class were saved as after normalization（[data/CCLE/Result_StandardScaler.csv](https://github.com/zhejiangzhuque/DeepEAG/blob/main/data/CCLE/Result_StandardScaler.csv)）
