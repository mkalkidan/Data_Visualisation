Airline Sentiment Analysis: The Class Gap
A Comparative NLP study analyzing the "Sentiment Gap" between Business and Economy class reviews for 29 major global airlines.

✈️ Project Overview
This project uses Natural Language Processing (NLP) to determine if there is a statistically significant difference in passenger satisfaction based on their travel class.

📊 Key Findings
The Sentiment Gap: Business Class polarity consistently outperforms Economy Class across all 29 analyzed airlines.

Positivity Bias: While individual reviews vary, the industry average stays within the 0.05 to 0.35 range (neutral-positive).

The "Winner": Singapore Airlines emerged as a top performer with high sentiment scores in both cabins.

🛠️ Technical Stack
Data: Skytrax Airline Reviews (Kaggle).

Language: Python (Pandas).

NLP: TextBlob (Lexicon-based sentiment polarity).

Visualization: Plotly (Interactive Scatter Plots) and WordCloud.

📈 Methodology
Filtering: Only included airlines with >100 Business, >200 Economy, and >500 total reviews.

Cleaning: Stripped metadata tags like ✅ Trip Verified |.

Analysis: Calculated average polarity scores for each cabin type per airline.

Open the Sentiment_analysis.ipynb notebook in Jupyter or VS Code to view the analysis and visualizations.

<img width="1026" height="360" alt="newplot" src="https://github.com/user-attachments/assets/b251ec68-b67d-4299-a2ca-d745f1ca4a08" />
