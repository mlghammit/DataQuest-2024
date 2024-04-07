### Decoded: Unmasking Credit Card Fraud

FusionPoint is a leading consulting firm in the United States specializing in providing strategic solutions and advisory services to clients in the financial services industry. Established in 2012, FusionPoint has quickly grown to become a trusted partner for over 150 clients, including banks, investment firms, insurance companies, fintech startups, and regulatory bodies.

Credit card fraud affects over 151 million adults or more in a single year in the U.S. alone. With the recent increase of credit card fraud incidents, FusionPoint recognizes the urgency and importance of addressing this issue. Measures need to be implemented to protect customers from financial losses and preserve their trust in the financial system. Credit card fraud also results in revenue loss for businesses and financial institutions, tainting their reputation. The firm is looking to expand its advisory services to mitigate credit card fraud and preserve the integrity and confidence among stakeholders. 

As a team of consultants at FusionPoint, you have been tasked to develop machine learning algorithms to predict fraudulent transactions. There are a multitude of variables that could influence the likelihood of an incident occurring, such as location of the transaction, category of spending, and many others. 

The predictive model must be able to accurately predict credit card fraud based on historical data. This may require assumptions and decisions around machine learning techniques such as feature engineering, hyperparameter tuning, and various ways to evaluate model performance using metrics such as precision, recall, and F1 score. FusionPoint will also need to consider how to handle the unbalanced dataset, with fraudulent transactions only representing a small portion of the data. 

If done right, this could present an opportunity for FusionPoint to expand its service offerings and gain a competitive advantage. Therefore, it is essential to create a representative model and identify trends and patterns in historical transaction data that can help predict future fraudulent transactions accurately.

Your Task

Determine how FusionPoint can use machine learning to predict fraudulent transactions using the dataset provided. You will analyze the dataset of transactions in the US and use machine learning algorithms to build a predictive model. You will further present your conclusions in a slideshow pitch with potential solutions that FusionPoint can explore to help different stakeholders (consumers, institutions, businesses, payment providers, etc.) prevent/identify credit card fraud, and which ones your team deems most effective and feasible.

The deliverable is a 10 minute presentation, followed by a 5 minute Q&A. Your team will need to submit all files and your slide deck before 2pm on April 7th.


## Challenges:

#### Lots of data
- model has to be simple and fast to check new transactions

#### Imbalanced dataset
- 99% of transactions are legitimate
- hard to detect fraud


#### Steps:

- Check data:
    - num of frauds
    - num of valids 
    - percentage
    - clean up nan values

- visualizing all the features:
    - for each feature compare classes
    - tips
        - often times the avg money txn on fraud is higher
    - check corr matric

- Create training and test data
    - X=features Y=class
    - sklearn train_test_split
    - Create a pipeline?

- Model building:
    - Isolation Forest is for Anomlay detection - poor results
    - Random Forest Model is better
    - Use many models? ensemble?
    