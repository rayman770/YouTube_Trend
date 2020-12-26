# YouTube_Trend

![youtube](https://seeklogo.net/wp-content/uploads/2017/08/YouTube-logo-1-512x512.png)

- **Dataset Source**
    - https://www.kaggle.com/datasnaek/youtube-new
    

- **Context of Dataset**
    - The dataset is a daily record of the top trending YouTube videos in the United States.
    - It contains 16 columns and 40,949 rows spanning the date range from November 2017 to June 2018
    - The original source provides an additional json file for category, which the raw dataset doesn't include.
    
    
- **Attribute Information**
    - video_id: ID of video recommended as trending video
    - trending_date: Date recommended as trending video
    - title: Title of video
    - channel_title: Channel title of video
    - category_id: ID of video category (associated with separate json file)
    - publish_time: Date and time when video was published
    - tags: Tags associated with video
    - views: Number of views on video
    - likes: Number of likes on video
    - dislikes: Number of dislikes on video
    - comment_count: Number of comments on video
    - thumbnail_link: Thumbnail link of video
    - comments_disabled: Whether or not comments disabled for video
    - ratings_disabled: Whether or not ratings disabled for video
    - video_error_or_removed: Whether or not video has error or removed.
    - description: Description of video
    
    
- **Table of Content**
    - Preparing Data
        - Importing the Dataset
        - Exploring the Dataset
        - Adding Category Information from Separate json File
        
    - Descriptive Analysis (Exploring Attributes & Time-Series)
        - Trending Video Types
        - Number of Trending Days Distribution
        - Top 10 Most Viewed, Liked, Disliked and Commented Videos
        - Daily Views, Likes, Dislikes, Comments
        - Monthly Views, Likes, Dislikes, Comments
        - Average Views, Likes, Dislikes, Comments by Time
        - Average Views, Likes, Dislikes, Comments by Weekday vs. by Weekend
        - Correlation Heatmap

    - Natural Language Processing (Text Analysis)
        - Word Cloud for Top 200 Tags
        - Sentiment Analysis (Polarity & Subjectivity) for 500 Descriptions
        - Topics of 500 Descriptions

    - Predictive Analysis (Machine Learning)
        - Linear Regression - predicting number of likes based on views, dislikes and comment counts
