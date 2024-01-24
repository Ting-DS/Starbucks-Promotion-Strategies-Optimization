# Starbucks Promotion Strategy Optimization
#### All Analysis Insights in My Medium Article: [After A/B Testing: Optimize a Advertising Promotion Strategy by Audience Targeting](https://medium.com/@LobsterTing/optimize-a-promotion-strategy-by-a-b-testing-and-audience-targeting-17b7ec49c55b)
<div align="center">

  <img src="https://github.com/Ting-DS/Starbucks-Promotion-Strategies-Optimization/blob/main/png/starbucks-sign.jpeg" width="60%">

</div>

## Background

A/B testing has achieved practical significance for boosting sales by promotion strategy, what next?

When a company wants to test whether a new product or advertising strategy will increase customer engagement, they often do so by designing and conducting A/B testing within a certain customer segment. The variations in A/B testing metrics (such as user engagement, purchase conversion rates, average click-throughs rates, etc.) are analyzed, and if there is a significant increase, it proves that the new feature or strategy is effective. The next step might seem to be rolling out the new feature/product/strategy to all customer groups or the entire platform, but that is a complete mistake!


<div align="center">

  <img src="https://github.com/Ting-DS/Starbucks-Promotion-Strategies-Optimization/blob/main/png/target_client.png" width="60%">

</div>


Launching new products/advertising strategies/features requires investment in terms of money and time. The results of A/B testing only prove the effectiveness of intervention, but if this intervention is blindly applied to all future customers, the company may not only fail to make a profit but also incur losses! The correct approach is to establish new business metrics while considering costs and benefits. These metrics represent the profit growth that the company expects to achieve through the launch of new features/strategies.

Detailed analysis should be conducted on experimental data from A/B testing, including exploring changes in customer behavior, clustering characteristics, feature analysis, statistical modeling, etc. Ultimately, it is necessary to accurately determine the characteristics of customer groups that are more sensitive to interventions and develop customer segmentation strategies. By evaluating the profitability ratio of various strategies using new core business metrics, targeted advertising strategies can be selectively deployed to precisely positioned customer groups instead of covering all groups. This will maximize enterprise profits!

## Installation

 - Anaconda distribution of Python.
 - Python 3.*.

## File Descriptions

The initial dataset is a task prepared by [Starbucks](https://www.starbucks.com/) for DS candidates, with approximately 120,000 data points divided into training and testing files in a ratio of 2:1. In the simulation A/B testing experiment, we conducted tests on advertising promotions aimed at attracting more customers to purchase a specific product priced at $10.

1. training.csv: results of the simulated A/B test experiment.
2. Test.csv: test evaluation metric of several promotion strategies.
3. test_strategies.py: test data script.
4. Promotion_Optimization_Strategy.ipynb: for A/B Testing Post-Analysis and strategies optimization.

## Results
<div align="center">

  <img src="https://github.com/Ting-DS/Starbucks-Promotion-Strategies-Optimization/blob/main/png/Results.png" width="100%">

</div>

 - Analyze the results of AB testing and determine that promotional strategies should be released based on the significant improvement in purchase conversion rate.
 - Infer the meaning of features through business knowledge, feature's behavior, distribution and correlation analysis; And perform reasonable feature engineering.
 - Optimize a promotion strategy by targeting the right clients to maxmize the business metric Incremental Response Rate (IRR) and Net Incremental Revenue (NIR)

## Acknowledgements

Thank you [Starbucks](https://www.starbucks.com/) for providing the A/B Testing experimental data!
