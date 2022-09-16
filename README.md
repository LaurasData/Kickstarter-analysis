# Kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends

### Purpose
- Analysis of Kickstarter campaigns in relation to their launch dates and their funding goals.

## Analysis and Challenges
- Created pivot tables and grouping in Excel to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date and funding goals
- Grouped "Row Labels" by months in the Pivot table
- Created Year() from Conversion date

### Analysis of Outcomes Based on Goals
    - While there are 1047 Theater Kickstart Campaigns
        694 were successful, 353 Theater Kickstart Campaigns Failed: but No Plays were canceled.
    - Over 85% of Successful Kickstarter Plays grossed less than $5000.
    - https://github.com/LaurasData/Kickstarter-analysis/blob/Resources/Theater_Outcomes_vs_Launch.png
       
### Challenges and Difficulties Encountered
- Created the conversion dates and years in the pivot tables was resolved by referring to Microsoft support for Countifs(), Years() and Time Stamp conversions.
- Microsoft docs and overstock provided formulas and explanations of concepts
- https://www.unixtimestamp.com/
- https://stackoverflow.com/questions/27065840/meaning-of-cells-rows-count-a-endxlup-row
- https://docs.microsoft.com/en-us/office/vba/api/excel.worksheetfunction.countifs
- https://github.com/LaurasData/Kickstarter-analysis/blob/Resources/Outcomes_vs_Goals.png
- https://github.com/LaurasData/Kickstarter-analysis/blob/Resources/Theater_Outcomes_vs_Launch.png

## Results

#### What are two conclusions you can draw about the Theater Outcomes based on Launch Date?
    A. While there are 839 successful Theater campaigns
        1. May and June have the highest Theater rates of successful campaigns
    B. While there are 37 total canceled Kickstarter campaigns
        1. Jan has the highest rate of Theater cancellations.
   
#### What can you conclude about the Play Outcomes based on Goals?
    A. While there are three types of Theater campaigns (Plays, Musicals, and Space)
        1. No Plays were canceled.
    B. While there are 694 successful Kickstarter plays, over 85% grossed less than $5000.
    C. https://github.com/LaurasData/Kickstarter-analysis/blob/Resources/Outcomes_vs_Goals.png

#### What are some limitations of this dataset?
    A. Moving and renaming formulas was time consuming

#### What are some other possible tables and/or graphs that we could create?
    A. Create a stacked Bar graph of types of theater campaigns canceled
    B. Create a Box and Whiskers graph can show the outliers for this dataset
    B. Create 
