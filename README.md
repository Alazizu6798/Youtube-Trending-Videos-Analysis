# Youtube-Trending-Videos-Analysis

# Introduction
YouTube is the most popular and most used video platfrom in the world today. YouTube has a list of trending videos that is updated constantly. Here we will using Power BI to analyze a dataset that was collected over 205 days. For each of those days, the dataset contains data about the trending videos of that particular day. It contains data about more than 37,000 trending videos. We will analyze this data to get insights into YouTube trending videos, to see what is common between these videos. These insights might also be used by people who want to increase popularity of their videos on YouTube.

This project analyzes U.S. YouTube Trending Videos for March 2018 using Power BI, providing insights into video performance, audience engagement, and viewing trends. The dashboard is fully interactive with filters for date and category, making it a useful tool for content creators, marketers, and analysts.

# 🗂 Dataset
- Source:- <a href="https://drive.google.com/file/d/1qugMIRiaDPny8yKJu3Q3DQMjYVAypBAL/view?usp=drive_link"> U.S. YouTube Trending Videos Dataset</a>
         - <a href="https://github.com/Alazizu6798/Youtube-Trending-Videos-Analysis/blob/main/Category_name.xlsx">Category Names</a>
- Time Period: March 2018
- Key Fields :
  - Video Title
  - Channel Name
  - Views, Likes, Dislikes, Comments
  - Engagement Rate
  - Upload Date & Time
  - Video Category

# 📌 Key Features of the Dashboard
# 1. Filters & Slicers
- Month Selector : Choose the month for analysis
- Category Selector : Filter by video category
- Date Picker : Select specific upload dates

# 2. KPIs (Cards)
- Total Views : 12B
- Total Likes : 402M
- Total Dislikes : 14M
- Total Comments : 46M
- Engagement Rate : 4.0%

# 3. Visuals Used

📊 Bar Charts
- Top 10 Trending Videos by Views : Ranked with gradient formatting
- Top 10 Channels by Views : Channel-wise performance ranking
- Average Likes & Dislikes by Category : Comparison by category

🍩 Donut Chart
- Weekday vs Weekend Views : Proportion of views by day type
🔥 Heatmap
- Views by Hour & Day : Highlights peak viewing times

# ⚙ DAX Measures Used
- Total Views = SUM(Views)  
- Total Likes = SUM(Likes)  
- Total Dislikes = SUM(Dislikes)  
- Total Comments = SUM(Comments)  
- Engagement Rate = ((SUM(Likes) + SUM(Comments)) / SUM(Views)) * 100  
- Weekend/Weekday Views calculated using WEEKDAY() classification.

# 🎯 Insights

- Most views occur during weekdays, especially during late afternoon hours.
- Certain categories dominate in likes but not in dislikes.
- Engagement rate varies significantly between top categories.
- Top-performing channels contribute a large share of overall views.
  
# 🖥 Dashboard Preview


# 🏆 Skills Demonstrated
- Power BI Dashboard Design
- Data Cleaning & Transformation
- DAX Calculations
- Conditional Formatting
- Interactive Visualizations


