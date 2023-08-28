# MultiTaskClassifier

In this project, instead of training three separate models for classifying cars’ color, producer, and usage type, a single EfficientNet model is used as the base model. Then, it is fine-tuned so that it is able to do all three classification jobs at the same time. In fact, the feature extraction section of the model is the same for all of the tasks but in the last fully connected layer (output layer), the model is trained to do the three jobs.
