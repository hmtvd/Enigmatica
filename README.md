# Machine Learning Chatbot Analysis

## Overview
This project focuses on analyzing chatbot performance for machine learning-related queries to identify and improve weak areas through data augmentation and refinement. The main objective is to ensure that the chatbot provides accurate and relevant responses across various topics in machine learning.

## Team
- Kushal Shah
- Saurabh Yadav
- Mallesh Kamati
- Nikhil Verma
- Hemant Meena

## Features
1. **Data Collection and Preprocessing**:
   - Generated 1600 labeled machine learning questions using ChatGPT and Perplexity AI.
   - Topics include:
     - Supervised Learning
     - Unsupervised Learning
     - Reinforcement Learning
     - Semi-Supervised Learning
     - Deep Learning
   - Preprocessed data using pandas and nltk libraries.

2. **Machine Learning Model**:
   - Implemented Naive Bayes classifier.
   - Achieved 89% accuracy with a train-test split of 75%-25%.

3. **Data Analysis**:
   - Topic classification using BERTopic for graphical clustering.
   - Analyzed chatbot performance based on user feedback.
   - Evaluated satisfaction levels using sentiment analysis and graphical insights.

4. **Performance Comparison**:
   - Compared chatbot responses with GPT-4, GPT-3, and web answers.
   - Achieved an average cosine similarity of 52% over 50 test questions.

## Libraries Used
- pandas
- nltk
- BERTopic
- plotly.express
- sentence_transformers
- sklearn

## Workflow
1. **Data Preprocessing**:
   - Removed duplicates, irrelevant rows, and tokenized sentences.
2. **Topic Clustering**:
   - Used BERTopic to cluster paragraphs and topics visually.
3. **User Feedback Analysis**:
   - Processed synthetic user queries and feedback to measure satisfaction levels.
4. **Performance Evaluation**:
   - Compared chatbot responses with external models to measure accuracy.

## Future Work
- Implement advanced classification algorithms to enhance accuracy.
- Focus on efficient data classification for improved performance.
- Increase testing datasets and explore real-time optimization techniques.

## Contributions
- **Kushal Shah**: Topic clustering and BERTopic analysis.
- **Saurabh Yadav**: Data preprocessing and Naive Bayes model implementation.
- **Mallesh Kamati**: User feedback analysis and satisfaction graph development.
- **Nikhil Verma**: Performance comparison and cosine similarity testing.
- **Hemant Meena**: Integrated synthetic data generation and real-time analysis.

## Thank You
For further details, feel free to reach out or explore the codebase for more insights!
