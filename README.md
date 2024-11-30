# DSA-210 Term Project: Personal Social Media Engagement/Consumption Analysis
This project aims to analyze my social media usage and habits using the data from various platforms (Particularly spotify, as I use it the most). I aim to understand my content preferances, usage patterns and test how I have been profiled in these platforms(platform inferences).

## Datasets
The project uses the following datasets, collected through platform requests and APIs(still collecting): 

### 1. Spotify Data:
- **Streaming History**: Includes timestamps, platforms, track details, listening durations, and other metadata.
- **Spotify Inferences**: Insights inferred by Spotify about music preferences, listening habits, and general interests.

And some other information like search queries, etc. 

Example: 

```json
{
    "ts": "2023-03-13T13:20:50Z",
    "platform": "ios",
    "ms_played": 265263,
    "master_metadata_track_name": "NEON BLADE",
    "master_metadata_album_artist_name": "MoonDeity",
    "reason_start": "trackdone",
    "reason_end": "trackdone"
}
```

### 2. Instagram Data: 
- **Impressions History**: Records of posts viewed, authors, and timestamps.
- **Saved Media**: Information about saved posts and their categories.
- **Topics of Interest**: Topics inferred based on engagement patterns.

And other useful information.

Example:

```json
{
    "topics_your_topics": [
        {"Name": {"value": "Crafts"}},
        {"Name": {"value": "Basketball"}}
    ]
}
```

### 3. Netflix Data: 
-**Watch History**: Titles watched, genres, and timestamps.

### 4. Reddit Data: 
-**User Engagement**: Posts, comments, and subreddit activity.

Some other useful personal data such as screen time, activity, etc. can be used in the future to relate to social media consumption. Also, data from other platforms such as "Twitter", "Twitch", "Youtube" could be used in the future to give variety and extend the scope of the initial analysis.  

## Project Plan
**Step 1:** Data Collection and Preprocessing: 
- Format, clean the data for data analysis
- If necessary use APIs or other means to enrich data 

**Step 2:** Exploratory Data Analysis(EDA):
- Analyze trends in consumption
- Visualize top genres, artists, engagement patterns
- Identify correlations
  
**Step 3:** Statistical Analysis and Hypothesis Testing
- Test some formed hypothesis regarding the data and findings
  
**Step 4:** Simple Machine Learning Model (If time permits)

**Step 5:** Deliverables and Report
