This project analyzes the effectiveness of two different web design versions (Group A and Group B) using an A/B testing framework with chi-squared analysis. The goal of the experiment is to determine whether the new design improves user conversion rates compared to the existing version.

Problem Statement:
A company redesigned its website landing page and wants to know whether the new design leads to a higher conversion rate.
Two versions of the page are tested:

- Control group: Old landing page
- Treatment group: New landing page

Users are randomly assigned to one of the two versions.
The goal of this project is to determine whether the new landing page should replace the old one.

Dataset:
The dataset contains information about user interactions with the landing pages.
| Column       | Description                                  |
| ------------ | -------------------------------------------- |
| user_id      | Unique identifier for each user              |
| timestamp    | Time of user visit                           |
| group        | Control or treatment group                   |
| landing_page | Page shown to the user                       |
| converted    | Whether the user converted (1 = Yes, 0 = No) |

Results:
The analysis shows that the difference in conversion rates between the new and old landing page is not statistically significant.
Therefore, there is insufficient evidence to conclude that the new page improves conversion.

Conclusion:
Based on the statistical test results:
The new landing page does not significantly outperform the old version.
The company should not replace the existing landing page based on the current experiment.
Further experimentation or design improvements may be needed before implementing the new page.
