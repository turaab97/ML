Part 1: Credit Risk Prediction (Supervised Learning)
Problem:
Develop a binary classification model to predict whether a loan applicant poses a good or bad credit risk based on demographic, financial, and historical credit data.

What I Did:

Cleaned and preprocessed the dataset, dropping high-cardinality and non-informative fields.

Built a baseline model using a RandomForestClassifier within a scikit-learn pipeline.

Engineered new features to capture behavioral and financial patterns.

Applied feature selection to improve signal-to-noise ratio.

Tuned hyperparameters using GridSearchCV to optimize model performance.

Evaluated the model using F1 score with k-fold cross-validation and held-out test data.

Part 2: Predictive Maintenance Cost Modeling (Supervised Learning + Business Impact)

Problem:
Predict equipment failures in advance to reduce unplanned maintenance costs by replacing reactive repairs with preventative inspections.

What I Did:

Modeled failure prediction using both Random Forest and RNN classifiers.

Extracted confusion matrix metrics (TP, FP, FN, TN) for each model.

Mapped model outcomes to real-world cost categories (e.g., false negatives = high failure cost).

Calculated total costs and cost savings under each model using a detailed cost matrix.

Compared models based on cost efficiency, recall, and business risk trade-offs.

Framed model choice in terms of operational cost vs. risk tolerance.

Part 3: Customer Segmentation via Clustering (Unsupervised Learning)
Problem:
Segment a customer dataset into meaningful groups for the purpose of tailored strategy, improved service offerings, and better targeting.

What I Did:

Performed unsupervised learning using both KMeans and Agglomerative Clustering.

Preprocessed and scaled features for clustering compatibility.

Evaluated clustering quality using silhouette score and interpretability.

Selected the more business-relevant clustering method based on clarity of segmentation.

Interpreted and profiled each cluster to define customer personas.

Developed a customer journey map tied to each segment’s behavior and needs.
