
# Market Basket Analysis
Market basket analysis is a technique used to identify associations and correlations between items frequently purchased together. It is essential for businesses as it helps uncover hidden patterns in customer buying behavior

## Problem Statement

To identify the correlation between different products sold at a grocery store to increase sales and create effective marketing strategies

## Report 

![](https://github.com/MandarSawant18/Power_BI_projects/blob/main/Basket%20Analysis/Screnshots/Basket%20Analysis%20Report.png?raw=true)

## Tech Stack

**Tool Used:** Power BI



## Key Metrics
    1. Obtain support, confidence, and lift values for all products
    2. Establish a network to understand the association between products.
    3. Develop a visual representation to explain the relationship between support and lift values of various products in a basket 




## Explanation
Explanation of technical jargons used

    1. Support – Indicates the frequency of products bought together
    2. Confidence – Indicates the direction of cross selling
    3. Lift – Indicates the strength of the relationship of products in a basket
    4. Basket = Products in one cart
       It is represented as Product1 – Product2 from here on

    All the baskets have been classified  into 4 categories for ease of understanding 
    Category 1: High Support – High Lift (Products which are purchased together frequently and have a strong relationship between them)
     Eg: If someone buys bread, there is a high possibility that they will also buy butter with it
    Category 2: High Support – Low Lift (Products which are purchased together frequently but do not have have a strong relationship between them)
     Eg: If someone buys bread, it does not necessarily mean the customer will also purchase butter
    Category 3: Low Support – High Lift (Products which are not purchased together frequently but have a strong relationship between them)
     Eg: Bread is not purchased frequently but whenever it is purchased, there is a high possibility the customer also buys butter with it
    Category 4: Low Support – Low Lift (Products which are neither purchased together frequently nor have a strong relationship between them)
     Eg: Bread and butter are neither bought frequently nor does purchasing either item influence the purchase of other item



## Analysis


- A total of 7835 orders have been executed by the grocery store.
- Products like yogurt-cream cheese, root vegetables – beef, whipped/sour cream- berries are commonly found in most of the baskets and fall into category 1
- Items like whole milk – tropical fruits, whipped/sour cream – chicken are frequently bought but they do not have any significant relationship between them. This a category 2 basket
- Eggs-butter, root vegetables – herbs, fruit juice - frozen vegetables are not bought together very often but have a strong influence on each other. They belong to category 3

## Recommendations

- The products within category 1 are strongly connected, and the main focus should be on maximizing the opportunities for cross selling and upselling. Additionally, as these products are frequently sold, it is important to effectively manage the inventory to guarantee that there is enough stock available
- Products from category 2 are already popular but low lift suggests these items do not influence the purchase of other items. Such products can be bundled with other complementary items to increase their appeal
- Since category 3 products have a strong association between them, but low support indicates work needs to be done to increase their visibility. This can be accomplished through efficient product placement, which requires rearranging the store layout and keeping these items together
- Finally for products in category 4, strategy should be devised to increase their awareness. This can be achieved by highlighting the product USP, offering free trials or samples of the products



## Related

Here are some related projects

[Power BI projects](https://github.com/MandarSawant18/Power_BI_projects)



## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.datascienceportfol.io/mandarsawant)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mandarsawant92/)



## Feedback

For any feedback or support, feel free to reach my Linkedin handle or write an email to smandar.work@gmail.com

