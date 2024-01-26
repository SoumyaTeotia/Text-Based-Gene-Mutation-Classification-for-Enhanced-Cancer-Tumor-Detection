# Text-Based Gene Mutation Classification
This project aims to develop a robust system for classifying gene mutations based on textual evidence, with the ultimate goal of enhancing cancer tumor detection. By leveraging machine learning and deep learning techniques, including natural language processing (NLP), the system automates the classification process, reducing reliance on manual methods that are time-consuming and prone to errors.

**Key Components:**
* Dataset: The project utilizes the Kaggle competition dataset "Personalized Medicine: Redefining Cancer Treatment" provided by the Memorial Sloan Kettering Cancer Centre (MSKCC). It includes genetic mutations and corresponding clinical evidence.

* Text Preprocessing: Extensive text preprocessing techniques are applied, including stop words removal, punctuation removal, stemming, and lemmatization, to prepare the textual data for analysis.

* Class Balancing: Addressing class imbalance is crucial for accurate classification. The project employs upsampling techniques to mitigate the effects of class imbalance in the dataset.

* Model Architecture: The classification system is structured in two stages. In the first stage, various machine learning models such as Naive Bayes, K-Nearest Neighbors, Logistic Regression, Stochastic Gradient Descent, and Support Vector Machine are applied to extract features from the textual and genetic data. The second stage involves ensemble methods such as Bagging (using Random Forest) and the Voting Classifier to combine predictions from individual models for final classification.

* Model Training and Hyperparameters: The models undergo rigorous training with hyperparameters tuned using techniques like GridSearchCV. Each model is optimized to achieve the highest accuracy and performance.

**Results and Conclusion:**
The project achieves a classification accuracy of 92.53%, demonstrating the effectiveness of the proposed approach in gene mutation classification. Bagging with a Random Forest classifier emerges as the most reliable classification method, consistently outperforming other alternatives. The study also highlights the importance of addressing class imbalance and potential biases in the model for improved accuracy and reliability.

For detailed insights and comprehensive analysis, refer to the complete report provided in the repository.
