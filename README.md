
# 📱 SMS Spam Detection using Machine Learning

## 🔍 Project Overview
This project aims to accurately classify SMS messages as **spam** or **ham (not spam)** using advanced machine learning techniques. It leverages feature engineering techniques and ensemble boosting algorithms like **CatBoost**, **LightGBM**, and **XGBoost** to enhance detection performance and ensure high accuracy.

## 🧠 Key Features
- Text preprocessing using **TF-IDF**, **Bag-of-Words**
- Ensemble learning algorithms for classification
- Evaluation using **Accuracy**, **Precision**, **Recall**, and **F1-score**
- input SMS and predict result

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Scikit-learn, Pandas, NumPy, XGBoost, LightGBM, CatBoost
- **Visualization:** Matplotlib, Seaborn
- **Notebook:** Jupyter Notebook (.ipynb)

## 📁 Dataset
-  SMS Spam Collection Dataset  (https://drive.google.com/file/d/1HCMeXRu4JNLHy5oB7N9wJZa-7v1NDqis/view?usp=sharing))
- Contains 5,572 messages labeled as "spam" or "ham"

## 🚀 How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/sms-spam-detection.git
   cd sms-spam-detection
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook
   ```bash
   jupyter notebook sms_spam.ipynb
   ```

## 📊 Results
| Model       | Accuracy | Precision | Recall | F1-Score |
|-------------|----------|-----------|--------|----------|
| CatBoost    | 98.4%    | 97.8%     | 98.7%  | 98.2%    |
| LightGBM    | 97.9%    | 97.5%     | 98.1%  | 97.8%    |
| XGBoost     | 98.1%    | 98.0%     | 98.2%  | 98.1%    |

## 🧪 Future Enhancements
- Integration of deep learning models like LSTM or BERT
- Real-time SMS prediction web service
- Federated learning for privacy-preserving spam detection

## 👨‍💻 Contributors
- **K.V. Siva Reddy** (21121A1252)
- K. Krushna Harshi (21121A1240)
- G. Hemanth (21121A1227)
- M. Thejomsri Sai (21121A1261)

## 📜 License
This project is part of the B.Tech Final Year Submission at Sree Vidyanikethan Engineering College. Open for academic and research use.
