# TravelTide-Rewards-Program
#### Tableau Dashboard: https://public.tableau.com/app/profile/leela.yathapu/viz/TravelTideSegmentationRewardsProgram/Dashboard4?publish=yes
#### Video Recording: https://www.loom.com/share/6cb135860994494ba097398429f2441b?sid=0a295b2f-aafb-4b71-aabf-e4e41c6c8c63

## Introduction/Background
This analysis is conducted to assist Elena Tarrant, Head of Marketing at TravelTide, in designing a personalized rewards program aimed at boosting customer retention. The focus is on selecting the most attractive perks for customers and assigning them to segments based on their specific travel behaviors, spending patterns.
Travel Tide currently consists of around 1.6 million users, not all have been active recently.
We have over 5 million unique app sessions with our users.
Our team was asked to identify active users and find good rewards perks for each.

## Requirement
As suggested by client we include users with more than 7 sessions Since Jan 4,2023.

## Objectives
The primary goal of this analysis is to group like minded customers based on their travel behaviour,spending patterns and determine which perks are likely to attract customers to book more frequent future travels from TravelTide.

## Approach
To achieve these objectives, we conducted an in-depth analysis of TravelTide's customer data, considering various customer behaviors and attributes to identify potential affinities to specific perks.

The process involves filtering TravelTide data according to specific cohort definitions, aggregating Session, Flight, and Hotel data while preserving key demographic and behavioral fields, and merging these insights into a comprehensive dataset.

We used Python,SQL queries and Tableau for data exploration, feature engineering, segmentation and visualization. This tailored approach should maximize satisfaction and loyalty within each segment.

## Prerequisites & Data Preparation
The notebook contains code focused on customer segmentation using filtering the data, defining the Cohort, initial data exploration, feature engineering-devising metrics, K-Means clustering, feature scaling, and evaluating the optimal clusters with silhouette scores and the Elbow method.

## Libraries and Data Setup:

Import necessary libraries (pandas, numpy, sklearn, etc.).
Create a connection to a PostgreSQL database and query the data.

## Data Preparation:

Several preprocessing steps (cleaning, feature engineering, etc.) have been performed.
Features are scaled using StandardScaler.

## Clustering:

K-Means is applied with varying numbers of clusters (n_clusters), and the silhouette scores are calculated to evaluate cluster quality.
The Elbow method is used to find the optimal number of clusters by plotting inertia.
Visualization:

The silhouette scores and inertia values are plotted to help determine the optimal number of clusters.
Tableau Dashboard: The Tableau dashboard serves as a powerful extension to the notebook's analytical work, transforming the customer segmentation insights into interactive visualizations. Leveraging the clusters identified through K-Means clustering, the dashboard provides a comprehensive view of customer segments, highlighting key metrics such as spending patterns, travel behaviors, and demographic characteristics.

## Summary of Analysis
As suggested by client we included customers with more than 7 sessions Since Jan 4,2023. This led to 5998 eligible customers for the reward program.

Based on the customer behavior and financial metrics in each segment, we can assign the most suitable perks based on the characteristics of their bookings, spending patterns, and travel preferences.

Segment 0: Free Cancellation
Segment 1: Exclusive Discounts
Segment 2: One Free Hotel Night with Flight
Segment 3: Free Checked Bag
Segment 4: Free Hotel Meal

## Benefits
In summary, the perks have been assigned based on each group's specific travel behaviours, spending patterns, and potential needs for flexibility or additional benefits.

Directly addresses current customer behaviour’s and preferences.

Enhances customer satisfaction by offering relevant perks and loyalty within each segment.

Encourages continued engagement based on existing usage patterns.

These assignments are tailored to enhance the value proposition for each group based on their travel behaviour and spending patterns.

## Recommendations
Focus on users who book multiple trips, particularly those who have already booked both flights and hotels together for their second or third trip. Create exclusive discount offers tailored to this segment, enticing them to continue booking all-inclusive travel packages.

Since users who book flight and hotel packages tend to spend more, ensure the booking process for combined packages is seamless and user-friendly. Highlight the potential savings and convenience of booking together.

Consider expanding the availability of discounts to a broader audience. While only 29% of trips received discounts in our analysis, there may be opportunities to attract more users by offering discounts for their first trips as well.

These recommendations should help tailor marketing strategies and email invitations to maximize customer engagement with TravelTide's rewards program.

It's essential to note that user preferences may evolve over time. Therefore, we recommend regularly reviewing analysis to adapt to changing user behavior and market dynamics.

## Next Steps and Conclusion
To operationalize the insights gained from our customer segmentation, we propose a structured approach:

Segmented Email Campaigns

Develop tailored email invitations, accentuating the perk most relevant to each customer segment.
Personalization is key to pique individual interests and drive engagement.
A/B Testing for Optimization

Implement A/B testing to validate the effectiveness of different marketing strategies and offers.
Conduct Ab testing with each segment to measure effectivness of different perks.
Continuously refine email strategies to maximize customer engagement.
Monitoring User Engagement

Implement tracking mechanisms to monitor user engagement with our personalized email campaigns.
Key metrics to observe include booking rates, click-through rates, and sign-up rates.
Feedback Collection

Encourage active participation from customers who enroll in the rewards program.
Solicit feedback regarding their perk preferences and overall experience.
Continuous Refinement

Utilize the gathered feedback to iteratively refine and personalize our perk offerings.
Aim for an evolving rewards program that resonates with our customers.
Dedicated Customer Support

Establish a customer support system to aid customers in perk redemption and address any queries or concerns linked to the rewards program.
By following this structured approach, we aim to not only attract customers but also maintain their engagement and loyalty by offering perks that align with their preferences. The continuous refinement of our offerings and strategies is pivotal to our long-term success.

It's essential to note that user preferences may evolve over time. Therefore, we recommend regularly reviewing of analysis to adapt to changing user behavior and market dynamics.
