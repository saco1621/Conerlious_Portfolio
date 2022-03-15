# Conerlious_Portfolio
Data Analytics Portfolio

# [Project 1: Cyclistic Bike share - Case study](https://rpubs.com/Corny26Saga/871934) 
* Made recommendations on _**How do annual members and casual riders use Cyclistic bikes differently?**_ business task for a company called Cyclistic. 
* I defined the problem and developed a business task based on the company's problem statement. 
* Data was collected from [Motivate International Inc](https://divvy-tripdata.s3.amazonaws.com/index.html). 
* Cleaned the data using R language and Excel. 
* Created visualisations using RStudio. 

    ![](https://imgur.com/BMzgXmI)


# [Project 2: Data Analysis Salary Estimator](https://saco1621.github.io/da_salary_proj/)
* This project is about a tool i created which can be used to estimate data analyst salaries. The tool can be used by data analysts to negotiate their incomewhen they get new jobs.
* The tool features the expected data analyst skill and shows how companies value them for a certain income. I used Python, Tableau, AWS, Spark, R, SQL and R.
* Made use of Random Forest, Lasso and Linear Regressors using GridsearchCV to get the best model for the tool. 
* Finally, i built a client facing API using Flask. 


#### Palette
```{r}
cmap = sns.diverging_palette(220,10,as_cmap = True)
sns.heatmap(df[['age','avg_salary', 'Rating', 'description_len', 'number_comp']].corr(),
            vmax =.3, center = 0, cmap = cmap, square = True, linewidths =.5, 
            cbar_kws = {"shrink": .5})
```
   [Imgur](https://imgur.com/BMzgXmI)
  
  ![](https://imgur.com/BMzgXmI)

#### Age, Average Salary & Rating Box Plot


  ![](https://imgur.com/LH6df3C)

#### Average Salary vs Siniority Pivot Table

   ![](https://imgur.com/JkGegIy)


