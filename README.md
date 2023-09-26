# Crowdfunding Analysis

## About
This project involves the analysis of a dataset containing 1,000 sample crowdfunding projects. The goal is to uncover trends and insights in crowdfunding campaigns to better understand the factors that contribute to project success or failure.

## Data Analysis
- **Conditional Formatting**: The "Outcome" column is color-coded to represent different project statuses: successful, failed, canceled, or live.
- **Percent Funded**: A new column, "Percent Funded," calculates the campaign's funding relative to its goal and is visually represented with conditional formatting.
- **Average Donation**: The "Average Donation" column calculates the average amount contributed by backers.
- **Category and Sub-Category**: New columns, "Parent Category" and "Sub-Category," split the original category data for analysis.

## Category and Subcategory Analysis
- A pivot table and stacked-column pivot chart analyze project outcomes per category.
- Another pivot table and chart analyze outcomes per sub-category.

## Date Analysis
- Unix timestamps in the "deadline" and "launched_at" columns are converted into Excel's date format in "Date Created Conversion" and "Date Ended Conversion" columns.
- A pivot table and line graph visualize outcomes based on project launch date.

## Crowdfunding Goal Analysis
- A table and graph show the percentage of projects that were successful, failed, or canceled based on their funding goals.

## Statistical Analysis
- Summary statistics for the number of backers in successful and unsuccessful campaigns, including mean, median, min, max, variance, and standard deviation.

## Conclusions
1. **Theatre Plays**: The most common type of crowdfunding campaign is in the theatre, specifically plays. Within this category, slightly more than half of these campaigns succeed, while the rest are canceled or fail.

2. **Seasonal Success**: Crowdfunding campaigns are more successful in the summer. Over a ten-year period from 2010-2020, there is a trend towards more successful campaigns in June and July, with a simultaneous decrease in failed campaigns. This suggests that the most lucrative time to initiate a crowdfunding campaign is during those two months. Avoiding August launch dates is advisable, as favorable outcomes drop significantly.

3. **Dataset Age**: The dataset collection ended in January 2020, which limits the conclusions drawn. Sociological changes, such as the COVID-19 pandemic, suggest that different categories may be more successful in a post-pandemic world. For example, increased at-home consumption of food, entertainment, and information may impact campaign success, but we lack data to confirm these assumptions.

## Limitations
1. **US-Centric Data**: The dataset is predominantly from the US (76.3%), which skews the results to an American point of view, making them less applicable to other countries.

2. **Limited Insight**: The dataset provides limited insight into why some projects fail and others succeed. Marketing efforts, for example, could impact campaign success, but we lack data on advertising efforts and subcategory specifics.

3. **Dataset Age**: The data collection ended in January 2020, which is 3 years ago, limiting conclusions for a post-pandemic world.

## Additional Insights
1. A pie chart could provide an easily digestible overview of the most common subjects of crowdfunding campaigns.

2. A line graph correlating country with date could advise potential campaigns within specific locations when to launch their campaigns, especially since the data is predominantly from the US. Cross-referencing this data with each sub-category could answer specific launch timing questions for different types of campaigns.

---

This project aims to provide insights into crowdfunding campaign success and failure, benefiting organizations seeking crowdfunding support.
