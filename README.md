# Youtube-Comments-NLP-with-Sentiment-Analysis
A Python project that uses Google Cloud's YouTube Data API to fetch video comments and perform sentiment analysis for audience insights

This project leverages Google Cloud's YouTube Data API v3 to fetch and aggregate comments from any specific video, providing insights into audience sentiment. Currently, the model retrieves up to 100 comments per video due to quota restrictions, though commercial implementations could lift these limits for larger-scale analyses. The aggregated comments are placed into a pandas DataFrame, enabling flexible data manipulation and sentiment analysis.

How Companies Can Use This for Evaluation
Identify Key Feedback: Highlight what viewers loved or disliked for better content strategies.
Monitor Brand Perception: Analyze trends in sentiment over time, especially after new campaigns or product launches.
Prioritize Response Efforts: Quickly address critical negative feedback to improve public perception.
Automate Insights: Use visualization tools to create dashboards summarizing overall audience sentiment.

Sentiment analysis is performed on each comment, splitting the results into individual columns for sentiment scores, making it easy to filter and explore. This data can be further analyzed using exploratory data analysis (EDA) to uncover trends and insights. While this is a proof of concept, more advanced NLP techniques or large language models could be integrated for deeper analysis, such as summarizing the general tone of the comments or providing comprehensive overviews of user feedback.

This project also demonstrates the powerful data collection capabilities of the YouTube Data API, showcasing how easily valuable data, such as video comments, can be gathered and processed for analysis. By using Google Cloud's API v3, we can automatically aggregate comments from any specific video, which is crucial for large-scale analysis or research without the need for manual data collection. The API’s ability to pull comments in bulk, even with the quota limitations, highlights its potential for gathering vast amounts of user-generated content, which can then be used for various purposes like sentiment analysis, trend identification, and content evaluation. This level of automation not only streamlines the data collection process but also enables real-time insights, allowing companies and researchers to track and analyze audience reactions as they happen.

This approach offers content creators, marketers, and researchers a valuable tool to evaluate videos without needing to sift through all the comments manually, streamlining the process of understanding audience sentiment and engagement.
