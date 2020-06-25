### Product_Review_Keras_Model
### Install Tensorflow == 1.2.0
#### IMDB - review
##### Description:
##### Large Movie Review Dataset. This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well.

##### Homepage: http://ai.stanford.edu/~amaas/data/sentiment/
##### Source code: tfds.text.imdb.IMDBReviews
##### Versions:1.0.0 (default): New split API (https://tensorflow.org/datasets/splits)
##### Download size: 80.23 MiB
##### Dataset size: Unknown size
##### Auto-cached (documentation): No
##### Splits:
##### Split	Examples: 'test'	25,000, 'train'	25,000, 'unsupervised'	50,000, Supervised keys (See as_supervised doc): ('text', 'label')
###### import tensorflow_datasets as tfds

###### ds = tfds.load('imdb_reviews', split='train')
###### for ex in ds.take(4):
######   print(ex)
