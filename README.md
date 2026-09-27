# 💊 Medicine Information Retrieval System

## 📌 Project Overview

The Medicine Information Retrieval System is an Information Retrieval project developed using Python and Natural Language Processing techniques.

The system allows users to enter a disease, disorder, or symptom and retrieves the most relevant medicine information from a medicine dataset.

It uses **TF-IDF (Term Frequency-Inverse Document Frequency)** to represent the text and **Cosine Similarity** to measure the relevance between the user's query and medicine records.

---

## 🎯 Objectives

- Retrieve relevant medicine information based on user queries
- Search medicine records using diseases, disorders, or symptoms
- Rank results according to similarity
- Provide relevant medicine information to the user
- Demonstrate Information Retrieval techniques using Python

---

## 🧠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorization
- Cosine Similarity

---

## 🔍 How the System Works

```text
User enters disease / disorder / symptom
                  ↓
            Text Processing
                  ↓
          TF-IDF Vectorization
                  ↓
          Cosine Similarity
                  ↓
        Similarity Score Ranking
                  ↓
        Top Relevant Results
                  ↓
          Medicine Information
📊 Dataset

The project uses an enhanced medicine dataset containing medicine-related information.

The dataset is used as the knowledge source for retrieving relevant medicine records.

⚙️ Key Features
🔎 Disease and symptom-based search
📚 Medicine information retrieval
🧠 TF-IDF-based text representation
📈 Cosine similarity-based ranking
🏆 Top relevant result retrieval
📊 Similarity score display
📈 Implementation

The TF-IDF vectorizer converts the textual medicine information into numerical feature vectors.

The system then calculates cosine similarity between the user's query and the medicine records.

The records with the highest similarity scores are returned as the most relevant results.

▶️ How to Run
1. Install Python

Make sure Python is installed on your system.

2. Install required libraries
pip install pandas numpy scikit-learn jupyter
3. Start Jupyter Notebook
jupyter notebook
4. Open the notebook
medicine_information_retrieval_system.ipynb
5. Run the cells

Run the notebook cells in order and enter a disease, disorder, or symptom when prompted.

📁 Project Structure
Medicine-Information-Retrieval-System/
│
├── Medicine_Details_Enhanced.csv
├── medicine_information_retrieval_system.ipynb
└── README.md
⚠️ Disclaimer

This project is developed for educational and academic purposes.

The retrieved medicine information should not be considered a substitute for professional medical advice, diagnosis, or treatment.

👨‍💻 Author

Tharun

B.Tech – Computer Science and Engineering
Specialization: Artificial Intelligence & Machine Learning
