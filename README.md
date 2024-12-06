# 📦 Hack the Future

Welcome to the "Hack the Future" app, a forward-thinking solution created to address critical mental health challenges facing youth in Rwanda and across Africa. This project leverages advanced AI, data analytics, and machine learning to provide actionable insights and support for mental health professionals, policy-makers, and communities. We use **Vite + React JS** for a fast, dynamic frontend and **Google Colab** to host machine learning models, including **pre-trained GPT** and **BERT** for natural language processing.

## 🌍 Project Vision

Our mission is to create a data-driven mental health platform that provides powerful insights and predictive capabilities. By empowering stakeholders with real-time analytics, we aim to enhance mental well-being and support for youth across Africa.

## 🚀 Features

- **Dynamic Data Visualization**: Interactive charts and dashboards provide clear insights into mental health trends among youth.
- **Predictive Modeling**: Advanced machine learning models predict mental health outcomes based on demographic, social, and economic factors.
- **AI Chatbot for Mental Health**: A responsive chatbot powered by **pre-trained GPT** offers immediate support and answers to frequently asked mental health questions.
- **Professional Directory**: Connect with a network of mental health professionals for additional guidance and support.
- **Multilingual Support**: Available in multiple languages, including English and Kinyarwanda, for broader accessibility.
- **Community Forum**: An anonymous space for users to share experiences and support each other in a safe environment.

- **Frontend**: Vite + React JS for a fast and modern user interface.
- **Backend**: Google Colab-powered API for ML model predictions and data processing.
- **Data Processing**: Pandas and Numpy for data handling and preprocessing.
- **Machine Learning**: Scikit-learn and deep learning models, including **pre-trained BERT** for sentiment analysis and text classification, and **pre-trained GPT** for natural language processing tasks.
- **NLP**: Hugging Face Transformers for utilizing pre-trained models like **BERT** and **GPT**.

### 🧑‍💻 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/hack-the-future.git
   cd hack-the-future
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Run the App**:
   ```bash
   npm run dev
   ```

### 🚧 Prerequisites

- **Node.js**: Version 14 or higher.
- **Vite**: `npm create vite@latest`
- **React JS**: Version 18.x
- **Google Colab**: For hosting the predictive model API.
- **Hugging Face Transformers**: For leveraging **pre-trained GPT** and **BERT** models.

### 🔍 Key Datasets

1. **Youth Mental Health Data**: Contains various metrics on mental health, substance use, social support, and demographics.
2. **General Population Data**: Used for comparative analysis and trend visualization.
3. **Mental Health Indicators**: Annual indicators across different mental health diagnoses.
4. **Dementia and Care Data**: Related to specific mental health challenges and treatment facilities in Rwanda.

> **Note**: Ensure data privacy and sensitivity when handling personal information. Anonymize data as necessary.

## 📈 Model Training and API

The model training process and API deployment are managed in **Google Colab**:
1. **Data Processing**: Cleaning, feature engineering, and outlier detection.
2. **Model Training**: Predictive models including Random Forest, Logistic Regression, and deep learning models for advanced analytics.
3. **API Integration**: Models are exposed through a RESTful API to be called from the Vite + React app for real-time predictions. We leverage **pre-trained BERT** for text classification and **pre-trained GPT** for language generation and NLP tasks.

## 🤖 AI Chatbot

Our custom chatbot, *Menti*, provides users with personalized responses. *Menti* is trained on common mental health FAQs and offers sentiment analysis to respond empathetically, powered by **pre-trained GPT**.

## 📄 License

This project is licensed under the MIT License.

## 👥 Contributing

We welcome contributions! Please fork this repository, make your changes, and submit a pull request for review.

1. **Fork the Repository**
2. **Create a Feature Branch** (`git checkout -b feature-branch`)
3. **Commit Changes** (`git commit -m "Your message"`)
4. **Push to Branch** (`git push origin feature-branch`)
5. **Open a Pull Request**
