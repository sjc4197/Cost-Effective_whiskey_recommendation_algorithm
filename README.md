# Cost-Effective whiskey recommendation algoruthm
## ABSTRACT
> Whiskey is an attractive option for many people, offering a wide variety of brands and unique characteristics. However, the high alcohol content of whiskey can make it challenging to fully savor its natural flavors, and the taste can vary depending on one's expertise and experience. Consequently, obtaining whiskey recommendations from others and finding a whiskey that perfectly suits your personal taste can be quite challenging. Furthermore, whiskey tends to be relatively expensive compared to the more commonly consumed alcoholic beverages in Korea, adding to the pressure of making the right choice.
In this study, we propose an algorithm that recommends cost-effective whiskeys using a content-based filtering approach. Initially, the algorithm identifies N similar data entries in the database based on the user's quantified taste expression data and a Taste Note describing the desired flavor profile. It then factors in the price, rating, and similarity of the identified whiskey data to calculate the R-value (price-to-benefit ratio). The N neighbors are sorted in descending order of R-value, with the whiskey having the highest R-value recommended at the top of the list. To assess the algorithm's performance, we devised and simulated user recommendation scenarios in various situations. The results indicated that the algorithm effectively recommended whiskeys within lower price ranges, making it easier for many people to discover whiskeys that align with their taste preferences and budgets. This minimizes the chances of making an unsuccessful choice when selecting whiskey. Notably, this algorithm is not limited to whiskey and can find applications in various domains where people seek enjoyment through diverse flavors.

<hr>

![알고리즘 순서도 final version](https://github.com/sjc4197/Cost-Effective_whiskey_recommendation_algorithm/assets/63084925/75f42388-2c8c-44d4-83b8-26e2db7afd77)
Figure 1. Algoruthm overview

<hr>

## Scenario test

### Scenario #1 input data
> - Recommendation approach : Emphasis on similarity
> - Taste note : sweet and fresh flavors like apple, orange, lemon
> - Rich :8
> - Full bodied : 7
> - Smoky : 2
> - Sweet : 5

### Result
> <img width="600" alt="image" src="https://github.com/sjc4197/Cost-Effective_whiskey_recommendation_algorithm/assets/63084925/27f106bc-9827-4be4-ae1a-abb1810bf256"><br>
> Figure 2. Scenario #1 R value of neighbors
> - Recommended whiskey : Tullibardine 12 Year
> - Kind of whiskey : Single Malt
> - ABV : 40.0
> - AGE : 12 Year
> - Rating : 3.72
> - Total similarty : 0.6898316481248351
> - Cost level : 2(25$ ~ 50$)<br>
> <img width="600" alt="image" src="https://github.com/sjc4197/Cost-Effective_whiskey_recommendation_algorithm/assets/63084925/e3c91e3d-336e-4512-8113-8a0f78a3ea0d"><br>
> Figure 3. Result word cloud

<hr>

### Scenario #2 input data
> - Recommendation approach : Emphasis on rating
> - Taste note : Highlighting aged flavors like leather and wood, and smoky, sweet
> - Rich :4
> - Full bodied : 6
> - Smoky : 9
> - Sweet : 8

### Result
> <img width="600" alt="그림1" src="https://github.com/sjc4197/Cost-Effective_whiskey_recommendation_algorithm/assets/63084925/9812226f-4972-4b4e-993c-a8bbd1ba0c0d"><br>
> Figure 4. Scenario #2 R value of neighbors
> - Recommended whiskey : Willett Pot Still Reserve Bourbon
> - Kind of whiskey : Bourbon
> - ABV : 47.0
> - AGE : NAS
> - Rating : 3.71
> - Total similarty : 0.6676571485915604
> - Cost level : 2(25$ ~ 50$)<br>
> <img width="600" alt="그림1" src="https://github.com/sjc4197/Cost-Effective_whiskey_recommendation_algorithm/assets/63084925/ec9405e0-44ee-4ecc-8a28-b0d35285a0dd"><br>
> Figure 3. Result word cloud
