# Predicting Recipe Popularity to Boost Website Traffic

<b>Background</b>  
The product team has presented a new challenge related to optimizing the selection of recipes displayed on our website's homepage. The goal is to leverage data science to predict which recipes will be most popular among our audience, thereby increasing overall website traffic and, subsequently, subscriptions.  

<b>Project Overview</b>  
You are tasked with developing a predictive model to forecast recipe popularity with high accuracy. The expectation set by the product team is ambitious: to correctly predict high-traffic recipes 80% of the time. Although this target might be challenging within the given timeframe, your objective is to approach it as closely as possible and suggest practical recommendations based on your finding.

<b>Key Objectives</b>   
1. Predictive Analysis
    - Develop a predictive model that identifies potential high-traffic recipes. The model should aim for an accuracy target of predicting popular recipes 80% of the time, understanding that this is an ambitious goal.
2. Data Exploration
    - Thoroughly analyze the available recipe and traffic data to identify patterns or features that can inform the predictive model. This may include recipe ingredients, preparation time, seasonality, previous traffic data, and any other relevant factors.
3. Strategic Recommendation
    - Provide actionable recommendations based on your analysis. This could include suggestions for recipe selection criteria, adjustments to the prediction model, or other strategic insights that could help in choosing high-traffic recipes.
  
<b>Meta Data</b>  
The product manager has tried to make this easier for us and provided data for each recipe,
as well as whether there was high traffic when the recipe was featured on the home pag  .
Don’t forget to double check the data really does match what they say - it might not  
| Column Name   | Details                                                                                           |
|---------------|---------------------------------------------------------------------------------------------------|
| recipe        | Numeric, unique identifier of recipe                                                              |
| calories      | Numeric, number of calories                                                                       |
| carbohydrate  | Numeric, amount of carbohydrates in grams                                                         |
| sugar         | Numeric, amount of sugar in grams                                                                 |
| protein       | Numeric, amount of protein in grams                                                               |
| category      | Character, type of recipe. Recipes are listed in one of ten possible g  roupings ('Lunch/Snacks', 'Beverages', 'Potato', 'Vegetable', 'Meat', 'Chicken', 'Pork', 'Dessert', 'Breakfast', 'One Dish Meal'). |
| servings      | Numeric, number of servings for the recipe                                                        |
| high_traffic  | Character, if the traffic to the site was high when this recipe was shown, this is marke“High”. |