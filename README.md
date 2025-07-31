# YouTube-Trending-Video-Analysis
An exploratory data analysis project using Python and Seaborn to uncover patterns in YouTube trending videos, including time to trend and category popularity.

# YouTube Trending Video Analysis

**Technologies:** Python, Pandas, Seaborn, Matplotlib  
**Date:** July 2025

## Project Overview
This project explores YouTube trending video data to uncover insights into how videos gain popularity and which content categories dominate the trending charts. As a student-led exploratory data analysis (EDA) project, it combines Python libraries with visual storytelling to identify performance trends, viral timing, and category-specific engagement.

## Key Objectives
- Examine how quickly videos trend after being published  
- Identify which video categories appear most frequently on the trending list  
- Visualize trends to highlight disparities across genres and virality  

## Tools & Technologies
- Python (Pandas, Seaborn, Matplotlib)  
- VS Code for development  
- GitHub for project versioning and publication  

## Core Analysis Performed

### 1. Data Cleaning & Preprocessing
- Converted `publish_time` and `trending_date` columns to timezone-consistent datetime objects  
- Filtered and structured the dataset to focus on U.S. trending data  

### 2. Days to Trend Analysis
- Calculated the number of days it takes for a video to reach the trending list after publishing  
- Visualized distribution with a histogram (most videos trend within 1 day)  

### 3. Top Trending Categories
- Counted and plotted the top 10 most frequent video categories by trend count  
- Observed that *Entertainment* and *Music* dominate the platform  

### 4. Percentage Contribution by Category
- Converted absolute counts into percentages for clearer comparative analysis  
- Added value labels to improve chart readability  

## Sample Insights
- A large majority of videos trend within the first 24 hours of being published, suggesting algorithmic favoritism toward recency  
- *Entertainment* alone accounts for over 20% of the top-trending videos, indicating a strong audience preference  
- Educational and niche categories (e.g., *Science & Technology*, *Film & Animation*) have much lower visibility  

## Next Steps
- Deploy an interactive Tableau dashboard using the category and trend data  
- Expand the analysis to compare different countries (e.g., CA, GB) or incorporate temporal trends over months  

---
## Author
Farzan Feeha
Information Science Student – July/August 2025
