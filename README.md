# OCTMNIST Classification
The task is to classify optical coherence tomography (OCT) images of retinal diseases using a Convolutional Neural Network (CNN) model. The dataset, OCTMNIST, contains 109,309 images labeled into four classes. This project includes data preprocessing, model design, and the application of techniques to prevent overfitting.


## Steps
A series of CNN models were developed to classify OCT images. Techniques such as L2 regularization, dropout, and early stopping were applied to improve generalization and prevent overfitting. The models were trained, validated, and tested, with performance metrics reported.
### Data Preprocessing

- Downloaded OCTMNIST dataset.
- Normalized pixel values to the range [0, 1].
- Split the dataset into training (70%), validation (15%), and test (15%) sets.
### Model Architecture

- Designed CNN models with at least three layers, including convolutional and fully connected layers.
- Applied ReLU activation functions after each layer.
### Techniques to Prevent Overfitting

- Regularization: Applied L2 regularization (weight decay) to the model’s parameters.
- Dropout: Introduced dropout layers between fully connected layers.
- Early Stopping: Monitored validation loss and stopped training when the loss stopped improving.
### Training and Evaluation

- Trained the models on the training set and evaluated performance on the validation and test sets.
- Reported training accuracy, training loss, validation accuracy, validation loss, testing accuracy, and testing loss.
- Generated and analyzed confusion matrices and calculated precision, recall, and F1-score for further performance evaluation.
### Results and Analysis

- Plotted training and validation accuracy over epochs.
- Plotted training and validation loss over epochs.
- Discussed the impact of regularization, dropout, and early stopping on model performance.

## Code

You can find the code for the entire project in the OCT-Image-Classification-CNN.ipynb file.
## Detailed Report

A comprehensive report detailing the model architecture, training process, evaluation metrics, and performance graphs is available in `report.pdf`.

For questions or feedback, please [email](mailto:gayatriwalke@gmail.com).
