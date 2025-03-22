# EM_Bot

EM_Bot is an AI-powered chatbot designed to provide intelligent assistance in medical diagnostics by analyzing symptoms, identifying potential diseases, and suggesting the appropriate type of doctor for consultation. The bot integrates machine learning and Retrieval-Augmented Generation (RAG) techniques to ensure accurate and contextually relevant responses.

## Features

- **Symptom-based Diagnosis**: Predicts potential diseases based on user-input symptoms.
- **Doctor Recommendations**: Suggests the right type of doctor for consultation.
- **RAG Integration**: Uses document embeddings and similarity search to retrieve relevant medical information.
- **Conversational Engagement**: Keeps users motivated with interactive conversations.
- **Data Analysis**: Provides insights into symptom-disease relations with graphical representations.

## Technology Stack

- **Backend**: Python (Flask/Django)
- **Frontend**: React.js / Vue.js
- **Machine Learning**: TensorFlow / PyTorch
- **Database**: PostgreSQL / MongoDB
- **Document Indexing**: LlamaIndex / Elasticsearch
- **Deployment**: Docker, AWS, Google Cloud
- **Security**: Authentication & Authorization mechanisms

## Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/AvHai/EM_Bot.git
   cd EM_Bot
   ```
2. Create a virtual environment:
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use: env\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the application:
   ```sh
   python app.py
   ```
5. Open your browser and visit `http://localhost:5000`

## Usage

1. **Input Symptoms**: Users enter symptoms in natural language.
2. **Diagnosis Processing**: The bot processes the input using vectorization and ML models.
3. **Disease Prediction**: The system identifies the most probable disease.
4. **Doctor Recommendation**: Suggests the appropriate type of doctor.
5. **Information Retrieval**: Provides insights on disease, prevention, and treatment using RAG.

## Future Enhancements

- **Integration with Telemedicine Services**
- **Voice-based Interaction**
- **Multilingual Support**
- **Enhanced Data Collection & Model Refinement**

## Contributing

We welcome contributions! Follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-branch
   ```
3. Commit changes and push:
   ```sh
   git commit -m "Added new feature"
   git push origin feature-branch
   ```
4. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


