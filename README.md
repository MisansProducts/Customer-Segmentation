# Customer Segmentation

Customer Segmentation prediction project for Python 3.11.5 (conda)

## Applications

* [Miniconda](https://docs.conda.io/en/latest/miniconda.html "Miniconda download")
* [Visual Studio Code](https://code.visualstudio.com/download "Visual Studio Code download")
* [Jupyter Iteractive Extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter "Jupyter Extension for Visual Studio Code installation page")
* [ipykernel](https://pypi.org/project/ipykernel/ "ipykernel for Jupyter")
* [Jupyter Notebook](https://jupyter.org/ "Jupyter Notebook download")
* [CUDA Toolkit 11.7](https://developer.nvidia.com/cuda-11-7-0-download-archive?target_os=Windows&target_arch=x86_64&target_version=10 "CUDA Toolkit 11.7 for Windows")
* `conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia`

## Required Libraries

* [Matplotlib](https://matplotlib.org/)
* [NumPy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [seaborn](https://seaborn.pydata.org/)
* [scikit-learn](https://scikit-learn.org/stable/)

## Credits

Alex Akoopie - Creator

# Analysis

Evaluation metrics:

```
Silhouette Score:           0.6519131785153831
Davies-Bouldin Index:       0.7904446163857773
Calinski-Harabasz Index:    4945.527694494468
```

![Raw Online Retail Data](imgs/1_data.png)

![Scatterplot and Histogram of Cleaned Data](imgs/2_cleaned_data.png)

![Confusion Matrix Graph](imgs/3_confusion_matrix.png)

![PCA Clustering Graph](imgs/4_pca_clustering.png)