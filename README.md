# 🌦️ Weather App (Full Stack - AWS Serverless)

A real-time weather application built using **HTML, CSS, JavaScript** and deployed on **AWS Cloud** with a **serverless backend**.

---


## 📂 GitHub Repository

📁[ https://github.com/your-username/weather-app](https://github.com/siddheshchore/weather-app.git)

---

## 📊 Architecture

User → S3 (Frontend) → API Gateway → Lambda → OpenWeather API → Response → UI

---

## 🧰 Tech Stack

### 👨‍💻 Frontend

* HTML
* CSS
* JavaScript

### ☁️ Backend (Serverless)

* AWS Lambda (Node.js)
* AWS API Gateway

### 🌍 Cloud & Tools

* AWS S3 (Static Website Hosting)
* GitHub (Version Control)

### 🌦️ External API

* OpenWeather API

---

## ✨ Features

* 🌍 Search weather by city
* 🌡️ Real-time temperature data
* 💨 Wind speed & humidity
* ⚡ Fast & responsive UI
* ☁️ Fully deployed on AWS

---

## 🛠️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

---

### 2️⃣ Setup Frontend

* Open `index.html` in browser
  OR
* Deploy using AWS S3

---

### 3️⃣ Setup Backend (AWS)

#### Step 1: Create Lambda Function

* Runtime: Node.js
* Add weather API logic

#### Step 2: Create API Gateway

* Create HTTP API
* Connect with Lambda

#### Step 3: Enable CORS

* Allow all origins

---

### 4️⃣ Connect Frontend to Backend

Update `script.js`:

```javascript
const API_URL = "https://your-api-id.execute-api.ap-south-1.amazonaws.com/weather";
```

---

## ⚠️ Common Issues

* ❌ 404 Error → Check `index.html` name
* ❌ API not working → Check API Gateway URL
* ❌ CORS Error → Enable CORS in Lambda

---

## 📸 Screenshots

<img width="1918" height="1030" alt="Screenshot 2026-03-29 234612" src="https://github.com/user-attachments/assets/9c1a9ce3-cddb-4455-b237-243739b3865e" />


---

## 📈 Learning Outcomes

* ✔️ Serverless architecture (AWS Lambda)
* ✔️ API integration
* ✔️ Cloud deployment using AWS S3
* ✔️ Version control using GitHub

---

## 🔮 Future Improvements

* 🔐 User Authentication (AWS Cognito)
* 🗄️ Store search history (DynamoDB)
* 📱 Mobile responsive UI
* 🔄 CI/CD pipeline



