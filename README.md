🛡️ AI-Powered Fake News Detector

An end-to-end Natural Language Processing (NLP) web application designed to classify news articles as real or fake in real-time. Built with Python, Scikit-Learn, and Streamlit, featuring an interactive inference dashboard deployed on Streamlit Community Cloud[cite: 1].

---

## 🚀 Live Demo & Access
* **Live Web Application:** [https://fake-news-detector-dpk3haeorbtqjmfgpmljb2.streamlit.app](https://fake-news-detector-dpk3haeorbtqjmfgpmljb2.streamlit.app)
* **GitHub Repository:** [snehajha0613/Fake-News-Detector](https://github.com/snehajha0613/Fake-News-Detector)[cite: 10]

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python[cite: 1]
* **Machine Learning & NLP:** Scikit-Learn (Logistic Regression, TF-IDF Vectorizer)[cite: 1]
* **Data Manipulation & Analysis:** Pandas, NumPy[cite: 1]
* **Visualization:** Matplotlib[cite: 1]
* **Web Framework & Deployment:** Streamlit Community Cloud[cite: 1]

---

## 📊 Project Architecture & Pipeline
1. **Data Preprocessing & Cleaning:** Handled missing values, cleaned text features, and conducted exploratory analysis on dataset distributions.
2. **Feature Extraction:** Implemented **TF-IDF (Term Frequency-Inverse Document Frequency)** to transform raw text into numerical representation vectors.
3. **Model Training:** Trained a high-accuracy **Logistic Regression** classifier optimized for binary text classification[cite: 1].
4. **Evaluation & Diagnostics:** Performed holdout evaluations (Accuracy, Precision, Recall, F1-Score) and prediction confidence scoring[cite: 1].
5. **Interactive UI:** Constructed a responsive Streamlit dashboard supporting real-time text input classification and performance metric displays[cite: 1].

---

## ⚙️ Local Installation & Setup

To run this application locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/snehajha0613/Fake-News-Detector.git](https://github.com/snehajha0613/Fake-News-Detector.git)
   cd Fake-News-Detector
Install dependencies:

Bash
pip install -r requirements.txt
Train the model (Generates binary pipeline & evaluation outputs):

Bash
python src/train_model.py --real data/True.csv --fake data/Fake.csv --outdir outputs
Launch the Streamlit interface locally:

Bash
python -m streamlit run src/streamlit_app.py
💡 Key Highlights
Zero-Downtime Deployment: Hosted on cloud architecture for instant accessibility by recruiters and peers.

Production-Ready Structure: Modular code layout separating dataset ingestion, model training scripts, and UI presentation components.

👩‍💻 Author
Sneha Jha

LinkedIn: linkedin.com/in/sneha-jha-02sj

GitHub: github.com/snehajha0613   
PNG


---

### Step 2: Push the updated README to GitHub
Run these commands in your VS Code terminal to sync your updated documentation with GitHub:

```bash
git add README.md
git commit -m "Update README with live Streamlit deployment URL"
git push origin main
