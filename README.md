# Medical Spa Sentiment Analysis

## Project Overview
This project conducts a comprehensive comparison of sentiment analysis techniques to determine the most effective method for analyzing customer reviews of medical spas in Toronto and Montreal. The analysis aims to help medical spa businesses extract actionable insights from customer feedback to improve service quality, enhance customer satisfaction, and drive business growth.

## Problem Statement
The medical spa industry in Toronto and Montreal faces increasing competition and relies heavily on customer feedback to maintain and improve service quality. The challenge lies in efficiently analyzing the large volume of unstructured customer reviews to extract actionable insights that can drive business improvements. With a goal of increasing customer satisfaction by 15% and reducing negative feedback by 20% over the next year, it is crucial to implement the most effective sentiment analysis technique.

This analysis aims to compare four distinct sentiment analysis approaches—probability-based (VADER), similarity-based (TF-IDF), information-based (Decision Tree), and error-based learning (Logistic Regression and CardiffNLP)—to determine which method most accurately captures the nuances of customer sentiment in medical spa reviews.

## Dataset
The analysis utilizes a dataset of 3,447 customer reviews from medical spas in Toronto and Montreal. Each review includes:
- Rating (1-5 stars)
- Review text
- Reviewer information
- Business details

## Methods Implemented
The project compares four learning approaches:

1. **Probability-based Learning**: VADER (Valence Aware Dictionary and sEntiment Reasoner)
2. **Similarity-based Learning**: TF-IDF with Cosine Similarity
3. **Information-based Learning**: Decision Tree Classifier
4. **Error-based Learning**:
   - Logistic Regression
   - CardiffNLP (RoBERTa transformer model)

## Key Features
- Complete data preprocessing pipeline for text data
- Implementation of multiple sentiment analysis techniques
- Comprehensive evaluation metrics and visualizations
- Comparative analysis of model performance
- Recommendations for optimal sentiment analysis strategy

## Results Summary
The analysis revealed that:
- CardiffNLP achieved the highest agreement (97.2%) with customer ratings
- VADER showed strong performance (94.7% agreement)
- Traditional methods like Decision Tree and Logistic Regression exhibited lower agreement
- CardiffNLP effectively differentiated sentiment across rating levels, while other models showed less clear distinctions

## Recommendations
Based on the analysis, CardiffNLP is recommended for sentiment analysis of medical spa reviews due to its high accuracy and nuanced sentiment classification. The model can be implemented to:
- Monitor service quality
- Evaluate staff performance
- Assess treatment effectiveness
- Guide marketing content creation
- Track competitive differentiation

## Project Structure
```
├── README.md                   # Project documentation
├── medical_spa_sentiment.ipynb # Main analysis notebook
├── requirements.txt            # Package dependencies
└── data/
    └── Toronto_Montreal_reviews_new.csv  # Dataset
```

## Installation and Usage

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required packages listed in requirements.txt

### Setup
1. Clone this repository
```
git clone https://github.com/yourusername/medical-spa-sentiment.git
cd medical-spa-sentiment
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Run the Jupyter notebook
```
jupyter notebook medical_spa_sentiment.ipynb
```

## Future Work
- Incorporate aspect-based sentiment analysis to identify specific service elements
- Develop a sentiment analysis dashboard for real-time monitoring
- Expand the analysis to include more locations and service types
- Implement a feedback loop system based on sentiment insights

## License
[MIT License](LICENSE)

## Contact
For questions or collaboration, please contact:
- Your Name - [bellosabur@gmail.com](mailto:bellosabur@egmail.com)
- GitHub: [SaburBello](https://github.com/SaburBello)
