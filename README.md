# Apparel-Recommendation
Recommends similar apparel products using content-based recommendation approach.

## Required Data-set Files 
1) tops_fashion.json
2) word2vec_model
- https://drive.google.com/open?id=1VAzVjLjJzWz2PYHjaoR60dhSXAtVHsoY
<br/>

- ##### Pre-processed Amazon dataset of 183k products with 19 features to 28k products & used it to build a model.

- ##### Implemented Word2Vec & TF-IDF to find similar products and enhanced recommendation results by integrating module to find similar products by images using VGG16 CNN model.

## Data Set Overview
- Number of data points :  183138 (approx. 183k)
- Number of features/variables: 19
- Data attributes <br />
  a) ASIN - Amazon standard identification number <br />
  b) Author <br />
  c) Availability<br />
  d) Availability_type<br />
  e) Brand<br />
  f) Color<br />
  g) Editorial_reivew<br />
  h) Title<br />
  i) Formatted_price<br />
  j) Large_image_url<br />
  k) Manufacturer<br />
  l) Medium_image_url<br />
  m) Model<br />
  n) Product_type_name<br /> 
  o) Publisher<br />
  p) Reviews<br />
  r) Sku<br />
  s) Small_image_url<br />
  t) reviews<br />

### Approaches for Recommendation 
<br/>

- Text Based Similarity 
  - Bag Of Word 
  - TF-IDF 
  - IDF
 
- word2vec
- Image features based product similarity


### Recommendation Result 
<br/>

-  Products similar to currently viewed product "Burnt umber Tiger tshirt with zebra stripes" 
<br/>

<img src="Capture.JPG"></img>
