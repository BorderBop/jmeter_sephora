# jmeter_sephora
Test script development

Tool: Jmeter
Application: www.sephora.com

##Scenario:

|Transaction Description and Sequence	| Probability | Comment |
| ----------- | ----------- | ----------- |
| Home Page	| 100	| |
| Open Random Category from “Fragrance” Menu |	25 | 100 % of visits	|
| Open Random Category from “Tools & Brushes” Menu	| 25	| |	
| Search Products by Keyword |	50	||	
| Open Random Product If Found Any	| 80	| 80% of visits |
| Add Product to Cart |	40 |	40% of visits |

•	Think time 5...10 seconds.
•	New user at each iteration.
•	A product should be available before adding to Cart.
•	Average shopping cart size – 4 items.
•	Average user session duration – 4 minutes.

##Set of keywords for search:
| Keyword	Probability | % |
| ----------- | ----------- |
| Fragrance |	30 |
| Lipstick |	20 |
| Color |	20 |
| Shampoo |	10 |
| Skin	| 10 |
| Eye	| 5 |
| Face |	5 |

""User Browser Statistics:
| Browser |	Probability, % |
| ----------- | ----------- |
| IE6	 | 25 |
| IE7 |	5 |
| IE8 |	10 |
| IE9 |	20 |
| IE10 |	10 |
| IE11 |	30 |

If something from the scenario above can’t be implemented then this may be skipped with a comment.

Script should be ready to run. (No testing/reporting are required. Pure Jmeter scenario should be provided)

