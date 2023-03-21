# Basic-Stock-Analysis-with-PySpark
Using PySpark to Analyze Stock Prices

## 1. Introduction

Spark is one of the most popular distributed processing technologies for Big Data. PySpark is the pyton api for spark that enables access to the spark cluster. The architecture of a Spark cluster can get complex, but a simple method for getting started is to simply deploy a standalone cluster on Docker. Luckily, Jupyter already made a Docker image for just such a deployment. Here we pull this image from Dockerhub and use it to analyze stock prices and predict intraday returns.

## 2. Getting Started

### 2.1. Prerequisites
In order for the code in this tutorial to work, you must have the following installed on your system:
1. Docker
2. Docker Compose
3. Git

### 2.2. Getting Started

Here are the basic steps to get started using this repository.

1. Clone this repo locally using ```git clone https://github.com/julianwileymac/Basic-Stock-Analysis-with-PySpark/```
2. Run ```docker-compose up``` in the root directory
3. Navigate to the localhost address that is produced by the above command (CTRL + click for VS Code)
4. You may have to upload the data files and notebook to the pyspark instance ([Instructions](https://jupyterlab.readthedocs.io/en/stable/user/files.html))
5. Run the [code](../Basic-Stock-Analysis-with-PySpark/basic_lin_reg.ipynb).

