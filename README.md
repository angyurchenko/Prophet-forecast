# Prophet-forecast
## **Summary:**

Write a program in Python to run prediction with the *Prophet algorithm* (developed by FB team)

There are two files with test data attached: **past.csv** and **future.csv**
- **past.csv** - contains revenue per day with ad spend per day
- **future.csv** - contains ad spends, but doesn't contain revenue
 
## **Tasks:**
- working source code in Python
- result dataset in csv format - it should contain **date, actual** and **fitted values** for past and future
- plot of historical vs. fitted revenue + predicted future revenue
- plot of prophet trends decomposition (see attached example)

## **Results**:
- For the revenue predicting Prophet model was used with the **tuned hyperparameters**
- As a result of hyperparameters tunning **root mean square error (rmse) dropped** from more then $700 to $30
- From the forecast could be found that trend has a negative impact throughout time which indicated a need for future modification of the marketing strategy 
