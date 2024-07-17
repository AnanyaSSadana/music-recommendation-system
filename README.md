# Music Recommendation System using PySpark and Kafka

Overview
This project implements a content-based music recommendation system using a combination of modern data processing and machine learning tools. The system recommends songs similar to those in a user's liked playlist by leveraging streaming data and sophisticated analytical techniques.

Technologies Used
Apache Kafka: For real-time data streaming.
PySpark: For data processing and handling large datasets.
Spark SQL: For querying structured data.
MLlib: For machine learning algorithms including KMeans and PCA.
Streamlit: For creating an interactive user interface.
Spotify API: For retrieving song data.
Features
Real-time Data Streaming: Utilizes Kafka to stream song data in real-time.
Data Processing and Analysis: Employs PySpark and Spark SQL to process and analyze the streamed data.
Machine Learning: Implements KMeans clustering and PCA analysis using Spark's MLlib to recommend songs.
Interactive Visualization: Uses Streamlit to visualize recommendations and user interactions.
Content-Based Filtering: Recommends songs based on features extracted from the user's liked playlist.
