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

## Access the Dataset【2023.03.27】
We have made this dataset available through Baidu Drive for your convenience. You can access the dataset using the following links:

### Baidu Drive
- [Download Dataset from Baidu Drive](https://pan.baidu.com/s/1GTCRa-N2rpkEMaqZJb_hCw)

To download the dataset from Baidu Drive, you may need to enter the following extraction code: `<KTYG>`.

- **UPDATE 2023.04.01!!** We released a long-tailed distribution dataset, BIT-AFGR50-LT.

### Google Drive
BIT-AFGR50 will be available through Gooble Drive soon!


## License

This dataset is provided for **academic research purposes only**. By using this dataset, you agree to:

- Use the dataset solely for academic research, and not for any commercial purposes or applications that violate human peace and morality.
- Give appropriate credit to the dataset creators when citing the dataset in your research.

Any other use of this dataset is strictly prohibited. If you have questions about the usage of this dataset or want to request permission for a specific use case, please contact the dataset maintainer.


## Citation

If you use this dataset in your research or data analysis projects, please cite the following paper: https://doi.org/10.3390/rs15071773


Thank you for your interest in the Dataset Title, and we hope it proves useful in your research or data analysis projects! If you have any questions or require assistance, please feel free to open an issue on this repository or contact the dataset maintainer.

