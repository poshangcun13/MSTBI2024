### After the paper is accepted, the complete dataset will be made public.
# MSTBI: Head CT Detection and Prognostic Assessment of Traumatic Brain Injury Dataset[paper]
![image](https://github.com/poshangcun13/CycleGAN-based-intrusion-detection/blob/main/ALL.png)
## Abstract
 A high-quality traumatic brain injury (TBI) dataset is essential to intelligent assisted diagnosis. In this work, we present a new labeled public TBI dataset containing head CT scans and various examination variables. The dataset was collected from 545 patients with moderate to severe TBI and CT annotations were produced. We provide example applications of segmentation, multilabel classification, and in-hospital mortality prediction models.
## Configuring the environment
 Open File：requirements.txt
## Advantages of the dataset
***Specialized TBI data:*** Compared to the datasets of proposed in [16], [17] and [18], the proposed dataset is specialized for moderate to severe TBI.\\
 ***Extensive CT image annotation:*** Each CT slice was meticulously annotated by a radiologist to encompass all potential subtypes of ICH and the corresponding hemorrhagic area masks.\\
 ***Multimodal TBI data:*** In contrast to [15] and [18] datasets, the proposed dataset includes demographic information, clinical data, imaging data, and other relevant information. It can be used for studies of multi-label classification, instance segmentation and prognosis prediction.\\
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

