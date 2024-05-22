# Sentiment and Text Analysis of YouTube Reviews of Young Sheldon
This project involved a detailed analysis of YouTube review videos and user comments related to the TV show "Young Sheldon." The project was divided into multiple questions, each focusing on different aspects of text analysis, sentiment analysis, and statistical interpretation.

Objectives
1.	Data Collection: Scraped captions and user comments from YouTube review videos.
2.	Sentiment and Subjectivity Analysis: Used Textblob and VADER to analyze the sentiment and subjectivity of captions and comments.
3.	N-gram Analysis: Identified and compared the top unigrams, bigrams, and trigrams in the captions.
4.	Emotion Detection and Sarcasm Analysis: Detected emotions and sarcasm in user comments.
5.	Supervised Machine Learning: Applied supervised machine learning techniques to classify comments.
6.	Clustering Analysis: Categorized comments into positive, neutral, and negative groups.
7.	Word Cloud Visualization: Created word clouds to visualize what users liked, disliked, and expected in future seasons of the show.

Steps and Deliverables
1.	 Data Collection
•	Selected two seasons of "Young Sheldon."
•	For each season, chose two different YouTube review videos.
•	Scraped captions from these four videos and saved them into CSV files.

2.	Sentiment and Subjectivity Analysis
•	Compared the average sentiment scores (Textblob polarity and VADER compound polarity) between the two YouTube channels.
•	Compared the average subjectivity scores (Textblob) between the two YouTube channels.
•	Compared the average sentiment scores (Textblob polarity and VADER compound polarity) between the two seasons.
•	Compared the average subjectivity scores (Textblob) between the two seasons.
Deliverable: Provided interpretations of the findings in a document.

3.	 N-gram Analysis
•	Identified the top 5 unigrams, bigrams, and trigrams in each video caption.
•	Compared similarities and differences among the four videos.
Deliverable: Saved results into CSV files and provided an interpretation document.

4.	User Comment Scraping
•	Scraped as many user comments as possible from the same four YouTube videos.
Deliverable: Saved the comments into CSV files.

5.	Sentiment and Subjectivity Analysis of Comments
For each scraped comment:
•	Performed sentiment analysis using Textblob’s polarity score and VADER’s compound polarity score.
•	Performed subjectivity analysis using Textblob.
•	Calculated readability (lexical complexity) of comments.

Deliverable: Saved results into CSV files.

6.	Sarcasm Detection
•	Calculated whether each comment was sarcastic or not.
Deliverable: Saved results into CSV files.

7.	Emotion Detection
•	Detected the strongest emotion in each comment.
Deliverable: Saved results into CSV files.

8.	Explicit Word Detection
•	Identified explicit words in the comments.
Deliverable: Saved results into CSV files.

9.	Supervised Machine Learning Analysis
•	Performed two supervised machine learning analysis to classify comments.
o	Random Forest Classifier with TF-IDF vectorization for predicting toxicity.
o	Support Vector Machine (SVM):

Deliverable: Saved results into CSV files and provided a detailed description and video link.

10.	 Hierarchical Cluster Analysis
•	Categorized comments into positive, neutral, and negative groups.
•	Described methods to overcome potential bias from subjectivity, emotion, and sarcasm.
Deliverable: Provided a document explaining the categorization process and bias mitigation strategies.

11.	Word Cloud Visualization
•	Created word cloud diagrams to explain:
•	What people liked and disliked about each season.
•	What viewers wanted to see in future seasons.
Deliverable: Provided word cloud diagrams and an interpretation document.

Tools and Libraries
•	Python: Used for scripting and data processing.
•	Libraries: BeautifulSoup, Selenium (for web scraping), Textblob, VADER, scikit-learn, matplotlib, wordcloud, and others as needed.
•	
This project offered a comprehensive approach to understanding viewer sentiments and opinions about "Young Sheldon." By leveraging various text analysis techniques and machine learning models, we aimed to uncover valuable insights that could inform future content strategies.


