

# Directory of visualizations {#directory-of-visualizations}

This chapter provides a quick visual overview of the various plots and charts that are commonly used to visualize data. It is meant both to serve as a table of contents, in case you are looking for a particular visualization whose name you may not know, and as a source of inspiration, if you need to find alternatives to the figures you routinely make.



## Amounts

<img src="directory_of_visualizations_files/figure-html/amounts-1.png" width="840" style="display: block; margin: auto;" />

The most common approach to visualizing amounts (i.e., numerical values shown for some set of categories) is using bars, either vertically or horizontally arranged (Chapter \@ref(visualizing-amounts)). However, instead of using bars, we can also place dots at the location where the corresponding bar would end (Chapter \@ref(visualizing-amounts)).

<img src="directory_of_visualizations_files/figure-html/amounts_multi-1.png" width="840" style="display: block; margin: auto;" />

If there are two or more sets of categories for which we want to show amounts, we can group or stack the bars (Chapter \@ref(visualizing-amounts)). We can also map the categories onto the *x* and *y* axis and show amounts by color, via a heatmap (Chapter \@ref(visualizing-amounts)). 


## Distributions

<img src="directory_of_visualizations_files/figure-html/single-distributions-1.png" width="840" style="display: block; margin: auto;" />

Histograms and density plots (Chapter \@ref(histograms-density-plots)) provide the most intuitive visualizations of a distribution, but both require arbitrary parameter choices and can be misleading. Cumulative densities and q-q plots (Chapter \@ref(ecdf-qq)) always represent the data faithfully but can be more difficult to interpret.


<img src="directory_of_visualizations_files/figure-html/multiple-distributions-1.png" width="840" style="display: block; margin: auto;" />

Boxplots, violin plots, jittered points, and sina plots are useful when we want to visualize many distributions at once and/or if we are primarily interested in overall shifts among the distributions (Chapter \@ref(boxplots-violins-vertical)). Stacked histograms and overlapping densities allow a more in-depth comparison of a smaller number of distributions, though stacked histograms can be difficult to interpret and are best avoided (Chapter \@ref(multiple-histograms-densities)). Ridgeline plots can be a useful alternative to violin plots and are often useful when visualizing very large numbers of distributions or changes in distributions over time (Chapter \@ref(boxplots-violins-horizontal)).

## Proportions

<img src="directory_of_visualizations_files/figure-html/proportions-1.png" width="840" style="display: block; margin: auto;" />

Proportions can be visualized as pie charts, side-by-side bars, or stacked bars (Chapter \@ref(visualizing-proportions)), and as in the case for amounts, bars can be arranged either vertically or horizontally. Pie charts emphasize that the individual parts add up to a whole and highlight simple fractions. However, the individual pieces are more easily compared in side-by-side bars. Stacked bars look awkward for a single set of proportions, but can be useful when comparing multiple sets of proportions (see below).


<img src="directory_of_visualizations_files/figure-html/proportions-comp-1.png" width="840" style="display: block; margin: auto;" />

When visualizing multiple sets of proportions or changes in proportions across conditions, pie charts tend to be space-inefficient and often obscure relationships. Grouped bars work well as long as the number of conditions compared is moderate, and stacked bars can work for large numbers of conditions. Stacked densities (Chapter \@ref(visualizing-proportions)) are appropriate when the proportions change along a continuous variable.


## *x*--*y* relationships

<img src="directory_of_visualizations_files/figure-html/unnamed-chunk-3-1.png" width="840" style="display: block; margin: auto;" />


Scatter plots represent the archetypical visualization when we want to show one quantitative variable relative to another (Chapter \@ref(associations-scatterplots)). If we have three quantitative variables, we can map one onto the dot size, creating a variant of the scatter plot called bubble chart. For paired data, where the variables along the *x* and the *y* axes are measured in the same units, it is generally helpful to add a line indicating *x* = *y* (Chapter \@ref(associations-paired-data)). Paired data can also be shown as a slope graph of paired points connected by straight lines (Chapter \@ref(associations-paired-data)).

<img src="directory_of_visualizations_files/figure-html/unnamed-chunk-4-1.png" width="840" style="display: block; margin: auto;" />

For large numbers of points, regular scatterplots can become uninformative due to overplotting. In this case, contour lines, 2D bins, or hex bins may provide an alternative (Chapter \@ref(overlapping-points)). When we want to visualize more than two quantities, on the other hand, we may choose to plot correlation coefficients in the form of a correlogram instead of the underlying raw data (Chapter \@ref(associations-correlograms)).

<img src="directory_of_visualizations_files/figure-html/unnamed-chunk-5-1.png" width="840" style="display: block; margin: auto;" />

When the *x* axis represents time or a strictly increasing quantity such as a treatment dose, we commonly draw line graphs (Chapter \@ref(time-series)). If we have a temporal sequence of two response variables, we draw a connected scatter plot where we first plot the two response variables in a scatter plot and then connect dots corresponding to adjacent time points (Chapter \@ref(time-series-connected-scatter)). We use smooth lines to represent trends in a larger dataset (*chapter to be written*). 


## Uncertainty

<img src="directory_of_visualizations_files/figure-html/unnamed-chunk-6-1.png" width="840" style="display: block; margin: auto;" />



