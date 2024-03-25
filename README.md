# Deep-learning-methods

1. `Evaluating_model.ipynb`
The code utilizes `PyTorch` and `torchvision` to download a dataset from OpenImages, preprocesses the data for training, loads a pre-trained model and calculates evaluation metrics such as accuracy, recall, precision, and F1 score for each class based on the model's predictions.
2. This project involves the implementation of an image classification model. Three classes were chosen from OpenImages V6 dataset for selecting classes and divised into training, validation and testing sets, before being preprocessed. An appropriate model architecture was created using `PyTorch`. A training loop was implemented and the model validated against the validation dataset. Finally, the trained model was evaluated on the testing datased using metrics like confusion matrix, accuracy, precision and recall. One can also invoke the model via REST API with Swagger.







