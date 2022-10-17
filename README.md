# AFGR-48: Image classification dataset for remote sensing Aircraft Fine-Grained Recognition.
## Dataset Overview 
AFGR-48 dataset is a challenging **48-class** geospatial fine-grained aircraft classification dataset. The dataset contains a total of **29828** aircraft instances from VHR optical remote sensing images which are acquired from Google Earth with **spatial resolution ranging from 0.3 to 0.7m**. The dataset provides two official splits for researchers to train and test fairly. The example structure of the AFGR-48 dataset is shown as below: <br>  
* **AFGR-48 Data Structure** `[official split: 25% for train and 75% for test]` <br>  
```
└─ ── 25-75  
      └── ─ train
      |        └── A0
      |        |     ├── A0_0.jpg
      |        |     └── ...  
      |        |     └── A0_xx.jpg 
      |        └── A1
      |        |     ├── A1_0.jpg
      |        |     └── ... 
      |        |     └── A1_xx.jpg 
      |        └── ...
      |        └── A47  
      |             ├── A47_0.jpg
      |             └── ...
      |             └── A47_xx.jpg
      └── ─ val
              └── A0
              |     ├── A0_0.jpg 
              |     └── ... 
              |     └── A0_xx.jpg  
              └── A1 
              |     ├── A1_0.jpg
              |     └── ...  
              |     └── A1_xx.jpg  
              └── ... 
              └── A47  
                   ├── A47_0.jpg 
                   └── ...
                   └── A47_xx.jpg 
```
* **Instance Samples** <br>  
![Samples1](https://github.com/wgqqgw/BIT-KTYG-AFGR/edit/main/Figures/Aircraft-samples1.gif)<br>
![Samples2](https://github.com/wgqqgw/BIT-KTYG-AFGR/edit/main/Figures/Aircraft-samples2.gif)<br>
## Dataset Download
The AFGR-48 Dataset will be release soon in a few weeks, please stay tuned for its update!<br>
If you have any questions, please write the it in the issue column, and I will answer it as soon as possible! Thank you!<br>
