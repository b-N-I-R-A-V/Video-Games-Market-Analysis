# Video Games Market Analysis
**Purpose and Context:** GamesCo, a video game company, wants to make data driven decisions for their future development of games. The purpose of this project was to perform global
market analysis for video games, historical market trends and market competition for the development of new games for our client GameCo.

### Project Goals:
- Determine popular game genres.
- Identify main competitors in specific markets.
- Examine sales variations across geographic regions.

# Tools and Techniques
Excel is a very powerful tool that can be used to perform data analysis for relatively small dataset. This project was carried out entirely in Excel utilizing is capabilities and the presentation was prepared using PowerPoint. This project demonstrates of the following skills:
1. Data Cleaning
2. Data Summarizing
3. Excel
4. Pivot Tables
5. Descriptive Analysis
6. Report Writing and Story Telling with Data 

# Dataset
The dataset used for this analysis comes from VGChartz. You can click on [VGChartz Dataset Link](https://images.careerfoundry.com/public/courses/intro-to-data/E1/vgsales.xlsx) to checkout the dataset. To prepare the dataset for the analysis I carried out the following series of steps:
1. Understanding the structure of the data
2. Identified columns with missing data
3. Removed completely vacant column NA units from the sheet
4. Missing categorical variables were filled with NA to highlight unknown values
5. Removed duplicate rows
6. Imputed mean values for missing data for quantitative variables

### Challenges
The dataset from VGChartz has limitations because it no longer estimates software sales due to the complexity of tracking digital sales reliably. Hardware sales estimates are based on retail sampling and may vary up to 10% from actual totals. The data is frequently updated to match official figures but can fluctuate, and there's a difference between VGChartz's sell-through data and manufacturers' sell-in data, except when consoles are discontinued.

## Key Questions
The following were the guiding questions that helped during the analysis:
* Are certain types of games more popular than others?
* What other publishers will likely be the main competitors in certain markets?
* How have their sales figures varied between geographic regions over time?

## Understanding Sales and Trends
Once ready with the dataset and having a set of questions to guide me, I started by describing the dataset:

<p align = "center">
  <img width="80%" alt="image" src="https://github.com/user-attachments/assets/25bd6a65-fd6d-4a28-8fad-872e05c4759f">
</p>

- In all the cases, median is less than average, indicating that average sales is higher due to outliers.
- Globally, 75% of the titles have seen a sale of less than 420,000 units.
- And in all regions, 75% of the titles have seen a sale of less than quarter a million


**Pupular Genre**
One of the business questions was to identify popular genre. I created a pivot table in Excel and created the following bar graph to easily convey which genre were popular and which were not.
<p align ="center">
  <img width="80%" alt="image" src="https://github.com/user-attachments/assets/3b4fdcfe-3392-48ac-9fdd-9b59daed13c9">
</p>

Globally, the most popular genre was Action with a total sale of 555.85 million copies sold, the second was Shooter genre with total sale of 385.39 million copies sold, the least favourite genre was Puzzle with 10.06 million copies sold, and the second last was Strategy with a sale of 22.03 million copies sold.

Below are excerpts from the presentation file. The presentation file contains all of the results and recommendations. I recommend you to go through the video game market analysis presentation file to develop a complete understanding of the results.

One of the assumptions from the stakeholders was that the market share remained the same for the 4 different regions highlighed in the dataset. This was effectively debunked with the help of the following line chart. This helped in improving our understanding about the market.
<div align="center">
<img width="683" alt="image" src="https://github.com/b-N-I-R-A-V/Video-Games-Market-Analysis/assets/153047871/73fab36a-e7fb-46cc-9254-300083b62876">
</div>
Globally, the top 4 genres were Action, Shooter, Sports, and Role-Playing. In contrast, least preferred genres were Puzzle and Strategy.
<div align="center">
<img width="713" alt="image" src="https://github.com/b-N-I-R-A-V/Video-Games-Market-Analysis/assets/153047871/f8fd3165-0c1b-4e5c-8012-3cf3ee7cce59">
</div>


