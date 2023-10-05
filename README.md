# Cost-Effective whiskey recommendation algoruthm
## ABSTRACT
> Whiskey is an appealing option for many people, with a wide variety of brands and different characteristics. However, whiskey's high alcohol content makes it difficult to enjoy its natural flavors, and the taste varies with skill and experience. For this reason, it can be difficult to get whiskey recommendations from others, as well as to find a whiskey that suits your personal taste. Moreover, the price of whiskey is quite high compared to the alcoholic beverages commonly consumed by Koreans, so the burden of failure is high.
In this study, we propose an algorithm that recommends cost-effective whiskey using content-based filtering. First, the algorithm finds N similar data in the database by inputting the user's quantified taste expression data and a Taste Note describing the desired taste. The price, rating, and similarity of the found whiskey data are used to calculate the R-value (price/benefit ratio). Sort the N neighbors in descending order by R-value and recommend the whiskey with the highest R-value at the top of the list. We conducted diverse user recommendation scenario simulations and observed the algorithm's effectiveness in suggesting budget-friendly whiskey options. This makes it easier for many people to find whisky that matches their taste and palate at a lower cost, and helps them make a successful choice by minimizing the chance of failure in whisky selection. This algorithm can be applied not only to whiskey but also to various other areas where people seek different flavors.

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
