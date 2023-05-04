# U-Net Implemention for Brain Tumor Segmentation
This repository contains implementation of U-Net architecture for brain tumor image segmentation created as part of project work for the Advanced Topics in Machine Learning course[ITI41820-1 23V] as a requirement for Master's in Applied Computer Science Program at Østfold University College.

## Dataset
The project has utilized the LGG Segmentation dataset, which is a publicly available dataset from The Cancer Imaging Archive (TCIA) and comprises data from 110 patients included in The Cancer Genome Atlas (TCGA) lower-grade glioma collection. The dataset is a pruned version of the [original dataset](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation) from kaggle.

Link to the dataset used for the project: https://drive.google.com/file/d/1YiU8rFyePAHl6B_xyXCuq0XbOlJ3fkjv/view?usp=share_link



## Steps to run the project:
Google Colab was used to build the project. In order to run the implementation follow the given steps:
- Clone the repo and upload the .ipynb file from the project to google colab.
- Download the [dataset](https://drive.google.com/file/d/1YiU8rFyePAHl6B_xyXCuq0XbOlJ3fkjv/view?usp=share_link). 
- You can either upload it directly into the colab or on your google drive. 
- Add the path/link of the dataset to `zip_file_path` variable. 
    - If you have uploaded the zipped file on the google drive mount google drive or else it is not needed.
 
 
 Here is the link of [pre-trained model](https://drive.google.com/file/d/1EOliq1n-_0S6xBqlLMyvZzmeFlONn_1U/view?usp=sharing) for the tumor segmentation. It requires 3 input channels, 1 output channel, and 48 features in the first layer.
    

