---
layout: default
title: Reclassify
parent: Lab Application
nav_order: 3
---


# Reclassify

Reclassify distance and elevation.  You should complete these general steps.  Refer to the short video at the bottom of the page for reference.

**1**{: .label .label-red } Reclassify the **Euclidean Distance** layer following the table below.

| Start | End  | New    |
| ----- | ---- | ------ |
| 0     | 250  | 0 		| 
| 250   | 500  | 250	| 
| 500   | 1000 | 500	| 
| 1000  | 1500 | 1000	| 
| 1500  | 2000 | 1500	| 
| 2000  | 50000| NODATA	| 

**2**{: .label .label-red } Reclassify the **PA_DEM_ProjectRaster** following the table below.

| Start | End  | New    |
| ----- | ---- | ------ |
| 0     | 2    | 0 		| 
| 2     | 4    | 2  	| 
| 4     | 6    | 4  	| 
| 6     | 8    | 6   	| 
| 8     | 10   | 8  	| 
| 10    | 12   | 10  	|
| 12    | 14   | 12  	|  
| 14    | 16   | 14  	|  
| 16    | 18   | 16  	|  
| 18    | 20   | 18  	|  
| 20    | 10000| NODATA	| 

**3**{: .label .label-red } Inspect the outputs to make sure they are correct.

<iframe width="560" height="315" src="https://www.youtube.com/embed/rGfeEaTi7Ig" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>