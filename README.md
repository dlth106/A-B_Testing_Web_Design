This project analyzes the effectiveness of two different web design versions (Group A and Group B) using an A/B testing framework with chi-squared analysis. The goal of the experiment is to determine whether the new design improves user conversion rates compared to the existing version.

Problem Statement:

A company redesigned its website landing page and wants to know whether the new design leads to a higher conversion rate.
Two versions of the page are tested:

- **Design A (Control Group):** Original webpage design
- **Design B (Treatment Group):** New webpage design

Users are randomly assigned to one of the two versions.
The goal of this project is to determine whether Design B should replace Design A.

Dataset: User ID	Group	Page Views	Time Spent	Conversion	Device	Location

The dataset contains information about user interactions with the landing pages.
| Column       | Description                                  |
| ------------ | -------------------------------------------- |
| user_id      | Unique identifier for each user              |
| time spend   | Time of user visit                           |
| group        | Control or treatment group                   |
| Page Víews   | Page shown to the user                       |
| Conversion   | Whether the user converted (1 = Yes, 0 = No) |
| Device       | What the user's device                       |
| Location     | Where the user's from                        |

Results:

The A/B test results show a **statistically significant difference** in purchase conversion rates between the two designs.
Design B achieves a **higher conversion rate** compared to Design A, indicating that the new design positively influences user purchase behavior.

Conclusion:

Based on the statistical analysis, Design B significantly improves the purchase conversion rate compared to Design A.  
Therefore, the new design can be considered more effective and is recommended for implementation.
