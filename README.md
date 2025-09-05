# NLP2
A practical implementation of NLP concepts from Stanford's CS224N (Natural Language Processing with Deep Learning) course, comparing traditional TF-IDF with neural Word2Vec embeddings for sentiment analysis.

📋 Project Overview
This project implements and compares two fundamental NLP approaches for sentiment analysis:

TF-IDF (Term Frequency-Inverse Document Frequency): A statistical approach that evaluates word importance

Word2Vec: A neural embedding technique that captures semantic meaning (implementing concepts from CS224N)

The application provides an interactive interface to analyze text sentiment using both methods and compare their results.

🎓 CS224N Concepts Implemented
Word Vectors & Embeddings (Lecture 1)

Word2Vec Algorithms: CBOW architecture (Lecture 2)

Distributional Semantics & Vector Space Models (Lectures 1-2)

Window-based Classification (Lecture 3)

Practical Comparison of Traditional vs Neural Methods

🛠️ Technical Skills Demonstrated
Python Programming

NLP Techniques: Text preprocessing, tokenization, feature extraction

Machine Learning: Logistic Regression, model evaluation

Deep Learning: Word2Vec implementation, embedding spaces

Libraries: Scikit-learn, Gensim, NumPy, Pandas, Gradio

Software Engineering: OOP, modular code design, API development


How It Works
Text Input: User enters text for sentiment analysis

Preprocessing: Text is cleaned and tokenized

Feature Extraction:

TF-IDF: Convert text to weighted frequency vectors

Word2Vec: Convert to semantic embeddings using pre-trained model

Classification: Logistic Regression predicts sentiment

Results: Comparison of both approaches with confidence scores

Results Example
Input: "This product is absolutely amazing! I love it."

TF-IDF Results:

Positive: 92.3%

Negative: 5.4%

Neutral: 2.3%

Word2Vec Results:

Positive: 88.7%

Negative: 7.1%

Neutral: 4.2%

🌟 Future Enhancements
Add Skip-gram implementation

Include BERT/Transformer comparisons

Implement attention visualization

Add model persistence

Expand to multi-class classification

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
