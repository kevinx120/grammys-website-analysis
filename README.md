# Website Performance Analysis: Grammys vs. Recording Academy

## Project Overview
This project analyzes website performance data from the Grammys and Recording Academy websites to understand how the website split affected user engagement, traffic behavior, and audience demographics.

## Main Business Question
Should The Recording Academy keep the Grammys and Recording Academy websites separate, merge them back together, or consider another approach?

## Tools Used
- Python
- pandas
- Plotly Express

## Project Scope
This analysis focuses on:
- Website traffic
- Pageviews
- Sessions
- Pages per session
- Bounce behavior
- Average session duration
- Desktop and mobile users
- Audience age demographics

## Datasets
The project uses the following datasets:

- `grammy_live_web_analytics.csv`  
  Contains website analytics data for the Grammys website.

- `ra_live_web_analytics.csv`  
  Contains website analytics data for the Recording Academy website.

- `desktop_users.csv`  
  Shows user activity from desktop devices.

- `mobile_users.csv`  
  Shows user activity from mobile devices.

- `grammys_age_demographics.csv`  
  Contains age demographic data for the Grammys audience.

- `tra_age_demographics.csv`  
  Contains age demographic data for The Recording Academy audience.

## Data Dictionary
Common fields used in the analysis:

- `date` — Date the data was recorded
- `visitors` — Number of users who visited the website
- `pageviews` — Number of pages viewed
- `sessions` — Number of website sessions
- `bounced_sessions` — Sessions where users left after viewing only one page
- `avg_session_duration_secs` — Average time users spent on the site
- `pages_per_session` — Average number of pages viewed per session

## Key Findings
- Pages per session increased after the website split.
- Both the Grammys and Recording Academy websites showed improved engagement after the split.
- Separating the websites appears to provide users with a more focused experience.

## Recommendation
Based on the analysis, The Recording Academy should keep the Grammys and Recording Academy websites separate because the data shows stronger user engagement after the split.

## Contact
Kevin Olvera  
kevinolvera120@gmail.com
