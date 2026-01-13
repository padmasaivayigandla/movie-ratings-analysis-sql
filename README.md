Movie Ratings Analysis using SQL
================================
Project Overview:
RSVP Movies, an Indian film production company, plans to release a movie for a global audience.  
To support data-driven decision-making, this project analyses historical movie data using SQL to uncover insights related to genres, ratings, directors, actors, production houses, and audience preferences.

The analysis focuses on identifying patterns that can help RSVP Movies choose the right genre, collaborators, and strategy for their upcoming global release.

Business Objectives:
- Understand movie performance based on ratings and votes
- Identify high-performing genres and trends over time
- Analyse directors, actors, and production houses based on success metrics
- Provide actionable recommendations for a global movie launch

Dataset Information
===================
The dataset was originally provided in Excel format and loaded into a relational SQL database for analysis.

Note: Raw data files are not included in this repository.  
> This project focuses on SQL-based analysis, queries, and insights rather than data hosting.

Tools & Technologies
====================
- SQL (MySQL)
- MySQL Workbench
- Relational Database Design
- Window Functions & CTEs

Analysis Approach
=================
The analysis is organised into multiple segments, each answering specific business questions:

- Data exploration and table profiling
- Trend analysis by year and month
- Genre-based analysis (counts, duration, ratings)
- Movie rating distribution and popularity
- Identification of top movies, actors, actresses, directors
- Production house performance analysis
- Advanced SQL:
  - Window functions ('RANK', 'ROW_NUMBER', 'LEAD')
  - Running totals and moving averages
  - Weighted average ratings
  - Inter-movie duration analysis

All queries are written with clear comments and business context.

Key Insights:
- Certain genres consistently dominate in production volume and ratings
- High-rated movies are often concentrated among specific directors and production houses
- Weighted ratings based on votes provide more reliable insights than simple averages
- Language and region play an important role in audience engagement
- Specific actors and actresses show strong performance in high-rated movies

Business Recommendations:
- Focus on top-performing genres with consistent audience engagement
- Collaborate with proven directors and production houses for global reach
- Use vote-weighted ratings to evaluate movie success more accurately
- Consider multilingual and region-specific strategies to maximise audience impact

How to Use This Repository:
1. Load the dataset into a SQL database (e.g., MySQL)
2. Open 'movie_ratings_analysis.sql'
3. Execute queries segment by segment to reproduce the analysis

Key Learnings:
- Applying SQL to solve real-world business problems
- Working with complex relational schemas
- Writing optimised and readable SQL queries
- Translating analytical results into business insights

Author

Padma Sai Vayigandla

Data Science Learner
