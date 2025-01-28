# CNN-Classifier

The purpose of this project was to introduce myself to implementing neural networks using TensorFlow, as well as utilizing plotting libraries like matplotlib to visualize results. It pulls from a dataset from
[Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) that contains 4 classes of brain tumors: meningioma, glicoma, pituitary, and notumor. This is done in cleaning_training.ipynb.
The data is preprocessed in pandas, and converted back to numpy before being putting into the model. There are 2 models: a CNN with 95% accuracy, and a DNN with about 85% accuracy. The goal of the CNN was to
be as accurate as possible. The intention of the DNN was to demonstrate how the CNN architecture was a much better fit. Some further metrics of the CNN model can be found in Results.ipynb.


If the above hyperlink doesn't work, the source of the dataset is here: 

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset
