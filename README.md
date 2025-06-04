# segmentation_xgb

**Using the Gradient Boosting method and segmentation analysis, I tried to predict new segments (0,1,2,3) for the new market 
and find out how new customers fit into the existing model.**

🔗 [Source:KAGGLE](https://www.kaggle.com/datasets/vetrirah/customer/data)
Licence: CC0: Public Domain


## 💡Key Findings

### 📊 Comparison of Segment Distribution
Growth of three segments (0,2,3 New_Proportion) — indicates a change in customer behavior in the new market
Segment 1 decreased—potential loss of this type of customer compared to the domestic market

![predicted segments](https://github.com/user-attachments/assets/c8b73115-63a4-4a15-b907-8f94e3214017)

### 📊 Key Factors Comparison
Of the new segments that grew overall (0,2,3), the second one is interesting, which, compared to the existing one, contains more customers with average and high purchasing power. It is therefore a segment that will welcome your business offers. For example, from the analysis you will learn that this segment is mainly made up of university graduates (93.9%), married people (97.5%), with an average age of 55. The distribution of the third segment is overall larger, but only the proportion of those with the lowest frequency of purchases has increased. We can also see that the new market (specifically segment 1) has a larger proportion of customers with high consumption (+11%), but its overall distribution is smaller, which means that this group will be less dominant in the new market. However, it is the right group to address with premium offers.

![key factors](https://github.com/user-attachments/assets/7cab898d-18b6-4f42-b411-2b49d8c25e7d)

### 📊 Feature Importance
New data shows that the factors that play the biggest role in defining segments are *age* and *consumption score.*
Age and consumption score are equally important and the most important in the original (existing) data as in the new one. This means that these factors have had and continue to have the greatest influence on which segment a customer falls into.
Family size has increased in importance—customer behavior may be different.

Summary: While *age* and *consumption score* are still key factors in determining customer segments, *family size* is gaining in importance. This suggests that family status may now have a greater influence on purchasing behavior.

![feature importance](https://github.com/user-attachments/assets/3f68b488-037a-481a-a929-957f852bbd9d)


🔗 [Read blogSLOVAK](https://mvalachova.com/blog/?blogPost=kto-su-vasi-potencialni-zakaznici-vyuzitie-strojoveho-ucenia-na-segmentaciu)




