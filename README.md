# Sentiment-Analysis

Introduction to the Project:

The course-end project analyzes sentiments expressed in over 34,000 reviews for Amazon brand products within the e-commerce domain. The dataset contains attributes such as brand, categories, review titles, review text, and sentiment levels categorized into "Positive," "Negative," and "Neutral." The project aims to predict sentiment or satisfaction levels based on various features and review text.

Objectives of the Project:
* Understand the sentiment expressed in consumer reviews.
* Address class imbalance in sentiment categories. 
* Implement classifiers and advanced techniques for sentiment analysis.
* Evaluate model performance using appropriate metrics.
* Compare traditional machine learning algorithms with neural network approaches.
* Explore topic modeling techniques for clustering similar reviews.
  

Project Task: Week 1

Class Imbalance Problem:

Perform an EDA on the dataset.

a) See what a positive, negative, and neutral review looks like.

b) Check the class count for each class. It’s a class imbalance problem.

Convert the reviews in Tf-Idf score.

Run multinomial Naive Bayes classifier. Everything will be classified as positive because of the class imbalance.

Project Task: Week 2

Tackling Class Imbalance Problem:

Oversampling or undersampling can be used to tackle the class imbalance problem.

In case of class imbalance criteria, use the following metrices for evaluating model performance: precision, recall, F1-score, AUC-ROC curve. Use F1-Score as the evaluation criteria for this project.

Use Tree-based classifiers like Random Forest and XGBoost. Note: Tree-based classifiers work on two ideologies namely, Bagging or Boosting and have fine-tuning parameter which takes care of the imbalanced class.

Project Task: Week 3

Model Selection:

Apply multi-class SVM’s and neural nets.

Use possible ensemble techniques like: XGboost + oversampled_multinomial_NB.

Assign a score to the sentence sentiment (engineer a feature called sentiment score). Use this engineered feature in the model and check for improvements. Draw insights on the same.

Project Task: Week 4

Applying LSTM:

Use LSTM for the previous problem (use parameters of LSTM like top-word, embedding-length, Dropout, epochs, number of layers, etc.) Hint: Another variation of LSTM, GRU (Gated Recurrent Units) can be tried as well.

Compare the accuracy of neural nets with traditional ML based algorithms.

Find the best setting of LSTM (Neural Net) and GRU that can best classify the reviews as positive, negative, and neutral. Hint: Use techniques like Grid Search, Cross-Validation and Random Search

Optional Tasks: Week 4

Topic Modelling:

Cluster similar reviews. Note: Some reviews may talk about the device as a gift-option. Other reviews may be about product looks and some may highlight about its battery and performance. Try naming the clusters.

Perform Topic Modelling Hint: Use scikit-learn provided Latent Dirchlette Allocation (LDA) and Non-Negative Matrix Factorization (NMF).
        
Learning Outcomes:

This project gives practical experience in sentiment analysis, classification techniques, and advanced modeling approaches. Understanding of class imbalance handling, model evaluation, and optimization techniques.

Conclusion:

By systematically addressing the class imbalance problem, selecting appropriate classifiers, and exploring advanced modeling techniques, this project aims to develop an accurate and robust sentiment analysis model for e-commerce applications. Insights gained from the project will contribute to the understanding of sentiment analysis methodologies and their applications in real-world scenarios.
