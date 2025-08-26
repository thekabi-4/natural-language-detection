Natural Language Detection using Scikit-learn

Detect the language of input text using Scikit-learn and machine learning classifiers.

📌 Description

This project implements a Natural Language Detection model in Python using Scikit-learn. The notebook (LD.ipynb) demonstrates data preprocessing, TF-IDF vectorization, and training ML classifiers (Naive Bayes, Logistic Regression, SVM) to identify the language of given text.

🚀 Features

Implemented in a Jupyter Notebook (LD.ipynb)

Preprocessing of multilingual text

Feature extraction with TF-IDF

Language classification with ML algorithms

Performance evaluation with accuracy, precision, recall, F1-score

⚙️ Installation

Clone this repository and install required libraries:

git clone https://github.com/your-username/natural-language-detection.git
cd natural-language-detection
pip install -r requirements.txt

📖 Usage

Open the notebook in Jupyter:

jupyter notebook LD.ipynb

Run all cells to train and evaluate the model.

Test the model by entering your own text in the prediction cell.

🌐 Run Streamlit App

streamlit run app.py

📊 Example Output

Input: "Hola, ¿cómo estás?"
Predicted Language: Spanish


🧰 Tech Stack

Python 3.x

Scikit-learn

Pandas, NumPy

NLTK (for preprocessing)

📈 Future Improvements

Add deep learning models (e.g., LSTM, Transformers)

Extend support for more languages

Create a Flask/FastAPI web service for live detection

🤝 Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

📜 License

This project is licensed under the MIT License.