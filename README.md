# Data-Driven Marketing for Retail
#### Unleashing the power of transaction data for an Italian retail chain
(Dec 2021)

### General Information
This project's incipit was to use a retail chain transaction dataset to create value out of it for the client company. This dataset contained around 300k transactions on a 3-month period: by analysing them, we drafted some recommendations with the goal of boosting profits while increasing customer satisfaction. The main result of the analysis is a data-driven loyalty program that is expected to increase retention and, thus, the company profits.

### Data
Each transaction is described by:
- customer ID (if the customers were part of the loyalty program)
- store ID
- date and time of purchase
- product ID
- product price
- promotion

### Outputs
The output of the projects were two presentations: 
1) Marketing_manager_slides: this set of slides is supposed to carry not only the final recommendations for the company, but also the process and statistical details that brought to them. In fact, the marketing manager is supposed to possess knowledge of both statistics and the business, and therefore, before presenting the final solutions to the CEO, she/he would like to review the solutions under the light of the process that led to them. 
2) CEO_slides: this set of slides instead is supposed to be presented to the CEO, hence they shed light on the main recommendations that the team developed based on data, and on the economic impact that they can have on the retail company.

### Detailed Description of the results
The schema the team used to answer the questions "what is compromising performances?" is simple: we defined 4 steps that, starting from data, bring to practical actions and their impact on the company. The steps are:
  1) Identification
  2) Exploration
  3) Recommendation
  4) Implication

The team performed several analyses by using different statistical techniques (clustering, population tests, market basket analysis, RFM analysis), and developed several solutions, of which the most important is a new loyalty program based on "gamification", a novel marketing technique. The main idea behind the model is to push customers in the "worse" classes (i.e., the less profitable ones) to slowly behave like the ones in the "best" classes (i.e., the most profitable ones), hoping that they will slowly change their behavior through customized marketing actions, by making them feel like being in a game that makes them save money whilst shopping groceries.
The customer clustering is given by their shopping behaviour, that is both based on the RFM analysis (so, their frequency of purchase, recency, and median expenditure) and on the product categories they buy. Each customer group is targeted differently through different marketing techniques (e.g., up-selling, cross-selling, based on MBA), in order to increase their retention, frequency of purchase and satisfaction with the retail store, and thus the retail store profits.

Not only the team ideated the loyalty program based on data, but also created a dashboard for empowering marketing employees in making more complex analyses and take better decisions for targeting customer classes and make much quicker and informed decisions.

The R code is not provided as the methodological slides report all the necessary material to describe the solutions. However, I'll be pleased to share it if someone wants to dig deeper in my project :)
