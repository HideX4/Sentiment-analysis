# Sentiment Analysis App

This project consists of a **Flutter** frontend and a **Flask** backend for sentiment analysis. The backend processes requests and returns sentiment predictions (0=negative, 1=neutral, or 2=positive).

### 🧩 My Contributions

My contributions to this sentiment analysis project included key responsibilities across the data pipeline and parts of the model development process:

- **Data Collection:**  
  Curated and aggregated a diverse dataset for sentiment classification, ensuring coverage across multiple sentiment classes and domains.

- **Data Cleaning & Preprocessing:**  
  - Removed noise such as stopwords, special characters, and punctuation.  
  - Normalized text via lowercasing and lemmatization.  
  - Handled missing values and performed label encoding for categorical targets.

- **Text Tokenization:**  
  Tokenized the text data for model compatibility using NLTK.

- **Model Training & Evaluation (Support):**  
  Collaborated on model selection and tuning. Supported training runs and contributed to evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.


---

## Project Structure

- **Backend/**: Flask backend for handling API requests and making predictions.
- **Frontend/**: Flutter mobile application that interacts with the backend.
- **Documentation/**: Includes a report (`.pdf` & `.docx`) detailing the process and a video demo of the app.
- **ModelDevelopment/**: Jupyter notebooks used for creating and training the machine learning models.

---

## Backend (Flask)

### Installation

1. Clone the repository:
   ```
   bash
   git clone https://github.com/HideX4/Sentiment-analysis.git
   cd Backend
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the Flask app:
   ```
   python run.py
   ```

---

## Frontend (Flutter)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/HideX4/Sentiment-analysis.git
   cd Frontend/sentiment-analysis
   ```

2. Install Flutter dependencies:
   ```
   flutter pub get
   ```

3. Run the Flutter app:
   ```
   flutter run
   ```