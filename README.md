# Vivas-AI

# Vivas AI – Crop Recommendation API 🌾

This is the crop recommendation microservice of **Vivas AI**, an AI-powered decision support platform for farmers.

## 🚀 Features

- Predicts best crop based on land and season
- Trained on cleaned real-world dataset
- Uses Random Forest Classifier

## 📦 API Endpoint

- `POST /recommend_crop`
  - JSON Body:
    ```json
    {
      "cultivation_area": 2.5,
      "estimated_yield": 1.8,
      "rainfed": 1.0,
      "fallow": 0.0,
      "irrigated": 1.5,
      "field_area": 2.0,
      "total_cultivable_land": 3.0
    }
    ```
  - Returns:
    ```json
    {
      "recommended_crop": "BT Cotton"
    }
    ```

## ⚙️ Tech Stack

- Flask
- Scikit-learn
- Render (Deployment)

## 🌐 Live API

👉 https://vivas-ai-crop.onrender.com

## 🧠 Part of Vivas AI

Other modules (coming soon):  
✅ Crop Recommendation | 🔜 Disease Detection | 🔜 Yield Prediction | 🔜 Chatbot
