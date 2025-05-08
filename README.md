Overview
This project involves analyzing the Google Play Store Dataset, which contains information about apps, including their ratings, categories, installs, and other metadata. The goal was to perform Exploratory Data Analysis (EDA) and Feature Engineering to uncover insights and prepare the data for further modeling or analysis.

Dataset Description
The dataset consists of the following key features:

App: Name of the application

Category: Category the app belongs to (e.g., Games, Social, Tools)

Rating: User rating (out of 5)

Reviews: Number of user reviews

Size: Size of the app

Installs: Number of downloads/installs

Type: Free or Paid

Price: Price of the app (if paid)

Content Rating: Target audience (e.g., Everyone, Teen, Mature)

Genres: Sub-category of the app

Last Updated: Last update date

Current Ver: Current version

Android Ver: Minimum Android version required
Key Tasks Performed
1. Data Cleaning & Preprocessing
Handled missing values (e.g., Rating, Type, Content Rating).

Removed duplicates and irrelevant entries.

Converted Size into a consistent format (MB/KB).

Processed Installs into numerical values.

Extracted useful features from Last Updated (e.g., year, month).

2. Exploratory Data Analysis (EDA)
Univariate Analysis: Distribution of ratings, app categories, installs, etc.

Bivariate Analysis:

Relationship between Rating and Installs.

Comparison of Free vs. Paid apps.

Top categories by number of apps and installs.

Outlier Detection: Identified anomalies in Reviews, Rating, and Installs.

Visualizations:

Bar plots (Category distribution, Free vs. Paid apps).

Histograms (Rating distribution).

Box plots (Outlier detection in Reviews & Installs).

Heatmaps (Correlation analysis).

3. Feature Engineering
Created new features:

Size_MB: Unified app size in megabytes.

Installs_Numeric: Converted install ranges into numerical values.

Last_Updated_Year/Month: Extracted from Last Updated.

Encoded categorical variables (Category, Content Rating).

Scaled numerical features for modeling readiness.

Key Insights
Most apps are free (~90%), with paid apps having a higher average rating.

Top categories: Family, Games, and Tools dominate the Play Store.

Rating distribution is left-skewed, with most apps rated between 4.0 and 4.5.

Higher installs correlate with higher reviews, but not necessarily higher ratings.

Paid apps are generally smaller in size compared to free apps.

Dependencies
Python 3.x

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn (for feature scaling)
