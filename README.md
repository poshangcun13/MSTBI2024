### After the paper is accepted, the complete dataset will be made public.
# MSTBI: Head CT Detection and Prognostic Assessment of Traumatic Brain Injury Dataset[paper]
![image](https://github.com/poshangcun13/MSTBI2024/blob/main/fig1.png)
## Abstract
 A high-quality traumatic brain injury (TBI) dataset is essential to intelligent assisted diagnosis. In this work, we present a new labeled public TBI dataset containing head CT scans and various examination variables. The dataset was collected from 545 patients with moderate to severe TBI and CT annotations were produced. We provide example applications of segmentation, multilabel classification, and in-hospital mortality prediction models.
## Configuring the environment
 Open File：requirements.txt
## Advantages of the dataset
***Specialized TBI data:*** Compared to the datasets of proposed in [16], [17] and [18], the proposed dataset is specialized for moderate to severe TBI.\
\
 ***Extensive CT image annotation:*** Each CT slice was meticulously annotated by a radiologist to encompass all potential subtypes of ICH and the corresponding hemorrhagic area masks.\
 \
 ***Multimodal TBI data:*** In contrast to [15] and [18] datasets, the proposed dataset includes demographic information, clinical data, imaging data, and other relevant information. It can be used for studies of multi-label classification, instance segmentation and prognosis prediction.\
 \
 File type：image data
### DataSets
A retrospective study was designed to collect brain CT scans, clinical data, and other relevant information from patients with TBI and was approved by the Ethics Committee of the Tianjin No. 4 Central Hospital (SZXLL-2023-KY028). The dataset included any patient admitted for TBI between the ages of 18 and 80 years with moderate to severe TBI and a GCS score of 3 to 13. Patients who did not have an admission CT head scan prior to neurosurgical intervention and patients without any recorded information were excluded. Each subject's personal information was anonymized.\
Data were collected on 545 patients with TBI from 2013 through 2024.The mean age of the patients in the MSTBI dataset was 55.8 years, with 420 males and 125 females. A non-enhanced CT scan consisted of approximately 60 slices with a slice thickness of 2.5 mm. The CT images were saved in two formats: as PNG images and as DICOM raw files. The pixel size of the images was uniformly set to 512×512 pixels. As illustrated in Fig. 1, the CT slices were classified into five categories based on the distinct locations of ICH: intraparenchymal hemorrhage (IPH), intraventricular hemorrhage (IVH), epidural hemorrhage (EDH), subdural hemorrhage (SDH), and subarachnoid hemorrhage (SAH). Two radiologists applied the Labelme software to the ICH region to generate a mask for each slice, and the type of hemorrhage was recorded. Figure 2 illustrates an annotated example of CT slices from the aforementioned dataset. Figure 2(a) depicts the original CT slice. Figure 2(b) depicts the ground truth, with different colors representing the various types of hemorrhage. Figure 2(c) provides a detailed account of the labels included in the CT slice.
### Data feature
 Table I lists the clinical characteristics of the patients involved in the constructed MSTBI dataset. The data set included information on patient demographics, the mechanism of injury, the initial clinical examination results following admission, qualitative imaging variables, and discharge information. The characteristics collected were referenced to benchmarks performed by previous researchers in order to facilitate comparison.\
 ![image](https://github.com/poshangcun13/MSTBI2024/blob/main/table1.png)
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

