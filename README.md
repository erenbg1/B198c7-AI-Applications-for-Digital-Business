# Medical Text Summarization System

## Overview
This project implements an AI-powered **text summarization system** tailored for the medical domain. The system extracts key points from complex medical texts, such as clinical notes, research papers, and patient records, providing concise summaries to enhance decision-making, research efficiency, and patient care.

## Features
- **Extractive Summarization:** Highlights the most relevant sentences from the input text.
- **Abstractive Summarization:** Generates human-like summaries that capture the core meaning of the text.
- **Evaluation Framework:** Ensures summarization quality using ROUGE, BLEU, and human evaluations.
- **Interactive Dashboard:** Visualizes summarization metrics, keywords, and key themes.
- **API Integration:** Real-time text summarization through a scalable REST API.

## Key Benefits
1. **Efficiency:** Reduces the time required to analyze lengthy medical texts.
2. **Accuracy:** Preserves critical information while summarizing.
3. **Scalability:** Handles large volumes of data effectively.

## Technology Stack
- **Programming Language:** Python
- **Frameworks and Libraries:**
  - Natural Language Processing: Hugging Face Transformers, NLTK, SpaCy
  - Machine Learning: TensorFlow, PyTorch
  - Deployment: Flask, FastAPI
  - Visualization: Plotly, Matplotlib
- **Cloud Platforms:** AWS, Azure

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-link>
   cd medical-text-summarization
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv env
   source env/bin/activate # For Linux/Mac
   env\Scripts\activate   # For Windows
   pip install -r requirements.txt
   ```

3. Set up API keys and configuration:
   - Obtain access to necessary APIs (e.g., PubMed API) and datasets.
   - Create a `.env` file with required credentials.

## Usage
### Summarization
1. Run the application:
   ```bash
   python app.py
   ```
2. Access the API or web interface at `http://localhost:5000`.
3. Input medical text and receive summarized results.

### Visualization
1. Open the interactive dashboard by navigating to `http://localhost:5000/dashboard`.
2. Explore summarization metrics, keyword clouds, and trends.

## Data Sources
- **PubMed Central (PMC) Open Access Subset**
- **MIMIC-III Clinical Database**
- **BioASQ Dataset**

## Evaluation Metrics
- **Quantitative:** ROUGE, BLEU, METEOR
- **Qualitative:** Human evaluations from medical professionals

## Future Work
- Expand dataset coverage to include more diverse medical topics.
- Implement multilingual support for non-English medical texts.
- Enhance visualization capabilities with additional insights.


