# MLOps-Introduction--Notes
-MLOps refers to applying/integrating DevOps priciples to Machine Learning.
- 10% of the work here will be Machine  Learning and 90% will be engineering.
- The process goes like:
  DATA COLLECTION -> TRAINING THE MODEL -> DEPLOY IN PRODUCTION


 ** CASE STUDY**
Email Spam Detection(Scammers and hackers can find a new method of sending the spam emails different from the ones that are in the dataset)

_MLOps Possible Scenarios_
1. When the model perfomance starts to decay. Assuming you have the _Email Spam Detection trained model_, you will eventually deploy the model but unfortunately you start seeing incorrect predictions.
   Hackers now will change their strategy to fraud and this will force you to (re)collect and (re)train both the data and the model.

2. We might need to reformulate our problem as it gets difficult to gatjer data which is free

3. Violation of assumption that was made during model training

4. When business objectives change.

   _Post-deployment woes_
1. _Accounting for latency_- It is said that 53% of site visits are abandoned if the site takes longer than 3 seconds to load
2. _Fairness_- eg Microsoft once launched _Twitter bot_ to learn from users. The bot quickly became racist.
3. _Lack of explainability and accountability_- Just make sure the model is authentic enough
4. _Slow_- Deploying models to production is very slow.

_Model-Centric Vs Data-Centric_
- Model-Centric is where you _hold the _data-fixed__ while you _iteratively fix the model_.
- Data-Centric is where you _hold the model fixed_ while you _iteratively fix the data_.

  Before starting anything(collecting data, deciding which model to use etc), first ask yourself the following question:
_        _What is the business problem that I/we are trying to solve?_
- Make sure you take care the cost of wrong predictions eg. _Overstocking_( can lead to _wasted resource_s  and _possible write-offs_),_Understocking_(can lead to _missed opportunities_, _unsatisfied custmers_).


# SALES FORECASTING PROJECT
- The project involves use of A/ML to analyze _past sales(histprical sales analysis)_ and _market trend(market trend analysis)_ to _predict future sales(Actual forecasting)_.
- The _ROI(Return On Investment)_ could be estimated by comparing the_ potential increase in sales_ and _decrease in wasted resources_ due to _improved forecasts_ against the _cost of developing AI/ML solutions._
- ROI-performance measure used to evaluate the efficiency or profitability of an investment. It compares the gain or loss from an investment relative to its cost.


# Machine Learning Implementation Structure

1. _Value Proposition_-
   - Define the problem, its importance and the end-user persona(the person who is going to use the product).
   - For instance ,for [target customer], who [need] our [product/service] is [product category] that [benefit]
   - Make sure that the [benefit] is the more important than the rest
2. _Data Sources_
   -Internal Databases
   - APIs
   - Open datasets
   - ------In thisprocess, consider hidden costs eg data storage and  purchasing external data --------

3. _Prediction task_
   -Supervised/unsupervised machine learning techniques? Is there an anomaly detection? Classification/Regression/Ranking?

4. Feature Engineering
   - Always work with _domain experts_ to _extract features from raw data sources_.eg in healthcare spaces(consult/work with a certified doctor to give you insights)

5. Offline evaluation
   - Set up some metrics to evaluate systempersomance pre-deployment.
   - Understand prediction errors and impacts
   - 








