# Fashion Image Recommender

![poster](./image_recommendation.png)

## Architecture



**Model:**  VGG16 Xception 

**Data set:** Amazon Image recommender dataset [link](https://cseweb.ucsd.edu/~jmcauley/datasets.html).

**Product Category Prediction Task:** Xception model with transfered learning.

**k-NN indexer:** Annoy library  by spotify [link](https://github.com/spotify/annoy).

**k-NN engine for similarity retrieval:**  the k-NN engine will retrieve the nearest 30 feature vectors and their product id in the predicted product category through similarity retrieval


## Citation:
```
Ups and downs: Modeling the visual evolution of fashion trends with one-class collaborative filtering
R. He, J. McAuley
WWW, 2016
(http://cseweb.ucsd.edu/~jmcauley/pdfs/www16a.pdf)

Image-based recommendations on styles and substitutes
J. McAuley, C. Targett, J. Shi, A. van den Hengel
SIGIR, 2015
(http://cseweb.ucsd.edu/~jmcauley/pdfs/sigir15.pdf)

Image-based Product Recommendation System with Convolutional Neural Networks
Luyang Chen, Fan Yang, Heqing Yang
CS231n, 2017
(http://cs231n.stanford.edu/reports/2017/pdfs/105.pdf)
```