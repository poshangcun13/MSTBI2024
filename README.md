### After the paper is accepted, the complete dataset will be made public.
# MSTBI: Head CT Detection and Prognostic Assessment of Traumatic Brain Injury Dataset[paper]
![image](https://github.com/poshangcun13/CycleGAN-based-intrusion-detection/blob/main/ALL.png)
## Abstract
 A high-quality traumatic brain injury (TBI) dataset is essential to intelligent assisted diagnosis. In this work, we present a new labeled public TBI dataset containing head CT scans and various examination variables. The dataset was collected from 545 patients with moderate to severe TBI and CT annotations were produced. We provide example applications of segmentation, multilabel classification, and in-hospital mortality prediction models.
## Configuring the environment
 Open File：requirements.txt
## DataSets
 PhysioNet: The PhysioNet dataset collected a dataset of 82 CT scans [15]. Two radiologists delineated the areas of ICH in each slice of the scans. Radiologists provided annotations for the presence of various types of ICH and fractures in each CT slice. However, the dataset contained only CT scans and the quality of the annotation was inadequate. Moreover, only semantic segmentation was feasible for the segmentation task.\
 RSNA: The RSNA dataset is available on the Kaggle Challenge with the goal of identifying subtypes of ICH from CT scans of the brain [16]. The dataset is substantial, containing over 25,000 CT scans with five distinct ICH subtypes. However, the data is only available for the classification task of cerebral hemorrhage and is not a dedicated TBI dataset.\
 CQ500: The CQ500 dataset was made publicly available in 2018 by the Mayo Clinic and Qure.ai [17]. CT scans can be used to identify medical information such as hemorrhages, fractures, and mass effects. However, the dataset is not exclusively from TBI patients, does not categorize subtypes of ICH, and does not have corresponding mask.\
 MIMIC-II: The MIMIC-III dataset is a critical care dataset [18]. The dataset contains multimodal data on patients admitted to the ICU, including laboratory results, demographic information, and examination variables. While the dataset can be filtered for data on TBI, it lacks imaging information.\
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

