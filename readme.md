# Insurance Premium Category 🚀

**Insurance Premium category** is a **FastAPI**-powered application that predicts insurance premium based on a large **CSV dataset of insurance**. The app is fully **containerized with Docker** and deployed on **AWS EC2** using a full **CI/CD pipeline**, showcasing modern cloud deployment and MLOps practices.

---

## Features ✨
- Predict accurate premium based on specifications.
- FastAPI backend for fast and efficient API responses.
- Handles large CSV datasets for training and prediction.
- Fully containerized using Docker for easy deployment.
- Scalable cloud deployment on AWS EC2.

---

## Tech Stack 🛠
- **Backend:** FastAPI  
- **Containerization:** Docker  
- **Cloud Deployment:** AWS EC2  
- **Data:** Premium specifications CSV dataset  
- **DevOps:** CI/CD pipeline

---

## Installation & Setup ⚙️

1. **Clone the repository**

git clone https://github.com/Sujalkumar123/Insurance-premium_AWS
cd Insurance Premium

2.  **Build Docker Image**

docker build -t Insurance premium .

3. **Run Docker Container**

docker run -p 8000:8000 Insurance premium

4. **Access the App**

Open your browser and go to: http://localhost:8000

---

## Deployment 🌐

• The app is deployed on AWS EC2.

• the EC2 Security Group allows the required port (e.g., 8000).

• IP or DNS of EC2 can be used to access the live app:

---

## Usage 💻

• Send a POST request to /predict endpoint with Insurance premium in JSON format.
• The API returns the predicted premium.

---

## Contributing 🤝

• Fork the repository and create a pull request.
• Feel free to improve the model, add features, or optimize deployment.
