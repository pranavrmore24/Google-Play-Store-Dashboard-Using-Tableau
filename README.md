# Google Play Store Dashboard Using Tableau

## Dashboard Screenshots

### Dashboard 1: Overview

![Google Play Store Dashboard Overview](Dashboard%20Screenshots/Dashboard%201%20(Overview).png)

### Dashboard 2: App Popularity & Install Analysis

![App Popularity and Install Analysis](Dashboard%20Screenshots/Dashboard%202%20(App%20Popularity%20%26%20Install%20Analysis).png)

### Dashboard 3: Rating Analysis

![Rating Analysis](Dashboard%20Screenshots/Dashboard%203%20(Rating%20Analysis).png)

### Dashboard 4: Reviews & User Engagement Analysis

![Reviews and User Engagement Analysis](Dashboard%20Screenshots/Dashboard%204%20(Reviews%20%26%20User%20Engagement%20Analysis).png)

### Dashboard 5: Pricing & Monetization Analysis

![Pricing and Monetization Analysis](Dashboard%20Screenshots/Dashboard%205%20(Pricing%20%26%20Monetization%20Analysis).png)

# Google Play Store App Analytics Dashboard Using Tableau

## Project Overview
This project analyzes the Google Play Store dataset to uncover insights related to app popularity, installs, ratings, reviews, pricing, content ratings, and user engagement. Using Tableau, interactive dashboards were created to help stakeholders understand app performance trends, market dynamics, and user preferences across different app categories.

## Objective
The objective of this project is to:

- Analyze app distribution across categories.
- Identify the most popular app categories based on installs.
- Evaluate app ratings and review patterns.
- Compare Free and Paid app performance.
- Understand user engagement through installs and reviews.
- Examine app pricing trends and their impact on ratings.
- Create interactive dashboards for business decision-making.

## Tools Used

- Tableau
- Microsoft Excel
- Data Cleaning & Transformation
- Data Visualization
- Dashboard Design

## Dataset Features

- App
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version

## Project Workflow

### 1. Data Cleaning

- Removed unnecessary columns
- Handled missing values
- Converted Installs column into numeric format
- Converted Reviews column into numeric format
- Converted Price column from text ($) to numeric values
- Converted Size values from MB/KB format
- Standardized Category names
- Verified data types
- Removed duplicate records

### 2. Basic Analysis (10 Questions)

- Total number of apps available
- Total installs across all apps
- Average app rating
- Distribution of apps by category
- Distribution of apps by content rating
- Free vs Paid app comparison
- Most installed app
- Most reviewed app
- Average rating by content rating
- Total categories available

### 3. Mid-Level Analysis (10 Questions)

- Top categories by installs
- Top applications by installs
- Highest-rated categories
- Average ratings across categories
- Reviews vs Ratings relationship
- Installs vs Ratings relationship
- Average reviews by category
- Category-wise review distribution
- Content rating impact on app ratings
- Free vs Paid app rating comparison

### 4. Advanced Analysis (5 Questions)

- Pricing impact on app ratings
- Price distribution analysis
- Installs vs Reviews correlation
- User engagement pattern analysis
- Category performance benchmarking

## Dashboard Structure

### Dashboard 1: Executive Overview

#### KPIs
- Total Apps
- Total Installs
- Average Rating
- Total Categories

#### Visuals
- Apps by Category
- Free vs Paid Apps
- Content Rating Distribution

#### Key Insight
The Play Store is dominated by Free apps, while the "Everyone" content rating category contains the highest number of applications.

### Dashboard 2: App Popularity & Install Analysis

#### KPIs
- Total Installs
- Average Installs
- Top Category

#### Visuals
- Top 10 Categories by Installs
- Top 10 Most Installed Apps
- Installs vs Ratings Scatter Plot

#### Key Insight
The GAME category generates the highest install volume, while popular Google and Meta applications dominate total installs.

### Dashboard 3: Rating Analysis

#### KPIs
- Average Rating
- Apps Rated 4+
- Highest Rated Category

#### Visuals
- Top Categories by Average Rating
- Average Rating by Content Rating
- Average Rating: Free vs Paid Apps
- Reviews vs Rating Scatter Plot

#### Key Insight
Paid applications generally receive slightly higher ratings compared to Free applications.

### Dashboard 4: Reviews & User Engagement Analysis

#### KPIs
- Total Reviews
- Average Reviews
- Most Reviewed App

#### Visuals
- Top Apps by Reviews
- Reviews vs Installs
- Average Reviews by Category
- Top Categories by Reviews

#### Key Insight
Applications with higher installs tend to receive significantly more reviews, indicating strong user engagement.

### Dashboard 5: Pricing Analysis

#### KPIs
- Total Paid Apps
- Average Paid App Rating
- Average App Price

#### Visuals
- Price Distribution Histogram
- Price vs Rating Scatter Plot
- Paid Apps by Category
- Average Price by Category

#### Key Insight
Higher-priced applications do not necessarily receive better ratings, suggesting price alone does not drive user satisfaction.

## Key Insights

### App Market Trends

- Free applications dominate the Google Play Store ecosystem.
- GAME category generates the highest install volume.
- Most applications belong to the "Everyone" content rating segment.
- Install counts are heavily concentrated among a small number of highly popular apps.

### Rating Insights

- Average app rating remains above 4.0.
- Paid applications generally receive better ratings than Free applications.
- Categories such as EVENTS and EDUCATION achieve the highest average ratings.

### User Engagement Insights

- Facebook is the most reviewed application.
- Reviews show a strong positive relationship with installs.
- SOCIAL and GAME categories receive the highest review activity.

### Pricing Insights

- Most applications are free.
- Paid apps are concentrated in specific categories.
- Price has a weak relationship with user ratings.
- Premium pricing does not guarantee higher customer satisfaction.

## Business Impact

### App Store Optimization

Developers can focus on high-performing categories such as GAME, COMMUNICATION, and SOCIAL to maximize visibility and downloads.

### User Acquisition Strategy

Understanding install patterns helps marketers prioritize categories with strong growth potential.

### Pricing Strategy

The weak relationship between price and ratings suggests developers should focus on app quality and user experience rather than premium pricing alone.

### Product Improvement

Review and rating analysis can help identify categories where users are more engaged and satisfied.

### Market Intelligence

Category-level performance metrics provide valuable benchmarks for launching new applications.

## Conclusion

This Tableau project provides a comprehensive analysis of the Google Play Store ecosystem through five interactive dashboards covering app distribution, installs, ratings, reviews, user engagement, and pricing behavior.

The analysis reveals that Free apps dominate the marketplace, GAME and COMMUNICATION categories drive the highest install volumes, and user satisfaction is influenced more by app quality and engagement than pricing. Review and install trends demonstrate strong user interaction patterns, while category-level insights help identify the most successful segments within the Play Store.

These findings can assist app developers, product managers, marketers, and business stakeholders in making data-driven decisions related to app development, pricing, user acquisition, and market expansion.
