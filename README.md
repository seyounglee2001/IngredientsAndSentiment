# Can Ingredients Predict Sentiment in Food Recipes?

--

## Motivation / Purpose
- Digital media exposure, including social networking and online recipe platforms, can influence dietary choices by highlighting trends, popular ingredients, and user-generated recommendations (Reau, 2013). These exposures impact what individuals perceive as desirable or normative foods. This project aims to investigate how ingredients, nutritional content, and sentiment in online recipes relate to recipe popularity, providing insights into potential digital media influences on taste preferences.

--

## Methods

### Data Collection and Manipulation
- Recipes and reviews were collected from a popular online recipe sharing platform.  
- Data preprocessing included cleaning ingredient lists, standardizing nutritional content, and extracting sentiment scores from user reviews.

### Regression Analysis
- **Individual Ingredients:** Linear regression models were used to evaluate the association between the presence of specific ingredients and user sentiment.  
- **Ingredient Pairs:** Pairwise regression analyses were performed to examine interactions between commonly co-occurring ingredients on sentiment.

### GAM Regression Model
- A Generalized Additive Model (GAM) was applied to examine the relationships between nutritional content (carbohydrates, fats, protein, calories) and both sentiment and popularity metrics.  
- This approach allowed non-linear effects of nutritional components on user sentiment and recipe popularity to be captured.
  
--

## Conclusion / Results
- Positive sentiment was observed for commonly used baking ingredients, while spicy ingredients were associated with negative sentiment.  
- Recipe popularity was primarily influenced by carbohydrate content, and sentiment was affected by fat content.  
- Calories and protein showed less impact on sentiment and popularity, suggesting that specific macronutrients (carbs and fats) have a stronger role in shaping user preferences.  
- These findings align with prior research indicating that digital media exposure can shape taste preferences, particularly favoring sweet, fatty, and salty foods while reducing preference for bitter flavors (Sina et al., 2021).  

---
