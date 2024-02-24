# NCAA Financials
**Dataset:** https://data.world/jbaucke/2021-w1-power-bi-wow-ncaa-financials

NCAA athletic department expenses and revenues by year.

### Week 1
1. cleaned data set with only **teams** from the Football Bowl Division. To do this, in the FBS Conferences field exclude the FBA Totals and null values.
2. Within NCAA Subdivision, remove all Conference Medians.

### Week 2
1. created a new field Total Profits = calculated by subtracting Total Expenses from Total Revenues and then adding back in Excess Transfers Back.
2. Created KPI dashboard that includes 3 high level measures: Total Revenues, Total Expenses, and Total Profits.
![image](https://github.com/manaswipatil/Workout-Wednesday/assets/50437663/a98b05b2-abda-4d22-b6fc-b00cd41dfff1)

3. included a trend line for each category and breakdown by conference.

**Summary View**
![image](https://github.com/manaswipatil/Workout-Wednesday/assets/50437663/c0f0f704-1e32-4d0b-bca8-daa2d47dced7)

### Week 3
1. Added a slicer for [Year] to the report.
2. Edited Interactions for the slicer to have it only slice the KPIs and bar charts (not trends)
3. Edited Interactions of the Conference breakdowns so that they filter the KPIs and Trends on click.

**How much money the MAC conference made in 2016?**
Profit : (- $8,293,274)  Revenue: $364,246,188  Expenses: $372,539,462

![image](https://github.com/manaswipatil/Workout-Wednesday/assets/50437663/15092603-0ed7-4f74-91ed-cc9e47398583)

### Week 4
- Created a new tab called “School View.” Replace the [Conference Abb] fields in your bar charts with [School Abb].
- Created drill through from your **Summary View** tab to your **School View** tab.
- Added a card to allow users to know what Conference they are viewing in the School View.

**Who contributed most to the MAC losing so much money in 2016?**
TOL : (- $5,376,238)
followed by KENT, BALL, BGSU, AKR, NIU

![image](https://github.com/manaswipatil/Workout-Wednesday/assets/50437663/74b6c167-bbed-4c1d-8bbe-34e108e8f6b5)





