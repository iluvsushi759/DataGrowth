## DataGrowth

#### Short Description:
For my employer, I've had to track data growth of disk space for our databases, warehouses, datalake sizes.  
That information is then placed into a .csv file and the script that I've provided will perform a Linear Regression to gather:

1. Data growth tracking
2. Predictions of growth

We could have also pulled the data straight from a database as opposed to using a csv.  
You will have to use connectors from a .py script to gather data from all different systems of on-site RDBMS, OLAP and cloud repositories and dump into a single DB.

In regards to the stucture of the .csv or database table, I have just 2 columns:  "timestamp" and "Size in GB".  
I did not provide how to pull the source data from multiple locations as that would consists of too many variables and depends on each circumstance.  I'll leave that to you to create your own data pull method.

There are few different versions in there with the growth charts.  Please feel free to play around and I'm sure you can improve on it.


#### Usage:
This is a ipynb file format.  Try importing it straight into your Notebook or copy and paste it into a .py file and run it.  
Please remember to have your necessary libraries installed and correct IDE that can run those.


