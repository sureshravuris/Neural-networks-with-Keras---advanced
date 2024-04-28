# Advanced Deep Learning Techniques with TensorFlow and Keras

This repository contains a series of Jupyter Notebooks designed to illustrate advanced data augmentation, regularization techniques, and custom TensorFlow/Keras constructs. Each technique is implemented to demonstrate how to enhance model performance and generalization across various types of data.

## Assignment Deliverables

### Part 1: Data Augmentation and Regularization Techniques

#### A) TensorFlow Regularizations
- **L1 and L2 Regularizations**: Implementing weight penalties to reduce overfitting.
- **Dropout**: Utilizing dropout layers to randomly deactivate input units.
- **Early Stopping**: Implementing early stopping to halt training when validation performance degrades.
- **Monte Carlo Dropout**: Demonstrating predictive uncertainty with Monte Carlo Dropout.
- **Various Initializations**: Exploring different weight initialization strategies and their impacts.
- **Batch Normalization**: Integrating batch normalization to standardize inputs to a layer.
- **Custom Dropout and Regularization**: Creating custom dropout and regularization methods.

#### B) Keras Data Augmentation
- **Keras CV for Data Augmentation**: Using Keras CV to apply image data augmentation techniques.

#### C) Data Augmentation for Various Data Types
- **Image, Video, and Text**: Implementing augmentation using libraries such as NLPAug.
- **Time Series and Tabular Data**: Augmenting structured data.
- **Speech and Document Images**: Applying augmentation techniques to speech and document images.

#### D) FastAI Data Augmentation Capabilities
- **FastAI Techniques**: Utilizing FastAI to demonstrate easy and effective data augmentation.

### Part 2: Advanced Keras Deep Learning Constructs

#### A) Custom TensorFlow and Keras Constructs
- **Custom Learning Rate Scheduler**: Implementing and using a custom learning rate scheduler.
- **Custom Dropout**: Creating and applying a custom dropout layer.
- **Custom Normalization**: Designing and using custom normalization methods.
- **Custom Loss Function**: Implementing a custom loss function, such as Huber Loss.
- **Custom Activation Functions, Initializers, Regularizers, and Constraints**: Creating and applying custom deep learning components.
- **Custom Metrics**: Designing metrics like a custom version of the Huber metric.
- **Custom Layers and Models**: Building and integrating custom layers and models.
- **Custom Optimizer**: Implementing a custom optimizer.
- **Custom Training Loop**: Designing and executing a custom training loop outside of the `fit` method.

> ### ▶️[Demo Video]()
## References

- TensorFlow Official Tutorials: [TensorFlow](https://www.tensorflow.org/tutorials)
- Hands-On Machine Learning with Scikit-Learn, Keras, TensorFlow(3rd Edition): [GitHub - ageron/handson-ml3](https://github.com/ageron/handson-ml3)
- AugLy by Facebook Research: [AugLy](https://ai.facebook.com/blog/augly-a-new-data-augmentation-library-to-help-build-more-robust-ai-models/)
- Awesome Data Augmentation: [Awesome Data Augmentation](https://brunokrinski.github.io/awesome-data-augmentation/)
- FastAI Book: [FastAI Book](https://github.com/fastai/fastbook)
