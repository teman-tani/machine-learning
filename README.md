# Machine Learning

## Description
Teman Tani is an android-based application that can recognize 5 kinds of diseases on rice leaves using machine learning, namely Leaf Blast, Brown Spot, Hispa, Tungro, and Blight. After detecting the disease, the application will provide appropriate pesticide recommendations.

## Rice plant disease detection system
We use MobileNet V2 for pretrained model. <br/>
MobileNet V2 model developed at Google. This is pre-trained on the ImageNet dataset, a large dataset consisting of 1.4M images and 1000 classes. ImageNet is a research training dataset with a wide variety of categories like jackfruit and syringe. This base of knowledge will help us classify rice leaf disease from our specific dataset.

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
* Build Content-based recomendation system in [here](https://www.kdnuggets.com/2020/07/building-content-based-book-recommendation-engine.html)
