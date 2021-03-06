# spampy

**Documentation**: <a href="https://spampy.abdullahselek.com" target="_blank">https://spampy.abdullahselek.com</a>

**Source Code**: <a href="https://github.com/abdullahselek/spampy" target="_blank">https://github.com/abdullahselek/spampy</a>


Spam filtering module with Machine Learning using SVM. **spampy** is a classifier that uses ``Support Vector Machines``
which tries to classify given raw emails if they are spam or not.

Support vector machines (SVMs) are supervised learning models with associated learning algorithms that analyze data used
for classification and regression analysis. Given a set of training examples, each marked as belonging to one or the other
of two categories, an SVM training algorithm builds a model that assigns new examples to one category or the other, making
it a non-probabilistic binary linear classifier.

Many email services today provide spam filters that are able to classify emails into spam and non-spam email with high accuracy.
**spampy** is a learning project that you can use filtering spam mails.

**spampy** uses two different datasets for classification. One of the datasets is already imported inside the project under ``spampy/datasets/`` folder. Second dataset is <a href="http://www.aueb.gr/users/ion/data/enron-spam/">enron-spam</a> dataset and inside the ``spampy`` folder I created a shell script which downloads and extract it for you.
