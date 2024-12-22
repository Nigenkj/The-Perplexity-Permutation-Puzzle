
# Text Unscrambling with Supervised Machine Learning


# Project Overview

This project explores text unscrambling using machine learning techniques, developed as part of my participation in the Santa 2024 Kaggle competition. The task involved transforming scrambled holiday-themed text into its correct form by leveraging both baseline and advanced methods.

# Key Objectives

Develop a baseline approach for unscrambling text.
Implement advanced machine learning techniques for improved accuracy.
Validate predictions using domain knowledge (English word dictionaries).
Methods and Approaches
1. Baseline Model
Heuristic Approach: Letters in each scrambled word were rearranged in alphabetical order to generate a naive unscrambled version.

Advantages: Quick and simple to implement, providing a baseline for comparison with advanced models.

2. Advanced Techniques
a. Data Simulation
A dataset of scrambled and unscrambled word pairs was generated using Python.
Random letter scrambling ensured diversity in training examples.

b. Feature Engineering
TF-IDF Vectorization: Character-level n-grams (bigrams to quadgrams) were used to numerically represent the scrambled text.
This enabled the model to capture patterns in letter arrangements.

c. Machine Learning
Model: Random Forest Classifier trained on the vectorized data to map scrambled text to correct forms.
Why Random Forest?: Robust performance on small datasets and interpretability.

![Screenshot 2024-12-21 211319](https://github.com/user-attachments/assets/72e578d5-c2db-4ab7-b897-029abfe39128)
d. Dictionary Validation
Post-processing step where predictions were matched against a pre-defined English dictionary to ensure valid outputs.

# Results and Outcomes
The advanced model demonstrated significant improvements over the baseline heuristic approach.
![Screenshot 2024-12-21 211304](https://github.com/user-attachments/assets/0a88bc30-c538-4525-a2b6-678d33a5bfd6)

Accurate predictions were achieved for test datasets, showing the effectiveness of combining domain knowledge with machine learning.

![Screenshot 2024-12-21 212001](https://github.com/user-attachments/assets/e5f906df-5276-4bfe-a1d2-f7ae56db5549)

# Technologies and Libraries
Languages: Python
Libraries: pandas and numpy for data manipulation.
nltk for dictionary validation.
sklearn for machine learning (TF-IDF and Random Forest).
random for data simulation.
How to Run the Project

Clone the repository.
Install required dependencies:

![image](https://github.com/user-attachments/assets/f8555fc2-ccad-4150-8468-216f13e499d6)

Import Libraries
![image](https://github.com/user-attachments/assets/6578df97-b900-4e35-8bf7-a4b6018ba596)

Note: Run the main.py script to preprocess data, train the model, and generate predictions.
Explore the notebooks/ directory for detailed steps and experiments.

# Next Steps
Experiment with deep learning models (e.g., LSTMs or Transformers).
Expand the dataset with more complex examples, including multi-word phrases.
Optimize model hyperparameters to further improve accuracy.

# Conclusion
This project highlights the power of combining machine learning with domain knowledge to solve challenging text processing problems. It also underscores the importance of starting with a strong baseline and iteratively refining the solution.



## Badges

Competetor![image](https://github.com/user-attachments/assets/ba4c5c21-32d4-445e-8eaf-012dfe204079)


Python Notebook![image](https://github.com/user-attachments/assets/e4c18d16-7877-49b1-82e5-1e4d14b5cfd9)



## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.kaggle.com/nigelagordorku)


