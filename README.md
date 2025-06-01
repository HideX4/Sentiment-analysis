# Sentiment Analysis App

<!-- TODO: Add my contributions -->
This project consists of a **Flutter** frontend and a **Flask** backend for sentiment analysis. The backend processes requests and returns sentiment predictions (0=negative, 1=neutral, or 2=positive).

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