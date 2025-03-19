# AnswerAI

Description

This chatbot is designed to efficiently resolve human queries using machine learning techniques. It utilizes TF-IDF Vectorization for feature extraction and an SVM (Support Vector Machine) classifier for response prediction. The model can handle various customer-related questions and deliver accurate responses.

Features

✅ Provides quick and accurate responses to customer queries✅ Utilizes machine learning for improved accuracy✅ Simple yet effective code structure for easy modifications✅ Easy integration into web or desktop applications

Technologies Used

Python

Pandas

NumPy

Scikit-learn

Google Colab (For development)

Installation

To run this chatbot locally, follow these steps:

Clone the Repository

git clone https://github.com/YourGitHubUsername/AnswerAI.git
cd AnswerAI

Install Dependencies

pip install -r requirements.txt

Run the Code

python chatbot.py

Usage

After running the code, you'll be prompted to enter your query.

Enter a question such as:

User: How do I return a product?

The chatbot will respond with the appropriate answer.

Bot: You can return within 30 days.

Troubleshooting

🔹 ModuleNotFoundError for pandas, numpy, or sklearn: Run pip install -r requirements.txt again to ensure all dependencies are correctly installed.🔹 Incorrect responses or errors in prediction: Ensure your data structure in the dataset is consistent and the model is trained correctly.🔹 git authentication errors during push: Use a personal access token instead of a password for GitHub authentication.

If you encounter additional issues, feel free to raise an issue in the repository.
