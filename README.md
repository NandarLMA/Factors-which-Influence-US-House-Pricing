# Factors-which-Influence-US-House-Pricing

##Problem Statement : Build a model using publicly available data for key NATIONAL Demand and Supply Factors that could influence US home prices. Explain how those factors impacted home prices over the last 20 years.


## Supply Data

- Building Permits
- New Owned Housing Unit
- House Sold Unit
- Monthly New House Supply
- Construction Spending

#### Data Distribution

- The monthly new house supplies are mostly less than 6 Unit.
- Most of the Constructions spend less than 600,000 M.
- Construction Permits peak at around 1300 Unit.
- Most of the new house in the dataset sold are between 250 and 750 Unit.
- House prices are mostly less than 200 Unit.

#### The Correlation 

- There is a strong and positive linear relationship between House Pricing and Construction Spending amonut. (85%)
- The relationship between House Pricing and Building Permits is approximately 30%.
- There is a weak linear relationship between House Pricing and monthly house supply data. (8%)
- New owned housing unit has around 25% linear relationship with House Price. 

#### Regression Model

Tested with 6 different algorithms and Polynomial Regression model was chosen as a final model for the Supply data.
Since it has lowest error rate (0.02) and highest testing accuracy (98%).

## Demand Data 

- GDP
- Unemployment rate
- Currency exchange rate
- Mortgage rate
- Disposable Income 
- Interest rate

#### Data Distribution

- GDP peaks at 16000.
- Unemployment rate peaks at around 5 unit.
- Disposable Personal Incomes are mostly less than 15000.
- Most of the Currency Exchange rates are between 10 and 14 units.
- Most of the Interest rate is less than 4 unit.

#### The Correlation
- There is a strong and positive linear relationship between House Pricing and GDP. (87%)
- Disposable Personal income and House Pricing also has a positive linear relationship (86%)
- The relationship between House Pricing and Currency Exchange rate is approximately 20% in positive way.
- There is a negative linear relationship between House Pricing and unemployment rate. (-24%)
- Interest rate has around 10% negative linear relationship with House Price. (-11%)

#### Regression Model

Tested with 6 different algorithms and XGB model was chosen as a final model for the Demand data.
Since it has lowest error rate (0.01) and highest testing accuracy (99%).
