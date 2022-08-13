# NOAEL
![GitHub forks](https://img.shields.io/github/forks/ifyoungnet/NOAEL.svg?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/ifyoungnet/NOAEL.svg?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/ifyoungnet/NOAEL.svg)

 A pipeline for NOAEL prediction
## How to form your own prediction pipeline:
The details of constructing your own workflow are shown in **Figure 1** and **Figure2**. 
Explanation of workflow: 
#### 1) The local model file is read by the Model Reader node above, while the below reads the model-Normalizer.zip file for normalizer; 
#### 2) The node of File Reader is used to read the data that needs to be predicted; 
#### 3) Convert numbers of label to strings using Number to String node is required in classification models; 
#### 4) Select the corresponding prediction node according to the model read by the model reader;
#### 5) Output for the prediction result. In addition, evaluation nodes can be chosen according to your task.

![image](https://github.com/ifyoungnet/NOAEL/blob/main/SCO-R%20for%20classification.svg)
<p align="center">Figure 1. KNIME usage example of classification model.</p>

![image](https://github.com/ifyoungnet/NOAEL/blob/main/SCO-R%20for%20regression.svg)
<p align="center">Figure 2. KNIME usage example of NOAEL prediction model.</p>

![image](https://github.com/ifyoungnet/NOAEL/blob/main/Application%20Domain.svg)
<p align="center">Figure 3. KNIME usage example of application domain.</p>

## Publication
> Jie Qian, Rui Liang, Fang-liang Song, Xue-jie Wang, Ying Liang, Wen-bin Zeng, Jie Dong. NOAEL prediction and explanation by systematic comparison of different machine learning methods and descriptors. Food and Chemical Toxicology, Available online 10 August 2022, 113325.

## Contact
  
  * Dong Jie <jiedong@csu.edu.cn> 
