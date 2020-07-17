# MasterClass_DataVisualization
A tutorial for beginners in python visualization using plotly and dash 

Doc Link: https://docs.google.com/document/d/1JOJhiBfsnu6hFufzhvOE6aGO2wVddZdvfG4thMyBwdc/edit?usp=sharing

Plotly
Using pip :  $ pip install plotly==4.9.0 
Or 
Using conda:  $ conda install -c plotly plotly=4.9.0

       2)	Pandas
	
	conda install pandas  OR  pip install pandas 

      3) Dash 

	pip install dash==1.13.3
	pip 
  
Why Plotly?
PYTHON :D
Generates interactive graphs (zooming, hovering, all available by default) 
The best part, the created visuals can be hosted using the Dash library( open-source framework) 
	
The python lib which we are going to use feeds the input to the Plotly.js ( a javascript code) under the hood. Every visualization in python is converted(serialized)  in the form of a JSON and is fed to this javascript code and that is how you see the visualization come alive :). 

What is JSON?
JSON (JavaScript Object Notation) is a lightweight data-interchange format. 
It is easy for humans to read and write. 
It is easy for machines to parse and generate.

Its representation and the manipulation that you do with it just like the python dictionary. 

Basic charts covered:

Line
Scatter
Bar
Pie
Box Plot

https://miro.medium.com/max/18000/1*2c21SkzJMf3frPXPAR_gZA.png

Boxplots are a standardized way of displaying the distribution of data based on a five-number summary (“minimum”, first quartile (Q1), median, third quartile (Q3), and “maximum”).
Median (Q2/50th Percentile): The middle value of the dataset. ( sorted list )
First quartile (Q1/25th Percentile): The middle number between the smallest number (not the “minimum”) and the median of the dataset.
Third quartile (Q3/75th Percentile): The middle value between the median and the highest value (not the “maximum”) of the dataset.
Interquartile range (IQR):  25th to the 75th percentile
Outliers (shown as green circles)
“maximum”: Q3 + 1.5*IQR
“minimum”: Q1 -1.5*IQR
Referred Resources

The main pages of the library used and that gives examples of the possible graphs that can be built using plotly.express
Basic Charts | Python
https://plotly.com/python/plotly-express/

Documentation on the function that you’ll come across:
https://plotly.com/python-api-reference/generated/plotly.graph_objects.Figure.html

Tweaking Legends
https://plotly.com/python/legend/

For more details on  data frames grouping
https://pandas.pydata.org/pandas-docs/version/0.22.0/generated/pandas.core.groupby.DataFrameGroupBy.agg.html
