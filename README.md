# Glossary

Here, we collect definitions of important concepts

**Ablation**: A technique for evaluating the importance of a feature or component by temporarily removing it from a model. Can also be used to determine the importance of a subsystem of a larger model. 

**Activation Function**: A user-implemented function that provides a nonlinear learning aspect of an algorithm between inputs and outputs.

**Auto-Encoders**: neural networks that learn to efficiently compress and encode data then learn to reconstruct the data back from the reduced encoded representation to a representation that is as close to the original input as possible.

**Auto-encoders:** Neural networks that can efficiently compress and encode data, and then use that encoding to reconstruct the original data as accurately as possible, which can reduce the input data dimensionality. 

**Batch Normalization**: In deep learning, each step (or batch) of model training must be normalized to have zero mean and unit variance. This prevents numerically large features from dominating the training process.

**Benchmark Dataset**: A dataset or data archive which is used to train the algorithm in machine learning.

**Bias-Variance Tradeoff**: It implies that as we increase the complexity of a model, its variance decreases, and its bias increases. Conversely, as we decrease the model's complexity, its variance increases, but its bias decreases.

**Big O notation**: A mathematical concept used in computer science to describe the performance or complexity of an algorithm's runtime or memory usage as the input size (denoted as n) becomes large

**Black box**: The inability to undestand how a deep learning system makes its decisions.

**Bootstrapping**: Bootstrapping is a resampling technique in statistics where multiple random samples are drawn with replacement from a single dataset. This method is employed to estimate the sampling distribution of a statistic and assess its variability.

**Clustering**: An unsupervised ML method that groups unlabelled data together by finding how similar/different different pieces of data are to each other. 

**Contrastive Learning**: A deep learning technique where similar patterns detected in the data are pushed close together in a representation space, while dissimilar patterns are pushed far apart.

**Convolutional Neural Network:** a deep learning algorithm that takes an input image and assigns weights to be able to diferrentiate other images from each other.  

**Core:** a processing unit of a CPU or GPU that performs the tasks.

**Cross-Validation:** This involves splitting of your data into smaller groups to train and test your model. It helps check how well your model works on different data and prevents it from overfitting.

**Data Augmentation**: Data augmentation is the process of generating new, artifical data from existing data. This is commonly used to increase the size of a training dataset in ML (ie. rotating input images in a data segmentation pipeline)

**Data dimensionality**: Dimensionality of data refers to the number of properties or categories in a dataset.

**Data Mining:** Analyzing raw data to extract useful information and find patterns.

**Data modality:** The simplest structure in which your data can be described (e.g., row-column, multi-dimensional, raster/image). 

**Decision Trees**: supervised learning that is used in statistics and machine learning that can do different "tasks" such as classification trees or regression trees, however they can sometimes be too broad when determining what fits their qualifications. 

**Deep Learning**: neural networks with multiple layers, allowing complex patterns and representations to be learned from large datasets.

**Deep Learning:** A subfield in machine learning based on artificial neural networks in which multiple layers of processing are used to extract progressively higher level features from data.

**Dimensionality Reduction:** A data transformation technique where high-dimensionality data is converted to lower-dimensionality data while preserving as much meaningful structure in the data as possible to address the curse of dimensionality and improve data visualization, interpretation, clustering, and other processing (ex. machine learning). 

![image](https://github.com/UW-ESS-DS/Glossary/assets/56406566/7477fad4-895e-4a42-97b6-40b3bcc2bf0a)

**Dropout**: The process of randomly setting a fraction of input units in a neural network to zero to prevent overfitting by breaking up situations where network layers co-adapt to correct mistakes in prior layers. This increases the neural network's ability to generalize to new data.

**Feature Engineering:** Manipulating raw data to select specific features from within the data.  Also referred to as feature extraction or feature discovery.  A feature, sometimes used interchangably with the term variable, can be a characteristic, property, attribute, etc. within the raw data.

**Features**: A 'feature' is any attribute of a dataset that represents (tangible or intangible) information about it. The term can be used broadly whereever relational properties about the dataset are relevant or represented as values, series, matrices, etc.. As such, a feature could be a single datapoint, a measurement series, a statistical property of the data (or a subset thereof), a pattern in the data represented by a 'filter,' a weight or bias, etc. In linear algebra terms, a feature is representable as a dimension of a subspace of the vector space of the data.

**Fuzzy Logic** : A logic system often used in machine learning, where results can be on a spectrum from correct or wrong, rather than entirely one or the other. Fuzzy Logic is particularly well-suited for use with noisy data.

**Gradient Boosting**: A machine learning technique used for regression and classification tasks that builds an ensemble of weak learners, typically decision trees, where each new model corrects the errors of the previous ones in an iterative manner.

**Gradient Descent**: An optimization algorithm used to minimize the loss function in machine learning models by iteratively adjusting the model parameters in the direction of the steepest descent of the loss function.

**Hyperparameters:** Common in Bayesian statistics, they are values to control the learning process and the outcome values of the machine learning training algorithm.

**Inference**: when a trained model is used to infer (predict) values using live data

**Instance:** refers to a computing unit, like a node. Terminology used in Cloud.

**K Means Clustering** A machine learning algorithm for grouping variables that partitions the signals of interest by their behavior/patterns. This is an example of an unsupervised machine learning model. 

**Kernel methods**: ML algorithms that use functions called kernels to project data into higher dimensional space. They are especially useful for pattern analysis of data that is not linearly separable. 

**Linear Regression**: A type of supervised learning algorithm that optimizes a linear function to data points. 

**Local model interpretation:** set of techniques aimed at evaluating why a model makes a specific prediction and what effect a specific feature value has on the prediction.

**Logistic Regression:** A statistical model used for classification given a dataset. Provides a discrete output.

**Neural network**: Is a computational model that mimics how the human brain works, using layers of connected nodes (or neurons) to learn from data and perform tasks like recognizing patterns and making predictions.

**Node:** refers to computing unit a single CPU with multiple cores, a dedicated memory, and a dedicated storage. Terminology used in high performance computing (HPC).

**Noise:** In the collected data noise is anything that is unwanted or adds difficulty for the model to interpret within said data.

**Overfitting:** It occurs when a model learns to perform exceptionally well on the training data but struggles to generalize its performance to new, unseen data.

**Physics-Informed Neural Networks**: Training of a neural network that is physis-agnostic at initial design, but constraining the predictions to obey physical law by crafting the loss function accordingly.

**Random forest**: A machine learning algorithm for classification, regression and other tasks that operates by constructing a multitude of decision trees (during training) to generate a single result.

**Random Forest**: an ensemble ML algorithm that combines multiple decision trees to create a more robust and accurate model for both classification and regression tasks.

**Random Forest**: a machine learning algorithm that combines the output of multiple decision trees into a single result.

**Regression Analysis**: Statistical processes for estimating the relationships between a dependent variable and one or more independent variables.

**Regularization**: techniques that help prevent overfitting in machine learning models by adding a penalty for complexity, ensuring better generalization to unseen data.

**Resampling:** The process of repeatedly generating new samples from training data in order to understand uncrertenties in the data being used.

**Signal** The part of the data you want to study/explore. Datasets must sometimes be denoised in order to pull out what you want.

**Structured Data**: data organized in a specific format, such as position (lat, long) information or physical measurements.

**Supervised Learning** a type of machine learning where a model is trained on labeled data, meaning the input data is paired with the correct output, and the model learns to make predictions or classify new, unseen data based on this training.

**Synthetic Data**: Data often used for training a model, generated by a computer and made to resemble real-world datasets. They can be helpful for creating data in cases where data is sparse.

**Training**:  It is important to train models using appropriate and enough data otherwise the results may be questionabe.

**Underfitting:** Occurs when a machine learning model is too simple to capture the underlying patterns in the training data, resulting in poor performance on both the training and testing data.

**Unstructured Data**: data that are not organized in a specific format and require more complex methods for automated interpretation. Examples include images, papers, books, audio files etc.
**Unsupervised Learning**: a category of machine learning where models are trained using unlabeled data to make connections between that data.
