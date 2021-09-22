# 💡 DataMining 

## 00. Data 

### 1) Types of Attributes

- categorical
- numerical

### 2) Types of DataSets

- Record Data 
- Graph-Based Data
- Ordered Data

### 3) Data Quality

- Data Preprocessing 
  - Aggregation 
  - Sampling 
  - Dimensionality Reduction 
  - Feature Selection 
  - Feature Weighting 
  - Feature Creation 
  - Discretization and Binarization 
  - Variable Transformation 

### 4) Measure of Similarity 

- Minkoswki Distance (거리)
  - Manhattan 
  - Euclidean 
  - Supremum
- Similarity Coefficients (똑같은 정도)
  - Simple matching 
  - Jaccard 
- Cosine Similarity (코사인 유사도)
- Correlation 

### 5) Issues in Proximity Calculation

- Standardization 
- Using weights 



## 01. Classification 

### 1-0. Evaluation Metrics 

- Confusion matrix 

### 1-1. General Issues of Classification Models 

- Model Overfitting 
  - limited training size 
  - high model complexity 
- Model Selection 
  - Using Validation Sets 
  - Pre-Pruning 
  - Post-Pruning 
- Model Evaluation 
  - Holdout Method
  - Cross-Validation (k-Fold Cross Validation)
- Presence of Hyper-Parameters
  - Simple approach 
  - Cross-validation approach 

### 1-2. Decision Tree Classifier 

- Structure 
- Hunt's Algorithm 
  - Start with a single root node 
  - Splitting criterion
  - Stopping criterion 
- Attribute Test Conditions 
  - binary
  - nominal
  - ordinal
  - continuous 
- Selecting an Attribute Test Condition 
  - Impurity 
    - Entropy
    - Gini index 
    - Classification Error 
  - Collective Impurity 
- Finding the best attribute test condition 
  - Information gain 
- Binary Splitting of Quantitative Attribute 
- Characteristics of Decision Tree Classifiers 
  - Applicability 
  - Expressiveness 
  - Computational efficiency 
  - Handling missing values 
  - Handling irrelevant attributes 
  - Handling redundant attributes 
  - Choice of impurity measure 
  - Using rectilinear splits 



