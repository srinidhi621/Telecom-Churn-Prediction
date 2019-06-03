# Telecom-Churn-Prediction
Telecom Churn Prediction using Machine Learning models

Telecom companies need to predict which customers are at high risk of churn. In this repo, we will have 3 main goals. 

1. Analyse customer-level data of a leading telecom firm.
2. Build predictive models to identify customers at high risk of churn
3. Identify the main indicators of churn.

## Data
The dataset contains customer-level information for a span of four consecutive months - June, July, August and September. The months are encoded as 6, 7, 8 and 9, respectively. 

The objective is to predict the churn in the last (i.e. the ninth) month using the data (features) from the first three months. 

In churn prediction, we assume that there are three phases of customer lifecycle :

    The ‘good’ phase: In this phase, the customer is happy with the service and behaves as usual.

    The ‘action’ phase: The customer experience starts to sore in this phase, for e.g. he/she gets a compelling offer from a  competitor, faces unjust charges, becomes unhappy with service quality etc. In this phase, the customer usually shows different behaviour than the ‘good’ months. Also, it is crucial to identify high-churn-risk customers in this phase, since some corrective actions can be taken at this point (such as matching the competitor’s offer/improving the service quality etc.)

    The ‘churn’ phase: In this phase, the customer is said to have churned. You define churn based on this phase. Also, it is important to note that at the time of prediction (i.e. the action months), this data is not available to you for prediction. Thus, after tagging churn as 1/0 based on this phase, you discard all data corresponding to this phase.
    
In this case, since we have data over a four-month window, the first two months are the ‘good’ phase, the third month is the ‘action’ phase, while the fourth month is the ‘churn’ phase.

