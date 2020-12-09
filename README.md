# EE542_final

## Usage

Final project for EE542

Our project is based on one of the Kaggle competition  ————————  MoA prediction

To run our scripts, several packages need to be installed first. 

It's best to run our scripts directly on kaggle platform because all packages we used are on that platform and those packages can be imported and installed directly through platform without the need of pre-installation on your computer. But still, you can run our scripts on other places as well and you probably need to pre-install these packages on your computer. 


Here's a list of packages we used: (you can search the name and import into your data folder if you use Kaggle)

1. iterative Statifiers: iterative-stratification/iterative-stratification-master

2. pytorch gpu(this is not mendatory, but this can speed up the calculation): 
pytorch16gpu/torch-1.6.0cu101-cp37-cp37m-linux_x86_64.whl

3. stratificater for TabNet: iterative-stratification-tabnet/iterative_stratification-0.1.6-py3-none-any.whl



## Overview

<img src = './picture/001.png'>


1) Feature Engineering

For feature engineering, besides basic feature statistics, we use RankGauss + PCA + VarianceThreshold. 


### Raw Data: 

        <img src = './picture/002.png'>


### Basic Feature Statistics: 

cp_type:

        <img src = './picture/003.png'>



gene data:

        <img src = './picture/004.png'>


cell viability data:

        <img src = './picture/005.png'>


Number of target classes that each sample has:

        <img src = './picture/006.png'>


10 largest number of labels in the scored targets:

        <img src = './picture/007.png'>











