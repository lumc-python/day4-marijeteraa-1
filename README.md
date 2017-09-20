# Interactive Visualization of Zika in the Americas

## Background

In 2016, the Zika virus epidemic hit the Americas.  

The file ```data/zika.csv``` contains data from the Center for Disease Control (CDC) tracking the number of confirmed cases of zika infection in the region during the epidemic.


## The Task

Using Jupyter and Bokeh, create an interactive visualization of the number of zika cases by country for **one** of the timepoints present in the data.

Use circles which are proportional in size to the number of cases.

Use tooltips which display the country name and the number of cases.


### Hints

The structure of the data is very similar to the fireball data from the lesson.

You should be able to re-use a lot of code from the lesson.

The 'Cases' field contains the number of confirmed cases.

The 'X' and 'Y' fields contain the map coordinates.

The 'Country' field contains the country name.

The 'Date' field contains the timepoint. Choose one timepoint and filter the dataframe to only use this one value.

To view only the Americas region on the map, use an x_range of (-11627260, -5627261) and a y_range of (-2724688, 3275312)


## Challenge

Can you add a slider to choose the timepoint?


### Challenge Hint

```
sorted(list(set(zika["Date"])))
```
can be used to get a list of timepoints for using with the slider.
