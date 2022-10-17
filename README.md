# AFGR-48: Image classification dataset for remote sensing aircraft fine-grained recognition.
## 1.Dataset Overview 
AFGR-48 dataset is a challenging 48-class geospatial fine-grained aircraft classification dataset. The dataset contains a total of 29828 aircraft instances from VHR optical remote sensing images which are acquired from Google Earth with spatial resolution ranging from 0.3 to 0.7m. The dataset provides two official splits for researchers to train and test fairly. The structure of the AFGR-48 dataset is shown as below: <br>  
*AFGR-48 [official split: 25% for train and 75% for test] <br>  
'''
| ── 25-75  
|    └── train
|        └── A0 <br>  
|            ├── A0_0.jpg
|            └── ...  
|          └── A0_xx.jpg 
|       └── A1
|            ├── A1_0.jpg
|            └── ... 
|            └── A1_xx.jpg 
|        └── ...
|        └── A47  
|            ├── A47_0.jpg
|            └── ...
|            └── A47_xx.jpg
|    └── val
|       └── A0
|           ├── A0_0.jpg 
|            └── ... 
|            └── A0_xx.jpg  
|        └── A1 
|            ├── A1_0.jpg
|            └── ...  
|            └── A1_xx.jpg  
|        └── ... 
|        └── A47  
|            ├── A47_0.jpg 
|           └── ...
|           └── A47_xx.jpg 
'''
