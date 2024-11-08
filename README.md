# Health Connect Bot

## Description
A specialized healthcare chatbot trained specifically on medical data using LangChain and a graph database, designed to provide secure access to patient medical histories, allergies, procedures, and claim information. 
The model is also capable of answering user questions based on medical knowledge, offering tailored responses to healthcare-related queries
---

## Key Features
- **Medical History Access**: Patients can query their medical history and get detailed information on encounters, procedures, and allergies.
- **Claim History Retrieval**: The chatbot allows patients to retrieve and interact with their claim history.
- **Medical Model Integration**: Built using Palmyra Med, which is specifically trained on medical data to provide accurate and domain-specific answers.
- **Graph Database**: Uses Neo4j for graph-based data modeling to manage relationships between patients, encounters, and healthcare data.
- **Business Logic via LangChain**: LangChain is used to manage the business logic and streamline complex tasks.
- **Orchestration**: Airflow is implemented for orchestrating workflows and scheduling tasks.
- **Data Pipelines**: Apache PySpark handles large-scale data processing for patient records and medical histories.
- **Tunneling for Accessibility**: Ngrok is used for secure tunneling to make the backend accessible for testing or production environments.
- **Frontend Interface**: A user-friendly interface built using Streamlit for patient interaction and data visualization.

## Tech Stack
- **Backend**: FastAPI, LangChain, Apache PySpark
- **Database**: Neo4j (Graph Database)
- **Data Processing**: Apache PySpark for handling large-scale data
- **Orchestration**: Apache Airflow
- **Frontend**: Streamlit for easy interaction and visualization
- **Tunneling**: ngrok for secure connections
- **AI Model**: Stability.ai for general model deployment, Palmyra Med for the medical domain model

## Getting Started

### Prerequisites
Make sure you have the following software installed:
- Python 3.x
- FastAPI
- Apache Airflow
- Apache PySpark
- Neo4j
- Streamlit
- ngrok
- Palmyra Med (for the medical model)
- LangChain
- Stability.ai (for AI models)

You can check for specific versions or installation instructions in the installation section.

### Installation

You can install the required dependencies via `pip`:
```bash
pip install -r requirements.txt
