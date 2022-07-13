# NSCGCN

This is the Python implementation of our paper: "NSCGCN: A Novel Deep GCN Model to Diagnosis COVID-19"

We will open all source code after our paper is accepted.

# Table of Contents

* [Team Members](#1)
* [Journal Paper](#2)
* [Installation](#3)
* [Dependencies](#4)
* [Directory Structure](#5)
* [Method Overview](#6)
* [Dataset](#7)
* [Results](#8)
* [Contact](#9)

# Team Members<a name='1'></a>

# Journal Paper<a name="2"></a>

If you find this work useful for your publications, please consider citing:

```

```



# Installation<a name="3"></a>

1. Make sure you have anaconda3 setup on your system.

2. Install requirements as：

   ```
   conda install pytorch==1.9.0 torchvision==0.10.0 torchaudio==0.9.0 cudatoolkit=10.2 -c pytorch
   pip install dgl-cu102==0.5.3
   ```

   # Dependencies<a name="4"></a>

Our project is built using Python 3.8.8 and the following packages: 

```
pands = 1.3.0
nibabel = 3.2.1
matplotlib = 3.4.2
```

# Directory Structure<a name="5"></a>

```
+-- NSCGCN
|   +-- CT dataset
|   |   +-- preprocess.ipynb
|   +-- CXR dataset
|   |   +-- preprocess.py
```

# Method Overview<a name="6"></a>

# Dataset<a name="7"></a>

We have used the [CT dataset](https://www.kaggle.com/andrewmvd/covid19-ct-scans)  and the [CXR dataset](https://www.kaggle.com/amanullahasraf/covid19-pneumonia-normal-chest-xray-pa-dataset) for evaluation of our proposed method. 

# Results<a name="8"></a>

# Contact<a name="9"></a>

In case of doubt or further collaboration, feel free to email us ! 😊

* [Chaos Hu (chaos.hu.edu@gmail.com)](mailto:chaos.hu.edu@gmail.com)
