# General instructions
* Do piece by piece. 
* Descriptive analytics task, 
* Decide on what field, subject, area of interest you would like to do this excercise
* Select data source(s) to be used
* Use Pandas and matplotlb or seaborn.

## evaluation details OF THIS PART to be evalueated (apart from exam). 
* Jupyter document 70 % weight: need to tell "story of data" which is readable, clear and well structured. 
* Pipeline software 30 % weight: 
1.  Need to have test part simulating data inflow
2.  need to have code you have tried in Jupyter document
3.  need to have result file having visualization data OR need to use matplot lib to show data 
4.  Need to change every time new "record" of data is received (from step i) 

# structure of work
Requirements: use Pandas and if needed numpy and scipy. Use some visualization library. 
## Part 1: Data Analytics: Story of data with Jupyter.
* Plan your pipeline. Describe the requirements you want to have. Describe data you will be using. Justify your decisions 
* This Jupyter document makes it possible to return to assumptions and decisions made and re-evaluate them at any point
  * So if you later on find that the data analysis model need to be fixed or made better, you can better find out correct approach.
* Future development: 
  * You can also list things that you feel should be done, but you will not do at this point
### Additional mandatory requirements for jupyter document
* Use all visualizations presented in in the same order
* use all location measures presented in order
* use all variation measures presented in order
* Use clear headings for the above. 
* For all of above tell what they reveal of the data you are handling

### additional guidelines you may want to think about
Tell what you want to do. Tell how you do it. If possible, tell why you do it, what is the purpose. In between you put pieces of python code, by which you are telling HOW you do it. All kind of interesting python code trials you want to include are fine also. if you try something and then decide not to use it, that can be inlcuded in the end. Just make it so that the Jupyter document is clear. 

## Part 2: Data Analytics  **software for pipeline in python**
1. *** Make a test code which feeds the data to your analytics code. 
2. make a simple analytics code which just takes in the data and does some simple calculation with it and outputs results of those to text file. 
* If possible use data source via some API. If not "fake" the api for static data table. 
* Make test code which feeds data to your analytics software record by record.  
* Database usage: save data handled by your analytics pipeline application to it. 
* draw some viusualization Visualization should change when new data is taken in. 
  * prove this by taking in such data that picture does change. 

# Possible data sources/areas of interest
* Covid
* weather
* Superstore Sales from BA1
Lot of open data available: google open data sources. 

# a list of python libraries
    Numpy and Scipy – Fundamental Scientific Computing. NumPy stands for Numerical Python. ...
    Pandas – Data Manipulation and Analysis. ...
    Matplotlib – Plotting and Visualization. ...
    Scikit-learn – Machine Learning and Data Mining. ...
    StatsModels – Statistical Modeling, Testing, and Analysis. ...
    Seaborn – For Statistical Data Visualization.

