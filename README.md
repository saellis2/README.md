## ICA #4
SQL to Business Insights

## Description
3 questions under the dataset.sat_scores table which includes teachers, schools, hours studied, and test scores for sat writing, verbal, and math. 

## Question 1
How does hours studied affect the math score? 

```sql
Select sat_math, hrs_studied
from datasets.sat_scores
where hrs_studied notnull 
order by hrs_studied ASC 
```
![ICA-4](Visualizations/Graph1.png)
