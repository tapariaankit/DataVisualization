# Data Visualization

The project provides implementations for two visualizations stated below:

## Visualization of mortality in the British Army (1854-55)
The below plots represent visualization of mortality in the British Army in the east during June 1854 to January 1855 due to 3 causes – Zymotic Diseases, Wounds and Injuries and all other causes. The areas of the wedges are measured from the centre and represents the number of deaths per 1000 by causes mentioned in the legends. *Figure 1* and *Figure 2* both represent the same information except the fact Figure 2 is more zoomed and **rotated 90 degrees anti-clockwise** with respect to *Figure 1*. **Legends** shown are **toggleable** in the notebook. **Hovering** on the plots shows the corresponding values at a particular point.

![alt text](https://github.com/tapariaankit/DataVisualization/blob/master/Visualizations_Screenshots/Nightingale_RoseChart.png "Nightingale RoseChart")

* *Dataset Used* -  nightingale-data.xlsx <br />
* *Code available in JupyterNotebook* - NightingaleRoseChart.ipynb <br />





## Visualization of Napoleon's 1812 March to Moscow

The below plots represent visualization of Napoleon’s 1812 March in Moscow. For the visualization, the troops are divided into **three** groups and their advance and retreat path along with number of troops survived at each point in the march are depicted.
All the cities (with their names), the troops passed through in the march are marked on the plots. Below figure represents the advance and retreat path of troops belonging to **Group-1** along with the number of troops survived. The **size of the markers (circles)** are proportional to the *number of troops survived at each data point*. So, we can observe, the march started with a large number of troops but as it progressed the troops kept decreasing and at the end very few survived. It also shows how **temperature drastically fell during the retreat** which made hard for the troop to survive. Similar plots were drawn for Troops belonging to Group-2 and Group-3. Hovering on the plots in the notebook shows the corresponding values at a particular point.


![alt text](https://github.com/tapariaankit/DataVisualization/blob/master/Visualizations_Screenshots/NapoleanMarch_1.png "Napolean's Russia march of 1812")
 
* *Dataset Used (From R's HistData Package)* -  minard-cities.csv, minard-troops.csv, minard-temp.csv <br />
* *Code available in JupyterNotebook* - MinardNapoleanMarch.ipynb <br />
 

# Tools, language and/or library used for the visualizations
+	Python 3.7
+	Plotly (graphing library) [https://plot.ly/]
+	Mapbox (for rendering of custom online maps in plots) [https://www.mapbox.com/]
+	Jupypter Notebook (IDE)

