# Credit-card-Marketing-analysis
  This project analyzes customer data to identify which segments are most likely to accept a credit card offer. Using PROC SQL and data visualization .  Key findings show that targeted marketing significantly improves results — acceptance rates increase from ~5.6% overall to ~18% 
**Project Work – Step-by-Step Tasks Completed**
* Imported the credit card marketing dataset into SAS using PROC IMPORT
* Explored dataset structure and variables using PROC CONTENTS
* Cleaned data by removing unwanted index column
* Checked for duplicate customers using Customer Number
* Calculated overall credit card acceptance rate

**Customer Behavior Analysis**
* Analyzed acceptance rate by Income Level
* Analyzed acceptance rate by Credit Rating
* Studied impact of Home Ownership on acceptance
* Compared acceptance by Mailer Type (Letter vs Postcard)
* Compared acceptance by Reward Type (Air Miles, Points, Cash Back)
* Evaluated combined impact of Mailer Type + Reward

**Customer Segmentation**
* Created balance-based segments using Average Balance (Low / Medium / High)
* Analyzed acceptance by Average Balance group
* Studied acceptance by number of Credit Cards Held
* Analyzed impact of Overdraft Protection
* Analyzed Household Size vs acceptance rate

**Advanced Targeting Analysis**
* Combined Income Level + Credit Rating to find high-potential segments
* Built multi-factor segmentation using:
  * Income Level
  * Credit Rating
  * Average Balance
  * Mailer Type
  * Reward

**Business Insights**
* Identified best-performing segment:
  * Low income customers
  * Low credit rating
  * Low average balance
  * Air Miles reward
* Compared Overall vs Targeted acceptance rate
* Found targeted marketing improves acceptance from ~5.6% to ~18% (≈3X increase)

**Visualization**

* Created bar charts using PROC SGPLOT for all major segments
* Built comparison graph: Overall vs Targeted acceptance rate

**Outcome**

* Identified high-potential customer segments
* Provided data-driven strategy to improve campaign performance
* Demonstrated SQL, data cleaning, segmentation, and business insight skills 
