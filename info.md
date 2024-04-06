### Credit Card Fraud Detection

## Challenges:

#### Lots of data
- model has to be simple and fast to check new transactions

#### Imbalanced dataset
- 99% of transactions are legitimate
- hard to detect fraud

#### Private data?
- reduce dimensionality


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
    