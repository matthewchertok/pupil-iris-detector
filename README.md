# pupil-iris-detector

Contains a dataset of eye images that I prepared in order to fine-tune a Faster-RCNN/ResNet50 model to estimate the width of the pupil and iris in pixels.
Also contains a model that I trained on this dataset.

The labeled_eye_data_train folder contains labeled images used for training the model.
The labeled_eye_data_validation folder contains labeled images used during the validation phase of training (after each epoch).
The L1 folder contains unlabeled images used for testing the model. These images are not used during training.
