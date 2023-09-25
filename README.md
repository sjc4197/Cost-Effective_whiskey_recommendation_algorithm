# Cost-Effective whiskey recommendation algoruthm
## ABSTRACT
> Whiskey is an appealing choice for many people due to its diverse brands and unique characteristics. However, its high alcohol content makes its taste highly subjective, requiring expertise and multiple experiences to appreciate fully. This not only makes it challenging to seek whiskey recommendations from others but also to find a whiskey that aligns with one's personal taste preferences. Moreover, the price of whiskey is considerably higher compared to the alcoholic beverages typically consumed by Koreans, adding a significant burden in terms of potential disappointment.
In light of these challenges, our study has developed an algorithm that utilizes content-based filtering to recommend cost-effective whiskeys. To do this, we begin by collecting quantified data on taste preferences from users, along with their 'Taste Notes' describing their desired flavor profiles. We then retrieve N similar data entries from the database based on this information. Utilizing price, rating, and the similarity of identified whiskey data, we calculate an R-value. Subsequently, we sort the N neighbors in descending order based on the R-value and recommend the whiskey that offers the greatest benefit in terms of the price-performance ratio as the top choice.
Through scenario-based algorithm testing and simulations, we have successfully provided recommendations for budget-conscious users seeking their desired whiskeys. This approach aims to facilitate the discovery of whiskeys that align with one's preferences and tastes at an affordable cost, thereby minimizing the likelihood of selecting an unsatisfactory whiskey. Additionally, it is expected that this algorithm could find applications in various fields where diverse flavors are enjoyed, thus demonstrating its potential for broader relevance.

<hr>

![알고리즘 순서도 final version](https://github.com/sjc4197/Cost-Effective_whiskey_recommendation_algorithm/assets/63084925/75f42388-2c8c-44d4-83b8-26e2db7afd77)
Algoruthm overview

<hr>
## Scenario test
- Recommendation approach : Emphasis on similarity![image](https://github.com/sjc4197/Cost-Effective_whiskey_recommendation_algorithm/assets/63084925/808ac087-2ba7-4c73-b524-eba89c59290b)


