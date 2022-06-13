# Machine Learning

## Description
Teman Tani is an android-based application that can recognize 5 kinds of diseases on rice leaves using machine learning, namely Leaf Blast, Brown Spot, Hispa, Tungro, and Blight. After detecting the disease, the application will provide appropriate pesticide recommendations.

## Rice plant disease detection system
We use Inception V3 for pretrained model. <br/>
nception V3 is a 42 layer deep learning network with
fewer parameters. Parameter reduction is done
with the help of convolution factoring. With more parameters
slightly, the model will overfit less and increase accuracy .
The Inception V3 model is widely used in image recognition and
specified CNN network. Inception V3 already has a dataset
which is called ImageNet which contains 1000 different categories of objects. Model
Inception V3 has a size of 92 MB, entered as top-1
accuracy is 0.779 and top-5 accuracy is 0.931 with parameters
of 23,851,784

We save our model.h5 and put it into the google drive [link](https://drive.google.com/file/d/194Aq8VsG872lwMThfZqWkJnKZCp46oSq/view?usp=sharing)

## Pesticide recommendation system
The 2 Types of Recommendation System<br />
  * Collaborative Filtering <br />
  It primarily makes recommendations based on inputs or actions from other people (rather than only the user for whom a recommendation is being made).
  * Content-Based <br/>
  Content-based systems make recommendations based on the user’s purchase or consumption history and generally become more accurate the more actions (inputs) the user  takes.<br/>
  Here we use content based recommendations system by name similarity.

## Dataset
* Detection system<br/>
We use a dataset already available on kaggle
  * [Dataset 1](https://www.kaggle.com/datasets/shayanriyaz/riceleafs ).
  * [Dataset 2](https://www.kaggle.com/datasets/chandrug/riceleafdisease)
* Recommendation system<br/>
We do data scraping on the Tokopedia website. We take the name, review, rating, price, weight, seller's address and pictures of pesticide products
we use chrome extension Web Scraper - Free Web Scraping
0.6.4 to do scraping, that you cand find [here](https://chrome.google.com/webstore/detail/web-scraper-free-web-scra/jnhgnonknehpejjnehehllkliplmbmhn?hl=id).

## Reference

* Recommendation system in [here](https://www.researchgate.net/publication/349409277_An_effective_feature_extraction_method_for_rice_leaf_disease_classification)
  * [Ref 1](https://www.researchgate.net/publication/349409277_An_effective_feature_extraction_method_for_rice_leaf_disease_classification)
  * [Ref 2](http://repository.ittelkom-pwt.ac.id/7005/)
* Build Content-based recomendation system in [here](https://www.kdnuggets.com/2020/07/building-content-based-book-recommendation-engine.html)
