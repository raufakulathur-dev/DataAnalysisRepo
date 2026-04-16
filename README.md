
Olympic Games Dashboard

1. Project Overview 
	The primary goal is to analyze Olympic data (often covering 1896-2016 data) to uncover trends in athlete performance, country-wise medal successes, and gender participation.
2. Tools Used 
- Microsoft Excel 
- Power BI 
3. Dataset 
- Source: Sample Data downloaded from google.
- Data contains: Typical data includes athletes, sports, events, teams (NOC), and medals won.
4. Steps Followed 
- Cleaned data in Excel (e.g., removed blanks, formatted columns). 
- Used Excel formulas and Pivot Tables for basic analysis. 
- Imported cleaned data into Power BI. 
-Created Measures Like Total Medals, gold, Silver, Bronze.
- Built dashboards using charts, slicers, KPIs and Maps. 
5.Key Metrics (DAX)
-Total Medals: Total_ Medal =CALCULATE(COUNT(athlets[Medal]),FILTER(athlets,athlets[Medal]<>"NA"))
-Total Athletes: Total Athletes = CALCULATE (DISTINCTCOUNT (athlets[ID]))
-Gold Medals: Gold = CALCULATE(COUNT(athlets[Medal]),FILTER(athlets,athlets[Medal]="Gold"))
-Silver = CALCULATE(COUNT(athlets[Medal]),FILTER(athlets,athlets[Medal]="Silver"))
6. Key Insights 
-Identifies top-performing countries (e.g., USA, Soviet Union, Germany).
-Identifies top Five Athletes.
-Age group Between 20 and 30 won more medals.
-Tracks the growth of female participation over time.
-Shows the dominance of specific countries in particular sports. 
7.Dashboard Visualizations
-Top 5 Countries: Bar chart/Map showing countries by total medals.
-Medal Breakdown: Column chart for Gold/Silver/Bronze distributions.
-Athlete Performance: Table listing top athletes by medal count.
-Filters/Slicers: Interactive filters for Sport, Year, Season (Summer/Winter), and Gender. 








8.Screenshot

 





