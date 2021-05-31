# Matplotlib

matplotlib is a Python package for 2D-graphics. It provides both a very quick way to visualize data from Python and publication-quality figures in many formats

Import matplotlib library :
`import matplotlib.pyplot as plt`
Set data for plot 
`plt.plot(<numerical data>)`
Show the chart :
`plt.show()`
Add label for the chart :
plt.ylabel(‘label name')

Customize the line properties (color and width):
`plt.plot(X, C, color="blue", linewidth=2.5, linestyle="-")`
Customize maximum values ​​for axes  (X and Y) :
`plt.xlim(X.min()*1.1, X.max()*1.1)`
Change axes ticks : 
`plt.xticks( [<list of new ticks values >])
Set a text value instead of numeric values ​​for axes ticks :
`plt.yticks([<list of numerical values>],[<list of text values>])`

**Adding a legend :**
`plt.legend(loc='upper left', frameon=False)`
Before that you need to add labels for every line in the chart :
plt.plot(X, label=" label _1")
