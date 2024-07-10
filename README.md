# Starbucks-Challenge

## Situation

A recent study shows that introducing a Starbucks into a neighborhood with no cafes increases startups created over the next 7 years by 5—11.8%. Starbucks are "third places" where people spend a lot more time and meet others, more so than a typical cafe like Dunkin'.

![image](https://pbs.twimg.com/media/GRXoW2faQAAYl1i?format=jpg&name=medium)

Here you find data about founded companies per district and industry in Hamburg: [Data](https://www.statistik-nord.de/fileadmin/Dokumente/Statistische_Berichte/industrie__handel_und_dienstl/D_I_2_j_HH/D_I_2_j23_HH.xlsx).

Here you can find out in which district in Hamburg Starbucks stores are currently located: [Stores](https://www.starbucks.com/store-locator?map=53.598662,10.010921,11z).

## Challenge
Predict how many more companies (startups) will be founded per district and industry if a Starbucks were to open in the area.

## Tasks
1. Normalize the relevant data in an SQLite database.
2. Create a list that shows the predicted growth of startups per industry and district.
3. Visualize the data in a suitable way.

## Approach
1. Data from various sheets in the Excel file were considered. Business listings, new startups, business registrations and deregistrations by Hamburg districts were cleaned and analyzed.
2. Data was normalized and a database for the cleaned data was created in SQLite
3. The growth % of start-ups based on the above study(5—11.8%) was utilized to generate the maximum and minimum increase in the number of startups.
4. Data is visualized for maximum and minimum increase in the number of startups, business and other startups.

## Submission
- SQLite database: hamburg_starbucks.db
- A README.md file 
- Well commented code: hamburg_starbucks.ipynb
- The list of the predicted growth of startups.
