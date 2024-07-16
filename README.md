# pml
This is our code collection for the course CS772: Probabilistic Machine Learning instructed by Prof. Piyush Rai

This project is exploring probabilistic approaches for treating model performance. This is required for safety critical tasks where an example that the model was previously trained on needs to be removed and so the model needs to completely forget about it. The naive method suggests to train the model from scratch on the new dataset; however, machine unlearning explores methods to avoid extensive retraining and smartly subtract the influence of the unrequired examplesfrom the trained parameters. For this, we devised a two-stage pipeline; 1) Cause identification for identifying what datapoints in the dataset are faulty (or no longer required) and 2) Model treatment to use a mathematical formula to rectify the trained weights. 

We achieved scores of 0.42 for corrupted training data and 0.50 for filtered training data after treatment. 

### Group Members
1. Gaurang Dangayach
2. Rahul Rustagi
3. Suryanshu Jaiswal
4. Udvas Basak
