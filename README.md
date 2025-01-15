# Agroo-AI

Agroo-AI is an all-in-one, user-friendly web application designed to revolutionize the agricultural industry by offering a marketplace for buyers and sellers, alongside smart farming insights such as crop monitoring, soil analysis, climate prediction, precision farming, and disease diagnosis using deep learning and AI technologies. 

This platform aims to empower farmers with innovative tools to improve productivity, reduce risks, make data-driven decisions, hereby addressing food security.

## Features

- **Marketplace for Buyers and Sellers**: Connects farmers with potential buyers, removing intermediaries, ensuring transparency, and fostering direct trade.
- **Smart Farming Insights**:
  - **Crop Monitoring**: Tracks crop health and growth using real-time data and advanced analytics.
  - **Soil Analysis**: Provides insights into soil quality and health for optimized farming practices.
  - **Climate Prediction**: Offers weather forecasts to assist farmers in planning their farming activities.
  - **Precision Farming**: Leverages data to improve farming efficiency and reduce resource wastage.
  - **Disease Diagnosis**: Uses AI and deep learning to diagnose crop diseases and provide treatment recommendations.
  
- **Deep Learning and AI Models**: Utilizes TensorFlow and Keras for the development and deployment of machine learning models for disease diagnosis, crop monitoring, and more.
- **Containerization with Docker**: Ensures easy deployment and scalability of the app.
- **Cloud Deployment on GCP**: Models are deployed on Google Cloud Platform to ensure scalability and reliability.

## Tech Stack

- **Frontend**: ReactJS for building the user interface
- **Backend**: FastAPI for developing the API
- **Machine Learning**: TensorFlow, Keras for model development and disease diagnosis
- **Containerization**: Docker for packaging the application
- **Cloud**: Google Cloud Platform (GCP) for hosting and deploying the application
- **Database**: (Specify the database used, e.g., MySQL, PostgreSQL)

## Setup Instructions

### Prerequisites

1. Install [Node.js](https://nodejs.org/) (for ReactJS frontend)
2. Install [Python](https://www.python.org/) (for FastAPI backend)
3. Install [Docker](https://www.docker.com/) (for containerization)
4. Install [Google Cloud SDK](https://cloud.google.com/sdk) (for GCP deployment)

### Frontend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/agroo-ai.git
   cd agroo-ai/frontend
2. Install dependencies:
   npm install
3. Run the frontend development server:
   npm start
   http://localhost:3000/
## Demo here: (https://agrooai.savvy91psinnovates.tech/)
## Backend Setup
1. Navigate to the api directory:
   cd ../api
2. Install Dependencies:
   pip install -r requirements.txt
3. Start the FastAPI server:
   uvicorn main:app --reload
   
   
## Model Development and Deployment
Navigate to the model directory:

cd ../training
Train your model using TensorFlow or Keras:

python train.py
Deploy the model on GCP:

gcloud app deploy
Ensure your API endpoints are connected to the deployed models for inference.

Docker Setup
# Build the Docker image: docker run -it -v C:\Agroo-AI\sweet-potato:/sweet-potato -p 8501:8501 --entrypoint /bin/bash tensorflow/serving

docker build -t agroo-ai .
# Run the Docker container:docker run -it --rm -p 8501:8501 -v C:/Agroo-AI/sweet-potato:/sweet-potato tensorflow/serving --rest_api_port=8501 --model_config_file=/sweet-potato/models.config

Contributing
We welcome contributions! If you'd like to contribute, please fork the repository and create a pull request with your changes.

Guidelines for Contributions
Ensure all code is well-documented.
Follow best practices for Python and JavaScript development.
Provide clear commit messages.
License

Acknowledgments
Codebasic
TensorFlow and Keras for machine learning model development.
FastAPI for the backend API.
ReactJS for the frontend user interface.
Google Cloud Platform (GCP) for cloud deployment.
Docker for containerizing the application.
Contact
For any inquiries or feedback, feel free to contact us at (https://matt.savvy91psinnovates.tech/).
 
