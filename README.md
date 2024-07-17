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


**Pupular Genre:**
One of the business questions was to identify popular genre. I created a pivot table in Excel and created the following bar graph to easily convey which genre were popular and which were not.
<p align ="center">
  <img width="80%" alt="image" src="https://github.com/user-attachments/assets/3b4fdcfe-3392-48ac-9fdd-9b59daed13c9">
</p>

Globally, the most popular genre was Action with a total sale of 555.85 million copies sold, the second was Shooter genre with total sale of 385.39 million copies sold, the least favourite genre was Puzzle with 10.06 million copies sold, and the second last was Strategy with a sale of 22.03 million copies sold.

**Global Average Sales For Top 4 Genre:** I also looked at recent trend of the top 4 most popular genres.
<p align = "center">
  <img width="80%" alt="image" src="https://github.com/user-attachments/assets/20c7f3aa-e6b6-47db-baf2-f0d4207b151f">
</p>

Following were my observations:
- Among Action,Shooter,Role-playing, and Sports, average sales of shooter were highest with staying above half a million units and average sales for Sports were second highest with approximately 380 thousand units in 2016.
- Average sales for action genre were least among the top for genres with about 170 thousand units.
- The average sales foraction, sports, and role-playing genre decreased overtime.

I was interested then in understanding the cause behind popularity of action genre. I hypothesized that maybe there are just more number of titles in Action genre.
<p align = "center">
  <img width="80%" alt="image" src="https://github.com/user-attachments/assets/32004fe2-da5b-4d27-bbc6-2237e26bdf72">
</p>
This graph explained why action genre was popular had so many sales.
- There were 2327 titles under Action genre, more than 3 times the number of titles released under Shooter genre.
- Shooter genre had only 723 titles.

## Marketshare of Geographical Regions
I then shifted my attention to understanding global trends of sales.
<p align ="center">
  <img width="80%" alt="image" src="https://github.com/user-attachments/assets/d0f721b5-b429-448f-a095-04f7f25b8d4c">
</p>

- The graph shows an increase in sales for all regions upto year 2008- 2009.
- Then sales in all regions declined dramatically in North America and Europe.

If we look at proportion of market occupied by these geographical regions we have the following observations to make:
<p align = "center">
  <img width="80%" alt="image" src="https://github.com/user-attachments/assets/aa31b5b8-0145-4264-a868-39f17f73f15c">
</p>
Sales in North American region had dropped from 93% to 32% whereas sales in Japan and Europe had increased. Moreover, present market share (2016) of Europe (38%) and North America (32%) is closer than ever in history.

### Competition in this Market
I then looked at the market competition and identified the top 10 competitors.
<p align = "center">
  <img width="80%" alt="image" src="https://github.com/user-attachments/assets/aa128a3a-9027-43cf-b224-bfef331dd4d0">
</p>

In the past 10 years, Nintendo was the highest selling publisher (830.96 million), followed by Electronic Arts (660.98 million), followed by Activision (522.09 million), followed by Ubisoft (390.12 million).

**Sales of Top 4 Publishers:**
If we look at the sales of top 4 competitors in the last 10 years, we have the following observation:
<p align = "center">
  <img width="80%" alt="image" src="https://github.com/user-attachments/assets/9e694171-5ebe-41ce-9306-8c7020f0519f">
</p>

- Sales for each of them fell considerably. Highest selling publisher, Nintendo, became the least selling publisher in 10 years span from 205.61 million sales to just 3.67 million sales.


**Popular Genres for Nintendo**
Finally, I focused on the popular genres for Ninetendo. 

<p align = "center">
 <img width="80%" alt="image" src="https://github.com/user-attachments/assets/b61a5027-33eb-4dfb-81cf-24af2f63a770">
</p>

- The total sales figure for Nintendo was 830.96 million between 2006-2016, out of which more than half the sales (474.39 million) came from three genre namely, Sports, Platform, and Role-Playing.
- As we have seen earlier, Sports and Role-Playing were among the top 4 genre by sales.


## Conclusion and Recommendations

### Revised Understanding

We have the following fact that has given us an improved understanding of the Video Games Market:
- Considering the data presented it challenges the assumptions we made earlier that all the regions hold the same share of market. North America holds 32%, Europe 38%, Japan holds 19%, and other holds 11%.
- Action, Shooter, Sports, and Role-playing were the top selling genres. Action having the maximum number of sales due to more titles released and Shooter had the maximum average sale for a title.
- Nintendo, Electronic Arts, Activision, and Ubisoft has been the top publishers in last 10 years.
- Nintendo lost he most market share, sales dropped by approx. 98.2%. Sports, Platform, and Role-Playing were the top selling genre for Nintendo.

### Recommendations

I have three recommendations for GamesCo. They are as follows:
- We recommend that GameCo focus more on Action, Shooter, Sports, and Role-playing genre as these were top selling genre with special attention to shooter genre.
- GameCo could also focus more on genre such as Sports and Role Playing as they were top selling for Nintendo to capitalize on the opportunity.
- Europe and North America are having most of the share of global market and more attention to these markets could be given.

I hope you have found something useful. If you have any questions or suggestions for me, feel free to reach out via my [LinkedIn](https://www.linkedin.com/in/nirav-bariya/) profile or [email](mailto:nkb.bariya@gmail.com) me.  Have a great rest of the day!
