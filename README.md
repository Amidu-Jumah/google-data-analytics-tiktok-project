# TikTok Video Performance & Engagement Analysis

📓 [View the complete analysis notebook](Google_Data_Analytics_Course_2_TikTok_Project.ipynb)

## Project Overview

This project analyzes TikTok video data to identify patterns associated with video performance and audience engagement.

The analysis was developed as part of my data analytics learning journey and extends the exploratory work from the Google Data Analytics Professional Certificate into deeper statistical analysis.

The project examines video views, likes, shares, comments, downloads, claim status, author status, and video duration to understand how these characteristics relate to engagement and performance.

## Business Questions

The analysis focuses on several key questions:

- What characteristics are associated with high-performing TikTok videos?
- Do high-performing videos generate stronger engagement even after accounting for their higher view counts?
- How do claim videos differ from opinion videos in views and engagement?
- Does video duration appear to distinguish high-performing videos?
- Are differences between selected groups statistically significant?

## Tools & Libraries

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- VS Code

## Analysis Performed

The project includes:

- Data inspection and cleaning
- Missing-value analysis
- Descriptive statistics
- Exploratory data analysis (EDA)
- Engagement-rate calculations
- High-performing video segmentation
- Claim vs. opinion video analysis
- Data visualization
- Correlation analysis
- Welch's independent-samples t-tests
- One-way ANOVA

## Key Findings

### High-Performing Videos

Videos in the top 25% of view count were classified as high-performing, using a threshold of approximately **504,327 views**.

After normalizing engagement by views, high-performing videos still showed stronger engagement than other videos:

- Like rate was approximately **28.1% higher**
- Share rate was approximately **26.4% higher**
- Download rate was approximately **28.1% higher**
- Comment rate was approximately **75% higher**

### Claim vs. Opinion Videos

Claim videos showed substantially greater reach and engagement than opinion videos.

Average video views were approximately:

- **Claim videos:** 501,029
- **Opinion videos:** 4,956

Compared with opinion videos, claim videos had approximately:

- **50.9% higher like rate**
- **50.8% higher share rate**
- **51.9% higher download rate**
- **180% higher comment rate**

### Video Duration

Video duration was very similar between high-performing and other videos.

The average duration was approximately:

- **High-performing videos:** 32.69 seconds
- **Other videos:** 32.33 seconds

This suggests that video duration alone does not meaningfully distinguish high-performing videos in this dataset.

## Statistical Testing

A Welch's independent-samples t-test was used to compare video views between claim and opinion videos.

The test produced a very large t-statistic and an extremely small p-value, providing strong statistical evidence of a difference in average views between the two groups.

A one-way ANOVA was also used to examine differences in comment rates across author ban-status groups.

These statistical results demonstrate association and group differences; they should **not be interpreted as proof of causation**.

## Skills Demonstrated

- Python data analysis
- Data cleaning and preprocessing
- Exploratory data analysis
- Feature engineering
- Data visualization
- Descriptive statistics
- Engagement-rate analysis
- Correlation analysis
- Hypothesis testing
- Welch's t-test
- ANOVA
- Interpretation of statistical results
- Communicating data-driven insights

## Repository Files

- `Google_Data_Analytics_Course_2_TikTok_Project.ipynb` — complete analysis notebook
- `tiktok_dataset.csv` — dataset used for the analysis
- `README.md` — project documentation

## Author

**Amidu Kofi Jumah**

Aspiring data professional building practical skills in Python, statistical analysis, and data-driven decision making.
