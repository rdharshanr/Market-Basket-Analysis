# Market-Basket-Analysis
**Market Basket analysis**

Market basket analysis serves as a strategic data mining technique employed by retailers to boost sales by gaining profound insights into customer purchasing behaviors. This method involves the meticulous examination of extensive datasets, including historical purchase records, to unveil inherent groupings of products and identify items frequently purchased together.

By discerning these patterns of co-occurrence, retailers can make well-informed decisions to optimize inventory management, devise targeted marketing strategies, implement effective cross-selling tactics, and even refine store layouts to enhance customer engagement.

For instance, understanding the likelihood of customers purchasing bread alongside milk during a supermarket visit allows retailers to tailor marketing efforts, strategically cross-sell related products, and plan shelf space for optimal product placement. This insightful analysis empowers retailers to make data-driven decisions, ultimately fostering increased sales and improved customer satisfaction.

**Association Rule Mining**

Association rule mining is a method that uses pattern recognition to discover and quantify relationships between different but related items. A practical example is finding that Eggs and Bread are frequently purchased together. This discovery can boost sales by placing these items together, advertising to buyers of one to increase their likelihood of buying the other, or offering discounts for purchasing both at once.

An association rule like "if eggs are purchased, then the possibility of buying bread is __" can be represented as {eggs} -> {bread}. This approach is advantageous for its speed, suitability for small datasets, and minimal feature engineering requirements.

Three key measures in association rule mining are Support (popularity of an item), Confidence (probability of buying a consequent item given the antecedent), and Lift (how much more likely items are purchased together rather than independently).

For instance, if 5000 supermarket transactions include 500 bread purchases and 350 egg purchases, the Support for Bread is 0.1. Confidence for Bread -> Eggs is calculated as 30%, indicating a 30% likelihood of buying eggs if bread is purchased. The Lift score of 4.28 suggests a strong association between buying bread and eggs.

**Apriori**

Apriori algorithm uses frequent itemsets to get association rules,but on the assumptions that

All subsets of frequent itemsets must be frequent

Similarly incase of infrequent subset their parent set is infrequent too The algorithm works in such a way that a minimum support value is set and iterations happen with frequent itemsets. Itemsets and subsets are ignored if their support is below the threshold till there can’t be any removal.


