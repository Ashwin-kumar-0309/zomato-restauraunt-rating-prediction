# 🍽️ Zomato Restaurant Rating Predictor

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ashwin-kumar-0309/zomato-restauraunt-rating-prediction/blob/main/colab.ipynb)

A machine learning model to predict restaurant ratings on Zomato Bangalore dataset. 🔮

## 🎯 Objectives
- Predict restaurant ratings based on key features
- Analyze Bangalore restaurant market trends
- Create production-ready prediction model
- Simple Flask-based web interface

## 🚀 Quick Start

### Prerequisites
- Python 3.10+
- Google Account (for Colab)
- Basic terminal knowledge

### Installation
```bash
git clone https://github.com/Ashwin-kumar-0309/zomato-restauraunt-rating-prediction.git
cd zomato-restauraunt-rating-prediction
```

### ▶️ Running the Project
1. **Model Training**:
   - Open `colab.ipynb` in [Google Colab](https://drive.google.com/file/d/1soFYPGPB03xCMbIjzLLTUZ4OchOFrvMy/view?usp=sharing)
   - Upload `zomato.csv` from [Kaggle Dataset](https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants/download) and maybe adjust paths
   - Run all cells → Model saved as `model.pkl`

2. **Run Flask App**:
```bash
python app.py
```
3. Access `http://localhost:5000` in your browser 🌐

## 📁 File Structure
```
├── app.py               - Flask application
├── colab.ipynb          - Model training notebook
├── templates/           - HTML templates
│   └── index.html       
├── requirements.txt     - Dependencies
├── model.py             - Model utilities you won't need until you know what you're doing
└── Zomato_df.csv        - Sample dataset
```

## 🔢 Dataset
[Kaggle Dataset Link](https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants)  

## 🔢 Pre-trained model by me
[Model](https://drive.google.com/)  (to-do next commit)

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📜 License
Distributed under MIT License. See `LICENSE` for more information.

## 📧 Contact
Ashwin Kumar - karnamashwinkumar@gmail.com
