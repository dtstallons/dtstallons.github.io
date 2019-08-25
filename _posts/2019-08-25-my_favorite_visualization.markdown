---
layout: post
title:      "My Favorite Visualization"
date:       2019-08-25 15:13:48 +0000
permalink:  my_favorite_visualization
---


Getting started on this program, it was immediately apparent the usefulness and value of a quality visualization. The illustration of a dataset tells a highly descriptive story that represents the data. My favorite to use thus far is the Seaborn Heatmap:

![](https://www.absentdata.com/wp-content/uploads/2018/11/Heatmap-1.png)

This is an example of using the heatmaps feature to observe coefficients for multicollinearity. Alternatively you could go through and calculate the variance inflation factor (VIF) for every one of the coefficients but I find it much easier to make the heatmap. It is so easy to view this information and pick out the columns you'd like to drop. Also, the map is a much more significant way to view trends in the data as with this image you can see the pattern of the collinearity.

The only negative with the heatmap that I have obseved thus far is when the amount of columns you are analyzing exceeds a large number like 25. With too many paramters the heatmap may still be helpful to show trend but it absolutely gets busy and difficult to read past a certain point. If this is the case then I would emply a different method to narrow the selection down and proceed with the heatmap after an ainitial reduction.
