# Skintellet: AI-Powered Facial Analysis for Personalized Skincare Recommendations

## 🌟 Overview
**Skintellet** is an intelligent, AI-powered facial analysis system that transforms skincare diagnostics and accessibility. It uses deep learning and computer vision to detect acne, assess oiliness levels, and provide personalized skincare recommendations in real-time. The platform also features an integrated dermatologist booking system, making expert advice more accessible than ever.

## 🔍 Key Features

- 🧠 **AI-based Acne Detection & Oiliness Assessment**
- 🤖 **Convolutional Neural Networks (CNNs)** for skin analysis
- 💡 **Personalized Skincare Recommendations**
- 📅 **Dermatologist Appointment Booking**
- 🌍 **Multi-skin tone and environment-aware predictions**
- 📷 **Real-time image upload & feedback**


## 🛠️ Tech Stack

| Layer          | Technologies Used                                |
|----------------|--------------------------------------------------|
| Frontend       | React.js, React Native, Flutter                  |
| Backend        | Node.js, Express.js, Django (alternative)        |
| AI/ML          | TensorFlow, PyTorch, OpenCV                      |
| Database       | PostgreSQL, Firebase                             |





## Clone the Repository

```bash
git clone https://github.com/yourusername/Skincare-Project.git
cd Skincare-Project

python app.py

Sample Prediction Code

@app.route('/predict', methods=['POST'])
def predict():
    image_file = request.files['image']
    image_path = save_and_preprocess(image_file)
    skin_result = model_skin.predict(image_path)
    oiliness_result = model_oiliness.predict(image_path)
    # Combine predictions and recommend products

Future Enhancements

Augmented Reality (AR) skincare visualization
Integration with IoT skincare devices
Advanced multilingual and accessibility features

## 📸 Screenshots

### 🔐 Login Page
![Login Page](https://github.com/MohanRajan-A/SkinCare-Project/blob/main/templates/login.html)

### 📝 Sign Up Page
![Sign Up]()

### 📊 AI Prediction Result
![Prediction Result](templates/analysis_result.png)

### 📅 Doctor Booking Interface
![Booking Page](templates/booking.png)

