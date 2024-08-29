### After the paper is accepted, the complete dataset will be made public.
# CycleGAN-based-intrusion-detection[paper]
![image](https://github.com/poshangcun13/CycleGAN-based-intrusion-detection/blob/main/ALL.png)
## Abstract
 A high-quality traumatic brain injury (TBI) dataset is essential to intelligent assisted diagnosis. In this work, we present a new labeled public TBI dataset containing head CT scans and various examination variables. The dataset was collected from 545 patients with moderate to severe TBI and CT annotations were produced. We provide example applications of segmentation, multilabel classification, and in-hospital mortality prediction models.
## Configuring the environment
 Open File：requirements.txt
## DataSets
 KDD99、CIC_DDOS2019、CIC_IDS2018,It should be noted that these three compressed data packages need to be downloaded separately and ***cannot be directly used for Git clones***. Each one needs to be downloaded one by one.\
 File type：image data
### DataSets
In order to better increase the generalization of the code, the batch size of this repository code is set to 1
### Data processing
 ***Z-scores***
## Using Frames
### Download code
 Decompression：IDS_KDD99、CIC_DDOS2019、CIC_IDS2018
### Data enhancement
![image](https://github.com/poshangcun13/CycleGAN-based-intrusion-detection/blob/main/data%20enhancement.png)
### Run code
 Train the model to detect individual attacks：run attacks.py\
 Model monetization of test set: run predict.py
### Performance analysis
![image](https://github.com/poshangcun13/CycleGAN-based-intrusion-detection/blob/main/FNR-FPR.png)

