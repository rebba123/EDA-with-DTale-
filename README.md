# EDA-with-DTale-


![Logo](https://media4.giphy.com/media/3oKIPEqDGUULpEU0aQ/200.webp?cid=ecf05e47pt5ce56witxj6st6pu2nbg8l0rt47qi199tsqap3&rid=200.webp&ct=g)


# Exploratory Data Analysis with DTale

🌱
This Repository represents the EDA of House price prediction Dataset.


# DTale Library

⚡
D-Tale is the combination of a Flask back-end and a React front-end to bring you an easy way to view & analyze Pandas data structures. It integrates seamlessly with ipython notebooks & python/ipython terminals. Currently this tool supports such Pandas objects as DataFrame, Series, MultiIndex, DatetimeIndex & RangeIndex.

## Description 

* Generally we perform various types of Analysis wrt the given data
 1.) Finding missing values 

![missingno_heatmap](https://user-images.githubusercontent.com/87561796/131805002-ffca5647-e320-4a39-a65c-22563a19f45d.png)
![missingno_matrix](https://user-images.githubusercontent.com/87561796/131805084-5a9baf74-03f9-471e-a030-24669ebf859e.png)

 2.) All numerical values
![Screenshot (425)](https://user-images.githubusercontent.com/87561796/131805312-52dffc3e-1b18-468e-b867-28a5135019a8.png)
The blue columns indicates the Numerical columns
 3.) Distribution of  Numercial values
![Screenshot (426)](https://user-images.githubusercontent.com/87561796/131805556-1078523a-54fb-4ecb-87e9-cda9c2254598.png)
![Screenshot (427)](https://user-images.githubusercontent.com/87561796/131805646-8e4fce5d-367b-44f0-b905-d38f7a96209e.png)
![Screenshot (428)](https://user-images.githubusercontent.com/87561796/131805710-92c758e7-24ba-48d2-b34c-2db2102c6e50.png)
Numerical values distribution wrt single feature indicating different graphs
 4.) Categorical variables

 5.) Cardinality of Categorical variables
![Screenshot (428)](https://user-images.githubusercontent.com/87561796/131806020-8238c9ee-a6ed-47bb-8fb1-95636017e10f.png)
 The above graph indicates above the heat map of whole dataset
 6.) Outliers
![Screenshot (431)](https://user-images.githubusercontent.com/87561796/131806656-901b5067-09d4-4ed7-a834-6be704dbf488.png)
Line graph
![Screenshot (431)](https://user-images.githubusercontent.com/87561796/131806725-d5cf2bde-fc72-470d-80c9-6d76227cd733.png)
bar graph
![Screenshot (433)](https://user-images.githubusercontent.com/87561796/131807046-6df86ba9-93ec-44ee-aacd-f81ccc875a0b.png)
scatter plot
![Screenshot (434)](https://user-images.githubusercontent.com/87561796/131807137-3605750d-555b-44fd-8ccb-294ca2baf05c.png)
pie chart
 7.) Relationship between Independent and dependent features
![Screenshot (430)](https://user-images.githubusercontent.com/87561796/131806236-5ab5ab5b-cd8e-41d0-8c7f-cbb4b55934fc.png)
The above graph indicates about the Corelation map

* As we cannot produce the whole graphs and analyzing here so i have uploded some of the screen shots for basic understanding.
*** Note : The above screen shots are of only sample pictures but the given analysis format of 7 points can be easliy done using "DTALE"
##  Requirements

🔭        
* Python 3.9+
* Jupyter Notebook
* Updated pip version


## Set-Up

1.) Install Jupyter Notebook and also upgrade pip 
    
    💬   pip install jupyter notebook

    python -m pip install --upgrade pip


2.) Install NumPy,Pandas, matplotlib and seaborn libraries
   
   💬    
    pip install pandas
    pip install matplotlib
    pip install seaborn
    pip install numpy


3.) Install DTale Library 
      
      💬    pip install DTale
