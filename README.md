# UniBot: AI-Powered University Chatbot

## Problem Statement
As inquiries to prestigious universities rise, the need for an intelligent chatbot to enhance customer service becomes crucial. UniBot is designed to accurately interpret inquiries and deliver appropriate responses using state-of-the-art natural language processing (NLP) and machine learning models. By reducing the workload on admissions teams and improving response quality, UniBot aims to revolutionize user experience on university websites.

## Features
- **Intent Prediction:** Utilizes NLP techniques for accurate classification of user inquiries.
- **Multiple AI Models:** Users can choose from four models (NLTK, BERT, Hybrid, and Rasa) for tailored chatbot responses.
- **Flask API Integration:** Ensures fast and efficient processing of user queries.
- **Robust Dataset Processing:** Employs text classification, pattern recognition, and data augmentation techniques for enhanced accuracy.
- **Scalability & Cloud Deployment:** Designed to handle increasing user traffic efficiently.

## General Working
1. **Text Preprocessing & Intent Recognition:**
   - Uses **NLTK** for foundational NLP tasks.
   - BERT enhances understanding of complex inquiries.
   - A **Hybrid Model** integrates rule-based and ML-based approaches.
   - **Rasa** provides advanced conversational AI capabilities.
2. **Dataset Handling:**
   - Tags inquiries into categories like **admissions, placements, fees, courses, hostels**, etc.
   - Uses **NLPAug & LLM-based data augmentation** for improving classification accuracy.
3. **Response Generation:**
   - Leverages APIs to generate fast responses.
   - Supports dynamic responses with conversational memory.

## Tech Stack
- **Frontend:** JavaScript, HTML, CSS
- **Backend:** Python (Flask)
- **Machine Learning Libraries:** TensorFlow, NLTK, Rasa, BERT (Hugging Face Transformers)
- **Data Augmentation:** NLPAug
- **Cloud Infrastructure:** AWS/Google Cloud for scalability

## Chatbot Models
1. **NLTK-Based Model:** Rule-based approach for basic inquiry handling.
2. **BERT Model:** Transformer-based model for deep contextual understanding.
3. **Hybrid Model:** Combination of rule-based and ML models for improved accuracy.
4. **Rasa Framework:** Advanced AI-powered chatbot with intent recognition and conversational memory.

## Scalability
- **Elastic Cloud Infrastructure:** Supports horizontal and vertical scaling.
- **Load Balancing:** Prevents bottlenecks and ensures smooth operation.
- **Optimized ML Models:** Reduces computational overhead.
- **Monitoring & Auto-Scaling:** Dynamically adjusts resources based on demand.

## Future Enhancements
- **Integration with Messaging Platforms** (WhatsApp, Messenger, Slack, etc.)
- **Personalized Recommendations & Adaptive Responses**
- **Advanced Analytics & Insights** for user behavior analysis
- **Continuous Model Improvement** leveraging cutting-edge AI advancements

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/unibot.git
   cd unibot
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the chatbot server:
   ```bash
   python app.py
   ```
4. Access the chatbot via the frontend.

## Contributing
We welcome contributions! Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or support, please contact [your-email@example.com](mailto:your-email@example.com).
