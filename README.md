# Running the project
## Step 0: Windows 
Install WSL from Microsoft store, eg. Ubuntu 20.4 LTS
## Step 1
Install Docker Desktop
## Step 2 
Run Docker Desktop
## Step 3
Load dataset
Enter all files from: 
``` https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data ```
to folder ```data``` so it looks like:
-- data
 |- holiday_events.csv 
 |- oil.csv
 |...

## Step 4
Run commands
```
docker-compose build
docker-compose up 
```
# Entering Jupyter Notebook
```
http://127.0.0.1:8888/lab
```
