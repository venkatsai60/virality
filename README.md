
# Analyzing Social Media Content to Identify Factors Driving Viral Video Propagation

## Project Overview

This project aims to understand the factors contributing to viral video propagation on social media platforms. Using machine learning techniques, we analyze video metrics like views, likes, comments, and dislikes to predict the likelihood of a video going viral. The system includes an interactive web interface where users can input YouTube video URLs to receive insights and actionable recommendations.

---

## Features

### Key Modules
1. **Video Data Extraction and Preprocessing Module**
   - Extracts video metrics from YouTube (e.g., views, likes, dislikes, comments).
   - Performs feature engineering and data scaling for better model training.

2. **Virality Prediction and Model Evaluation Module**
   - Implements logistic regression and neural networks for virality prediction.
   - Evaluates model performance using accuracy, precision, recall, and F1-score.

3. **User Video Upload Module**
   - Allows users to input a YouTube video URL.
   - Fetches and processes video metrics for analysis.

4. **Insights Generation and Recommendations Module**
   - Provides detailed insights into video performance.
   - Generates personalized recommendations to improve video reach and engagement.

### Technologies Used
- **Backend**: Python with Flask
- **Machine Learning**: Scikit-learn, TensorFlow/Keras
- **Natural Language Processing**: NLTK
- **Computer Vision**: OpenCV
- **Visualization**: Matplotlib, Seaborn
- **Data Handling**: Pandas, NumPy
- **YouTube Integration**: PyTube

---

## Project Workflow

1. **Data Collection**
   - Fetch video metrics using the YouTube API or PyTube.
   - Metrics include views, likes, dislikes, comments, and engagement rates.

2. **Data Preprocessing**
   - Clean and scale data.
   - Engineer features like like-dislike ratio and sentiment from comments.

3. **Model Training**
   - Train models (logistic regression and neural networks) using historical video metrics.
   - Evaluate models on test datasets.

4. **User Interaction**
   - Users upload a YouTube video link through the interface.
   - The system fetches video metrics and predicts virality.

5. **Insights and Recommendations**
   - Analyze engagement metrics and provide actionable insights.
   - Suggest optimizations for future videos.

---

## Results

- **Model Performance**:
  - Logistic regression and neural networks were effective in predicting virality, with neural networks slightly outperforming.
- **Key Findings**:
  - Metrics like views, likes, and like-dislike ratio are strong predictors of virality.
  - User engagement metrics (comments and likes) are highly correlated with viral success.

---

## Future Enhancements

- **Platform Expansion**:
  - Extend analysis to platforms like TikTok and Instagram for broader applicability.
- **Real-Time Data Integration**:
  - Include real-time social media data to enhance predictions.
- **Advanced Models**:
  - Experiment with transformer-based models (e.g., BERT) for sentiment analysis.
- **Niche-Specific Insights**:
  - Tailor insights for specific video genres or demographics.

---

## How to Run

1. Clone the repository.
   ```bash
   git clone [repository_url]
