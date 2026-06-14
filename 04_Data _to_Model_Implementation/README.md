# Machine Learning

Machine learning enables systems to learn patterns from data and make predictions or decisions without being explicitly programmed. This phase covers classical ML — the algorithms that still power most production systems today.

---

## Learning Steps

### 1. Supervised Learning

- **Regression:** Linear Regression, Ridge, Lasso, Elastic Net
- **Classification:** Logistic Regression, Decision Trees, Random Forest, SVM, k-NN
- **Ensemble Methods:** Gradient Boosting, XGBoost, LightGBM, AdaBoost
- Feature engineering, selection, and importance

### 2. Unsupervised Learning

- **Clustering:** k-Means, DBSCAN, Hierarchical Clustering
- **Dimensionality Reduction:** PCA, t-SNE, UMAP
- **Anomaly Detection:** Isolation Forest, LOF

### 3. Model Evaluation

- Train / validation / test split, cross-validation (k-fold, stratified k-fold)
- Classification metrics: Accuracy, Precision, Recall, F1, ROC-AUC, Confusion Matrix
- Regression metrics: MAE, RMSE, R²
- Bias-variance tradeoff, overfitting vs underfitting, regularization (L1/L2)

### 4. Pipelines & Production

- Scikit-learn Pipelines: preprocessing + model in one object
- Hyperparameter tuning: GridSearchCV, RandomizedSearchCV, Optuna
- Model serialization: joblib, pickle
- MLflow for experiment tracking and model registry

---

## Tools & Libraries

| Tool | Purpose |
|------|---------|
| **Scikit-learn** | The standard ML library — regression, classification, clustering, evaluation metrics, pipelines |
| **XGBoost** | Gradient boosting for tabular prediction — demand forecasting, business ML, competitions |
| **LightGBM** | Fast gradient boosting for large datasets |
| **Pandas + NumPy** | Feature engineering and data preparation |
| **MLflow** | Experiment tracking, model registry, deployment |
| **DVC** | Data version control alongside Git |
| **Weights & Biases** | Experiment visualization and hyperparameter sweeps |
| **Optuna** | Hyperparameter optimization framework |

---
## Learning Sources

### O'reilly

- Beginner: [Introduction to Machine Learning with Python](https://drive.google.com/file/d/1tNK2V7OUcfQBKv1_U-mMSFYUyePpROHm/view?usp=drivesdk)
- Intermediate: [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 3rd Ed.](https://drive.google.com/file/d/1MD34rI4JZNVHqir3Kpl0RUBjx53_oi8s/view?usp=drivesdk)
- Intermediate–Advanced: [Designing Machine Learning Systems](https://drive.google.com/file/d/1DtVOYvfhLmiQJO1NmxAyI_ZC51guuJeZ/view?usp=drivesdk)
- Advanced / production: [Machine Learning Production Systems](https://learning.oreilly.com/library/view/machine-learning-production/9781098156008/)
- Advanced system design: [Machine Learning System Design](https://learning.oreilly.com/videos/machine-learning-system/9781633438750VE/)

### Academic Sheet

- [Machine Learning Basics](./MachineLearningBasics.pdf)
- [Intro to ML](./MachineLearningSheet1.pdf)
- [Data Cleansing](MachineLearningSheet2.pdf)
- [KNN Algorithm Basics](./KNNAlgorithm.pdf)
- [KNN Algorithm Full](./MachineLearningSheet3.pdf)
- [Training set, Classes and  Classifier](./MachineLearningSheet4.pdf)
- [Clustering](./MachineLearningSheet5.pdf)
- [Confusion Matrix](./MachineLearningSheet6.pdf)
- [Covariance and Corelation](./MachineLearningSheet7.pdf)

### Cheat Sheet

* [Machine Learning Cheat Sheet](./ML+Cheat+Sheet_2.pdf)
* [Scikit-Learn Cheat Sheet](./Scikit-Learn_Cheat_Sheet.pdf)
* [Supervised Machine Learning Models](./Supervised_Machine_Learning_Models.pdf)
* [Unsupervised Machine Learning Models](./Unsupervised_Machine_Learning_Models.pdf)

### Other Sources

- [Kaggle: Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning)
- [Kaggle: Intermediate Machine Learning](https://www.kaggle.com/learn/intermediate-machine-learning)
- [ML RoadMap Bangla](https://www.youtube.com/playlist?list=PLKdU0fuY4OFfWY36nDJDlI26jXwInSm8f)
- [Scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
- [XGBoost Documentation](https://xgboost.readthedocs.io/)
- [Hands-On ML with Scikit-Learn, Keras & TensorFlow — Aurélien Géron](https://github.com/ageron/handson-ml3)
- [ML Lifecycle from Data Ingestion to Model Deployment (Snowflake)](https://www.snowflake.com/en/developers/guides/first-machine-learning-project/)

------

## Tabular ML Projects

**How to Start a Machine Learning Project?**
![**How to Start a Machine Learning Project?**](Machine_Learning_Project_Start.png)

Minimum proof:

- train/validation/test split
- baseline model and improved model
- metric comparison
- feature engineering notes
- confusion matrix or regression-error analysis

Strong evidence:

- experiment tracking
- inference script or small API
- business interpretation of results

### pre-Developing Projects

[Here is the 33 projects list ](https://www.datacamp.com/blog/machine-learning-projects-for-all-levels)

### Developing Projects

1. 
2. 
3. 
4. 
5. 

------
------
# Machine and Computer Vision

Computer vision gives machines the ability to interpret and understand the visual world. It is one of the most impactful application areas of modern AI and the **primary perception layer for Physical AI and Robotics**.

**Application domains:**
- Image classification, object recognition
- Medical imaging and diagnostics
- Manufacturing inspection and quality control
- Surveillance, tracking, and smart cameras
- Autonomous vehicles and mobile robots
- Retail analytics and smart devices
- Edge AI systems

---

## Tools & Libraries

| Tool | Description |
|------|-------------|
| **OpenCV** | Industry-standard CV library — preprocessing, segmentation, HSV masking, contours, morphology, pipelines |
| **YOLO (Ultralytics)** | Real-time object detection system — identifies and locates multiple objects in a single neural network pass, optimized for speed |
| **MediaPipe** | Google's cross-platform ML framework for multimodal pipelines (video, audio, sensors) — real-time perception on mobile, web, and edge devices |
| **Detectron2** | Meta AI (FAIR) high-performance library — object detection, instance segmentation, panoptic segmentation (PyTorch-based) |
| **PyTorch + torchvision** | Deep learning backbone for custom vision models and transfer learning |
| **Albumentations** | Fast image augmentation library for training robust vision models |
| **Open3D** | 3D point cloud processing — used for depth cameras and LiDAR in robotics |
| **SAM (Segment Anything)** | Foundation model for zero-shot image segmentation (Meta AI) |
| **CLIP** | Vision-language model — connect images and text (OpenAI) |

---

## Learning Steps

### Classical Computer Vision (OpenCV)

- Image preprocessing: resize, crop, normalize, color space conversion
- Edge detection: Canny, Sobel, Laplacian
- Thresholding and contours
- Morphological operations: erosion, dilation, opening, closing
- Motion detection and optical flow
- Feature extraction: SIFT, ORB, HOG

### Deep Learning for Vision (PyTorch)

- CNN architectures: LeNet → ResNet → EfficientNet → ViT
- Image classification with transfer learning
- Object detection: YOLO family, Faster R-CNN, SSD
- Segmentation: Semantic (FCN, DeepLab), Instance (Mask R-CNN), Panoptic
- Video analysis: tracking, temporal models

### Edge AI & Robotics Vision

- Real-time inference pipelines — optimize for FPS on edge hardware
- Depth estimation: monocular and stereo
- Multi-camera systems and calibration
- 3D point cloud processing (Open3D, PCL)
- Foundation vision models: SAM, CLIP, DINO

### Vision Evaluation

- Classification: Accuracy, Top-5 Accuracy
- Detection: mAP (mean Average Precision), IoU
- Segmentation: Dice coefficient, pixel accuracy
- Profiling: inference time (ms), FPS, model size (MB), FLOPS

---

## Real-World Task Categories

### Computer Vision Engineering

- Image preprocessing and annotation quality
- Model selection by task (classification vs detection vs segmentation)
- Evaluation metrics appropriate to the task
- Inference speed and memory constraints
- Deployment environment awareness

### Robotics, Autonomous Systems, and Edge AI

- Perception pipelines with real-time inference
- Camera and sensor integration (RGB, depth, stereo, thermal)
- Efficient vision models for latency-constrained environments
- Safety-critical thinking for autonomous systems

### Applied AI Products

- Retail analytics (product recognition, shelf monitoring)
- Manufacturing QA (defect detection, surface inspection)
- Healthcare imaging (anomaly detection, segmentation)
- Document vision (OCR, layout parsing)
- Smart devices (gesture recognition, face detection)
- Multimodal systems (vision + language)
------

## Learning Resources

## O'Reilly Resources

* Beginner: [Programming Computer Vision with Python]()
* Beginner–Intermediate: [Learning OpenCV 5 Computer Vision with Python]()
* Intermediate: [Modern Computer Vision with PyTorch, 2nd Ed.]()
* Intermediate–Advanced: [Deep Learning for Computer Vision]()
* Project-focused OpenCV: [Computer Vision Projects with Python]()

### Academic Sheet

- [Intro to Computer Vision](ComputerVisionSheet1.pdf)
- [CV_BasicOperations_Code](CV_BasicOperations_Code.pdf)
-[HighLowPassFiltering_Code](HighLowPassFiltering_Code.pdf)
- [Fourier Transform](ComputerVisionSheet2.pdf)
- [Image Segmentation](ComputerVisionSheet3.pdf)
- [ Image Edge](ComputerVisionSheet4.pdf)
- [Back propagation and Epoch](ComputerVisionSheet5.pdf)
- [MINST Datebse](./MNISTDatabase_Code.pdf)

### Other Sources

* [fast.ai Practical Deep Learning for Coders](https://course.fast.ai/)
* [Kaggle Learn: Computer Vision](https://www.kaggle.com/learn/computer-vision)
* [DataCamp Computer Vision Courses](https://www.datacamp.com/courses-all?technology=Computer+Vision)

------
## Computer Vision Project

Minimum proof:

- dataset description
- training or fine-tuning workflow
- measurable evaluation
- qualitative failure-case review

Strong evidence:

- edge or optimized inference
- comparison between two model approaches
- deployment notes

### pre-Developing
1. 
2. 
3. 

### Developing

1. 
2. 
3. 
------
# Deep Learning and NLP

Deep learning uses multi-layer neural networks to learn complex patterns directly from raw data. It powers modern computer vision, NLP, and physical AI systems. **PyTorch is the primary framework** — preferred for research, robotics, and edge AI.
------

## Learning Steps

### 1. Neural Network Fundamentals

- Neurons, layers, activation functions: ReLU, Sigmoid, Softmax, Tanh
- Forward pass, loss functions (Cross-Entropy, MSE), backpropagation
- Optimizers: SGD, Adam, RMSprop — learning rate intuition
- Vanishing and exploding gradients — BatchNorm, gradient clipping

### 2. PyTorch Core

- Tensors, autograd, computational graphs
- Building models with `nn.Module`
- Training loops, DataLoaders, data augmentation
- GPU training (`.cuda()`), model saving/loading (`state_dict`)

### 3. Convolutional Neural Networks (CNNs)

- Convolution, pooling, receptive fields
- Architectures: LeNet → AlexNet → VGG → ResNet → EfficientNet
- Transfer learning: fine-tuning pre-trained models from `torchvision`
- Applications: image classification, feature extraction

### 4. Recurrent Neural Networks (RNNs)

- Sequence modeling: vanilla RNN, LSTM, GRU
- Vanishing gradient in RNNs — why LSTMs solve it
- Applications: time-series, sensor data from robots, text sequences
- Encoder-Decoder, seq2seq architecture

### 5. Regularization & Optimization

- Dropout, weight decay, batch normalization, layer normalization
- Learning rate schedules: cosine decay, warmup, ReduceLROnPlateau
- Mixed precision training (AMP) for GPU efficiency

### 6. Model Deployment & Edge AI

- ONNX: export PyTorch models for cross-platform inference
- TorchScript: production-ready, serialized PyTorch models
- TensorRT: NVIDIA GPU-optimized inference (critical for Jetson in robotics)
- ONNX Runtime: cross-platform model inference
- Benchmarking: latency, throughput, memory profiling

---

## Frameworks & Tools

| Tool | Purpose |
|------|---------|
| **PyTorch** | Primary framework — custom models, edge AI, real-time inference, research |
| **TensorFlow** | Production-grade training and deploying scalable models |
| **Keras** | High-level API on top of TensorFlow — rapid prototyping |
| **torchvision** | Pre-trained vision models, transforms, datasets |
| **torchaudio** | Audio processing and feature extraction for PyTorch |
| **ONNX Runtime** | Cross-platform model inference — export from PyTorch/TF |
| **TensorRT** | NVIDIA GPU-optimized inference engine — used on Jetson for robotics edge AI |
| **OpenVINO** | Intel hardware inference optimization |

---

## Learning Resources

### Academic Sheet

* [Neural Network Basics](./Neural_Networks_Basics.pdf)
* [Convolutional Neural Network](./CNN.pdf)
* [Recurrent Neural Network](./RNN.pdf)
* [Convex and Non-Convex Function / Optimization using Gradient Descent](./Optimization_using_Gradient_Descent.pdf)
* [Calculus for Artificial Intelligence / Backpropagation](./Backpropagation.pdf)
* [Vanishing and Exploding Gradients Problem](./Vanishing_and_Exploding_Gradients_Problem.pdf)
* [Deep Learning From Scratch](./Deep_Learning_From_Scratch.pdf)
* [Deep Learning with PyTorch](./Deep_Learning_with_PyTorch_1.pdf)
* [Keras Cheat Sheet](./Keras_Cheat_Sheet_gssmi8.pdf)

### Other Sources

- [90 Days Deep Learning (Bangla)](https://www.youtube.com/playlist?list=PLKdU0fuY4OFdFUCFcUp-7VD4bLXr50hgb)
- [PyTorch Official Tutorials](https://pytorch.org/tutorials/)
- [fast.ai Practical Deep Learning for Coders](https://course.fast.ai/)
- [Deep Learning Specialization — Andrew Ng (Coursera)](https://www.deeplearning.ai/courses/deep-learning-specialization/)

------

# Natural Language Processing

NLP enables machines to understand, process, and generate human language. It underpins search engines, chatbots, document AI, summarization, sentiment analysis, and the LLM systems covered in section 09.

## Learning Steps

### 1. Text Preprocessing

- Tokenization, stopword removal, stemming, lemmatization
- Regular expressions for text cleaning
- Text normalization and encoding

### 2. Classical NLP

- Bag of Words (BoW), TF-IDF
- N-grams, feature extraction
- Named Entity Recognition (NER)
- Part-of-Speech (POS) tagging, dependency parsing

### 3. Word Embeddings

- Word2Vec, GloVe, FastText
- Understanding semantic similarity and vector space

### 4. Sequence Models

- RNNs, LSTMs, GRUs for text (see section 05)
- Encoder-Decoder architecture, seq2seq, attention mechanism

### 5. Transformers & BERT

- Transformer architecture (self-attention, multi-head attention)
- BERT, RoBERTa, DistilBERT — fine-tuning for classification/NER
- Hugging Face `transformers` library

### 6. Large Language Models (LLMs)

- GPT family, instruction tuning, RLHF
- Prompt engineering, few-shot, zero-shot
- Connects directly to section 09 (ICT Automation / AI Engineering)

### 7. Applied NLP Tasks

- Text classification, sentiment analysis
- Question answering, summarization
- Information extraction, document understanding
- Semantic search with vector databases

---

## Libraries & Tools

| Tool | Use Case |
|------|----------|
| spaCy | Industrial-strength NLP pipeline |
| NLTK | Classic NLP, tokenization, corpora |
| Hugging Face Transformers | Pre-trained models, fine-tuning |
| Hugging Face Datasets | NLP benchmark datasets |
| Gensim | Word embeddings, topic modeling (LDA) |
| TextBlob | Lightweight sentiment and parsing |
| LangChain / LlamaIndex | LLM orchestration (see section 09) |

---

## Learning Resources

### Cheat Sheet

* [spaCy Cheat Sheet](./spaCy_Cheat_Sheet_final.pdf)

### Other Sources

- [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course/chapter1/1) — best free NLP course
- [fast.ai NLP](https://www.fast.ai/)
- [Stanford CS224N: NLP with Deep Learning](https://web.stanford.edu/class/cs224n/)
- [Kaggle: Natural Language Processing](https://www.kaggle.com/learn/natural-language-processing)

-----