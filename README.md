# Project Report: Coupon Acceptance Analysis

## Overview

This project explores the factors that influence whether a driver accepts or rejects a promotional coupon. By analyzing various demographic and behavioral attributes, we identified distinct patterns that separate high-conversion customers from those unlikely to engage. The primary goal of this analysis was to move beyond broad targeting and pinpoint the specific "profiles" that drive the most value for different coupon types.

## Findings: Who Accepts Coupons?

Our analysis revealed that prior habits are the single most significant predictor of whether a customer will accept a coupon. Across both Bar and Coffee House categories, customers who already frequented those establishments showed significantly higher acceptance rates than new or infrequent visitors.

## Bar Coupons

The Power of Habit: Drivers who visit bars more than 3 times a month have a 77% acceptance rate, which is more than double the 37% rate seen in infrequent visitors.

Social and Situational Context: Acceptance peaks at 71% for frequent bar-goers who are not accompanied by children. This suggests that social freedom and a lack of immediate responsibility are key drivers for spontaneous bar stops.

Target Demographics: Younger adults (under 30) and those in specific lifestyle clusters—such as those who also frequent "cheap restaurants"—show a higher propensity to accept, typically around 59%.

## Coffee House Coupons

The Loyalty Loop: Similar to bars, frequent patrons (3+ visits per month) accept coupons at a rate of 68%, compared to 45% for others. This indicates that these coupons act as a "subsidy" for an existing daily routine.

The Youth Factor: Drivers under the age of 30 who visit coffee houses at least once a month are highly responsive, maintaining a 68% acceptance rate. This segment represents the primary growth opportunity for this category.

## Recommendations & Actionable Items

To improve marketing ROI, the following strategies should be implemented:

Behavioral Targeting over Demographics: Prioritize coupon delivery to "High Frequency" users. The data suggests it is easier to reward an existing habit than to create a new one.

Conditional Suppression: For bar coupons, utilize real-time data to suppress offers when children are present in the vehicle, as this situational factor leads to a drastic drop in conversion.

Routine-Based Scheduling: Align Coffee House coupon delivery with traditional "morning commute" or "mid-afternoon break" windows to catch habitual users during their natural decision-making periods.

## Next Steps

Moving forward, the analysis should expand into the following areas:

Time-Series Analysis: Determine if specific days of the week or times of day significantly amplify the acceptance rates within our identified high-conversion segments.

Cross-Promotion Discovery: Perform a cluster analysis to see if "Coffee House" users and "Cheap Restaurant" users overlap, which could justify bundled promotional offers.

Predictive Modeling: Develop a logistic regression model to rank the importance of factors like income, age, and frequency, allowing for an automated "Propensity to Accept" score for every user in the database.
