# oxford-102-flowers-data-set
This code shows how to build an image classifier by using deep learning model in order to recognize different 102 species of flowers. The data set is from Oxford repository which TensorFlow provides in TensorFlow datasets. A pre-trained model 'MobileNet' is utilised and then connected with keras dense layer having 102 output nodes.

## Install

- **1) Import Resources**
  tensorflow version >= 2.0.0
  tensorflow_datasets version >= 4.3.0+nightly
  ```
  !pip install grpcio
  !pip install tensorflow --upgrade --user
  !pip install tfds-nightly --user
  ```
- **2) Download data to default local directory "~/tensorflow_datasets"**
  `!python -m tensorflow_datasets.scripts.download_and_prepare --register_checksums=True --datasets=oxford_flowers102`
  
- **3) Download the file label_map.json**
  This file contains a mapping from label to category name, which is a dictionary mapping the integer coded labels to the actual names of the flowers.


