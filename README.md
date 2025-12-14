<div align="justify">
<h1> <b> Statistical analysis of the impact of the introduction of the "Safe Credit 2%" program on apartment prices in Poland </b> </h1>
<h2> This project aimed to show how the government's "Safe Credit 2%" programme has affected housing prices in Poland. The analysis used data on housing prices from 2010 to 2022 in the 5 largest cities of Poland, taken from the GUS website, as well as data for 2023 on housing prices from Kaggle. The research used multiple regression analysis and repeated measures analysis. </h2>
</div>


> * Datasets sourses:
>   - _GUS:_ [DBW](https://dbw.stat.gov.pl/baza-danych)
>   - _Kaggle:_ [Apartment Prices in Poland](https://www.kaggle.com/datasets/krzysztofjamroz/apartment-prices-in-poland)
> 
> * Used technologies:
>   - Python | Jupyter | VS Code
> * Used libraries:
>   - pandas | numpy | matplotlib | statsmodels

## Data visualization
* Yearly price change per square meter (2010 - 2023)
![1](https://github.com/AnnnaMm/Statistical-analysis-of-the-impact-of-the-Safe-Credit-2-program-on-apartment-prices-in-Poland/blob/main/DV/2010-2023.png)
* Monthly price change per square meter (08.2023 - 04.2024)
![2](https://github.com/AnnnaMm/Statistical-analysis-of-the-impact-of-the-Safe-Credit-2-program-on-apartment-prices-in-Poland/blob/main/DV/2023.png)

## Results
### Multiple regression analysis
* Summary of Model 1 including square meters, number of rooms, and year of construction:
![3](https://github.com/AnnnaMm/Statistical-analysis-of-the-impact-of-the-Safe-Credit-2-program-on-apartment-prices-in-Poland/blob/main/MRA/1.png)
* Summary of Model 2 including square meters, number of rooms, and year of construction:
![4](https://github.com/AnnnaMm/Statistical-analysis-of-the-impact-of-the-Safe-Credit-2-program-on-apartment-prices-in-Poland/blob/main/MRA/2.png)
* Summary of Model 3 including square meters, number of rooms, and year of construction:
![5](https://github.com/AnnnaMm/Statistical-analysis-of-the-impact-of-the-Safe-Credit-2-program-on-apartment-prices-in-Poland/blob/main/MRA/3.png)

### Repeated measures analysis
* Mixed model analysis results for the base year 2010:
![5](https://github.com/AnnnaMm/Statistical-analysis-of-the-impact-of-the-Safe-Credit-2-program-on-apartment-prices-in-Poland/blob/main/RMA/all_do2010.png)
* Rate of change in price per square meter compared to 2010:

| Year                                                                | 2011   | 2015   | 2020   | 2023   |
| ------------------------------------------------------------------- | ------ | ------ | ------ | ------ |
| Percentage change price/square meter                                | 1,55%  | -3,75% | 28,09% | 68,07% |
| Percentage change price/square meter (compared to the previous year)| -      | 1,03%  | 10,11% | 6,46%  |


* Mixed model analysis results for the base year 2022:\
![7](https://github.com/AnnnaMm/Statistical-analysis-of-the-impact-of-the-Safe-Credit-2-program-on-apartment-prices-in-Poland/blob/main/RMA/all_do2022.png)
* Rate of change in price per square meter compared to 2022:

| Year                                                                | 2011    | 2015    | 2020    | 2023    |
| ------------------------------------------------------------------- | ------- | ------- | ------- | ------- |
| Percentage change price/square meter                                | -36,66% | -39,03% | -26,31% | 6,46%   |
| Percentage change price/square meter (compared to the previous year)| -       | 0,0103  | 0,06865 | 0,1762  |


* Mixed model analysis results for the base year 2023(august):
![7](https://github.com/AnnnaMm/Statistical-analysis-of-the-impact-of-the-Safe-Credit-2-program-on-apartment-prices-in-Poland/blob/main/RMA/mnth.png)
* Rate of change in price per square meter compared to 08.2023:

| Month                                                               | 09.2023 | 12.2023 | 04.2024 |
| ------------------------------------------------------------------- | ------- | ------- | ------- |
| Percentage change price/square meter                                | 2,28%   | 10,70%  | 14,83%  |
| Percentage change price/square meter (compared to the previous year)| -       | 4,76%   | 0,36%   |



## Conclusions
  From the results of the analysis we can conclude that the programme ‘Safe Credit 2%’ programme had a significant impact 
on the price of housing in Poland - prices per square metre increased at a per square metre have increased at a relatively 
fast pace, compared to the annual growth trends. Multiple regression analysis reveals the impact of specific 
factors on property price formation and is useful for for research on data of this type, although it would be necessary 
to improve/expand this model in future research. Repeated measures analysis appropriately applied to data of this form and 
showed changes in the dependent variable taking into account the time scale. Its results appear to be in line with reality. 
From the analysis given, we can read that the increase in price per square metre in 2023 compared to 2022 
is approximately <ins>6.46 %</ins>, while the the average percentage increase in price per square metre over the duration of the
credit programme is <ins>9.74 %</ins>, which leads to the conclusion, that the investigated credit programme 
has significantly influenced the increase in housing prices during its during its operation. 
The increased availability of mortgage loans has contributed to an increase in demand for housing, 
which has driven up prices in the most desirable locations.



> [!IMPORTANT]
> For full access to the code and additional information, contact the repository owner -> annamamch17@gmail.com .
