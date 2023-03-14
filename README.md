# AFGR-50: Image classification dataset for remote sensing Aircraft Fine-Grained Recognition.
## Dataset Overview 
AFGR-48 dataset is a challenging **50-class** geospatial fine-grained aircraft classification dataset. The dataset contains a total of **12500** aircraft instances from VHR optical remote sensing images which are acquired from Google Earth with **spatial resolution ranging from 0.3 to 0.7m**. The dataset provides two official splits for researchers to train and test fairly. The example structure of the AFGR-50 dataset is shown as below: <br>  
* **AFGR-50 Data Structure** `[official split: 20% for train and 80% for test]` <br>  
```
└─ ── 20-80  
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
              └── A49  
                   ├── A49_0.jpg 
                   └── ...
                   └── A49_xx.jpg 
```
* **Instance Samples** <br>  
![Samples1](https://github.com/wgqqgw/BIT-KTYG-AFGR/raw/main/samples/BIT-AFGR50-1.png)<br>
![Samples2](https://github.com/wgqqgw/BIT-KTYG-AFGR/raw/main/samples/BIT-AFGR50-2.png)<br>
## Dataset Download
The AFGR-50 Dataset will be released in a few weeks, please stay tuned for its update!<br>
If you have any questions, please write them in the issue column, and I will answer them soon! Thank you!<br>
