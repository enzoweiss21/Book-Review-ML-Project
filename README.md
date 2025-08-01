📚 Book Review Sentiment Classification
🔍 Project Overview
This project applies machine learning techniques to classify book reviews as either positive or negative. It demonstrates the full ML lifecycle—from data preparation to model evaluation—using a real-world dataset of textual reviews.

🎯 Objectives and Goals
Understand and implement the end-to-end machine learning pipeline

Train a classification model that predicts review sentiment

Apply NLP preprocessing techniques to improve model accuracy

Evaluate and interpret model performance through metrics and visualization

🧠 Methodology
Dataset: bookReviewsData.csv containing 1,973 labeled book reviews

Task: Binary classification (Positive Review: True/False)

Techniques Used:

Text preprocessing (tokenization, vectorization)

Train-test split

Logistic Regression and other classifiers

Accuracy, Precision, Recall, and F1-score for evaluation

📊 Results & Key Findings
The logistic regression model achieved strong baseline accuracy on test data

Performance was improved through vectorization and hyperparameter tuning

Key indicators of sentiment were visualized via most influential words

📈 Visualizations
The notebook includes:

Word frequency distribution

Confusion matrix

Precision/recall/F1-score tables

Optional model comparison plots

🚀 Getting Started

🔧 Installation & Setup

Clone this repository:

git clone https://github.com/enzoweiss21/Book-Review-ML-Project.git
cd Book-Review-ML-Project

Create a virtual environment and install dependencies:


python3 -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt

📁 Files Included
DefineAndSolveMLProblem.ipynb – Jupyter notebook with complete workflow

bookReviewsData.csv – Dataset of reviews and labels

README.md – Project overview and instructions

🧪 Run the Project
✅ To train and evaluate the model:
Open the notebook:

bash
Copy
Edit
jupyter notebook DefineAndSolveMLProblem.ipynb
Run each cell in order to:

Load the dataset

Preprocess the text

Train the model

Evaluate results

Visualize performance

🔄 Potential Next Steps
Apply deep learning (e.g., LSTM or BERT) for improved sentiment detection

Expand the dataset to include neutral sentiment or ratings

Deploy as a web app using Flask or Streamlit

👥 Individual Contributions
Enzo Weiss – Data selection, model design, implementation, evaluation, and reporting

📘 Documentation
This project includes:

Inline documentation within the notebook

Code comments for clarity

Step-by-step execution flow from raw data to results

