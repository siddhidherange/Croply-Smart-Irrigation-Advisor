# 🌱 Croply – Smart Irrigation Advisor

Croply is an AI-driven irrigation recommendation system that helps farmers decide **when and how much water crops need**.  
By analyzing **soil data, crop type, fertilizer details, and live weather inputs**, Croply predicts irrigation levels to reduce water waste, improve yield, and enable climate-smart farming.

---

## ✨ Features
- ✔️ Predicts irrigation levels: **High / Medium / Low / None**
- ✔️ ML-based insights replacing manual guesswork
- ✔️ Inputs: soil type, crop type, fertilizer, and weather data
- ✔️ Interactive **Streamlit** web interface
- ✔️ Water-efficient and farmer-friendly solution
- ✔️ Easily deployable as a web app

---

## 🔄 Workflow
1. Collect soil, crop, and fertilizer dataset  
2. Fetch live weather inputs using API  
3. Preprocess and encode data  
4. Train **Random Forest Classifier**  
5. Save trained model and encoders as `.pkl` files  
6. Deploy UI using **Streamlit**  
7. Generate irrigation recommendations  

---

## 🧠 Tech Stack

### Machine Learning & Data
- Python  
- Pandas, NumPy  
- Scikit-learn  

### App & Deployment
- Streamlit  
- Weather API  
- Pickle (model persistence)  

---

## 📁 Project Structure


```text
Croply/
├── data/
├── model/
│   ├── croply_model.pkl
│   └── encoders.pkl
├── app.py
├── pages/
│   └── Recommendation.py
└── README.md
```


## 📈 Output
- ML-based irrigation recommendation  
- User-friendly input page  
- Clear and simple result display for farmers  

---

## 🌱 Future Scope
- 🔹 IoT sensor integration for real-time soil data  
- 🔹 Support for multiple regions and crop varieties  
- 🔹 Offline mobile application for rural access  
- 🔹 Advanced and more accurate weather prediction models  

---

## 🤝 Contribution
Contributions, suggestions, and improvements are welcome!  
Feel free to raise issues or submit pull requests (PRs).

