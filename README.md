# Python-EDA-StackOverflow-developer-survey-dataset
Welcome to the GitHub repository for the analysis of the Real Estate dataset. In this project, we delve into the rich data provided by 10Alytics aiming to uncover insights that shape the real estate market.

## Table of Contents
- [Project Objective](#Project-objective)
- [Data Scource](#data-source)
- [Data Processing](#data-processing)
- [Evaluation Metrices](#evaluation-metrices)
- [Key Insights](#key-insights)
- [conclusion and recommendations](#conclusion and recommendations)

## Project Objective
The dataset used for this analysis is the  dataset, which can be accessed here. The dataset provides a comprehensive view of the real estate community, covering factors driving the sales price of houses. This project was carried out to understand the factors on which the pricing of houses depends. Specifically, factors affecting the pricing of homes.

## Data Source
The dataset used for this analysis was obtained from 10Alytics.

## Data Processing
The dataset undergoes a rigorous data processing phase to ensure accuracy and relevance in our analysis. Python, along with powerful libraries like Pandas, is employed to clean, preprocess, and structure the data. This step is crucial in preparing the dataset for meaningful exploration and interpretation.

## Evaluation Metrices
In this analysis, we utilize various metrics to evaluate and interpret the findings. Each factors in the dataset was analyzed critically to find existing relationship with sales price.

## key Insights
1. Sales price: The data visualization for the salesprice feature is positively skewed. Outliers are observed especially at price above 500000.
2. 79% of the houses fall under the RL zone while the C zone has the least percentage (0.7%) of houses.
3. There appears to be a positive relationship between the sales price and the year the house is built. The newer the house the more expensive. Although there are some outliers, with some older houses being more expensive. The year the house is built may be a good predictor of the cost of the house.
4. Houses from the FV region tend to be the most expensive followed by region RL. The least expensive region is the C region. Houses that are in the C regio tend to be the cheapest houses with a threshold of 100000.
5. Overall quality of house have a positive coorelation with sales price.
6. LotFrontage: The histogram is positively skewed. It has a longer tail extending towards the right side, indicating a higher frequency of houses with lower prices.Fewer houses have high lot frontage above 150.
7. Land slope: Most of the houses (1382) have gentle slopes.
8. Street Type: 99% of the houses have pavement type of street with just 1% having gravel type of street
9. Utilities: - 99.9% of all houses have all public utilities installed in them.
10. LandContour: Most of the houses sold are near flat level properties
11. Regular and slightly irregular shapes houses are the prevalent in the real estate market
12. Inside (1052) and Corner (263) lot are the top 2 Lot configuration types of houses in the market.Only 4 of the houses have frontage on the 3 sides.
13. The top and least conditions (1) are houses with normal proximity to various conditions(Norm - 1260) and houses (RRNe - 2) within 200' of East-West Railroad. The same is observed for condition2.
14. The highest and lowest MSSubClass in the market are 20 (1-STORY 1946 & NEWER ALL STYLES) and 40 (1-STORY W/FINISHED ATTIC ALL AGES).
15. LotConfig: CulDSac house typeb have the highest sales price while inside house types have the lowest sales price. Although inside house type lotConfig have high number of outliers with prices as high as 600000 while corner house type config have few outliers with prices above 700000.
16. Condition1:PoSA, PosN and PRae have the highest sales price while the lowest is Artery.
17. Condition2: RRNn have the lowest sales price while PosA have the highest sales price.
18. Lotshape: IR2 have the highest median value followed by IR3 but IR3 have lager variability in salesprice. Reg lot shape houses have the lowest sales price. Although, Reg and IR1 house types have a lot of outliers with extreme sales price.
19. MSSubClass: 2 storey buildings 1446 & newer (60) have the higehst sales price while 1 storey 1945 and older have the lowest sales price.
20. Street: The distribution of sales prices for properties with pavement access is much wider than the distribution for properties with gravel access. This suggests that there is a greater range of prices for properties with pavement access.The median sales price for properties with pavement access is higher than the median sales price for properties with gravel access. This suggests that, on average, properties with pavement access sell for more than properties with gravel access.There is some overlap between the two distributions. This means that there are some properties with gravel access that sold for more than some properties with pavement access.
21. Utilities: Two major type stands out. Normal and NoSeWa. Overall, houses with normal public utilities have a higher sales price.
22. LandContour: Houses with HLS land contour have the highest sales price while Bnk have the lowest prices. Although there are some outliers.
23. Landslope: Sev and Mod type of houses have the highest sales price. Gtl type of houses have the lowest salesprice. Although Gt1 have a lot of extreme outliers with some outliers having salesprice higher than 700000.
24. There is a weak positive correlation between sales price, lot area and lot frontage.

## Conclusion and Recommendations
In conclusion, some of the identified factors that drive the sales price of hiuses in the real estate community are: lot are, lot frontage, year built, overall quality, conditions, street.
