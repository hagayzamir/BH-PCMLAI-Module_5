# Activities
## About this file
This file describe the activities perform during this assignment.

### Data Cleaning 
I first counted the number of null values in the dataset using: 

```
data.isnull().sum()
```
I then used:
```
data.info()
```
to see the type of data i have in the dataset

Give the results, I have decided to 'drop' the car coulmn and then to 'dropna' all the other missing rows.
```
data = data.drop(columns=['car'])
data = data.dropna()
```
