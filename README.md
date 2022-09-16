# Kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends

### Purpose
- Analysis of Kickstarter campaigns in relation to their launch dates and their funding goals.

## Analysis and Challenges
- Created pivot tables and grouping in Excel to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date and funding goals
- Grouped "Row Labels" by months in the Pivot table
- Created Year() from Conversion date

## Analysis of Outcomes Based on Goals
    - While there are 1047 Theater Kickstart Campaigns
        694 were successful, 353 Theater Kickstart Campains Failed: but No Plays were canceled.
    - Over 85% of the Successful Kickstarter Plays grossed less then $5000.
    - https://github.com/LaurasData/Kickstarter-analysis/blob/Resources/Theater_Outcomes_vs_Launch.png
    - 
   
### Challenges and Difficulties Encountered
- Created the converation dates and years in the pivot tables was resolved by referring to microsoft support for Countifs(), Years() and converstions.
- Microsoft docs and overstock provided formulas 

## Results

#### What are two conclusions you can draw about the Theater Outcomes based on Launch Date?
    A. While there are 839 successful theater campaigns
        1. May and June have the highest Theater rates of sucessful campaigns
    B. While there are 37 canceled  Kickstarter campaigns
        1. Jan has the highest Theater cancelaton rates.
   
#### What can you conclude about the Play Outcomes based on Goals?
    A. While there are three types of Theater campaigns (Plays, Musicals, and Space)
        1. No Plays were canceled.
    B. While there are 694 successfull Kickstarter plays, over 85% grossed less then $5000.
    C. Outcomes_vs_Goals.png

#### What are some limitations of this dataset?
    A. Moving and renaming formulas was time consumming

#### What are some other possible tables and/or graphs that we could create?
    A. Create a stacked Bar graph of types of theater campaigns canceled
    B. Create a Box and Whiskers graph can show the outliers for this dataset
    B. Create a Histogram graph of the distribution of goals
