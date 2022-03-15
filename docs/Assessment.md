---
layout: default
title: Assessment
nav_order: 4
---

# Assessment

You can use the submit your answers to the Assessment via the Module 3 Quiz on Canvas.  Questions are listed here with hyperlinks to the relevant section of the module if you need help finding answers.


## Written Answers & File Uploads

Written answers should be brief but they should adequately answer the question.  Bullet point format is sufficient unless otherwise specified.  All written answers & charts will be evaluated following this general rubrics below.

* Scores & categories are general guides, you TA may assign scores between these levels
* Your TA will provide brief comments where applicable, if you need more feedback you can follow up with your TA.

**Written Answer Rubric**

|Score|      Category      |                             Details                              |
|-----|--------------------|------------------------------------------------------------------|
|0%   |Missing             |N/A                                                               |
|40%  |Insufficient        |Minimal effort, missing major key points, or serious logical flaws|
|60%  |Below Expectations  |Missing a few key points or minor logical flaws                   |
|80%  |Met Expectations    |Hits key points and mostly well constructed                       |
|100% |Exceeds Expectations|Clearly thought out, concise, and astute                          |

**Map Rubric**

|Score|      Category      |                             Details                               |
|-----|--------------------|-------------------------------------------------------------------|
|0%   |Missing             |N/A                                                                |
|40%  |Insufficient        |Serious errors in analysis, missing data, or major stylistic issues|
|60%  |Below Expectations  |Minor errors in analysis or multiple stylistic issues              |
|80%  |Met Expectations    |Error free analysis, minor stylistic issue                         |
|100% |Exceeds Expectations|Error free analysis and clean, aesthetically pleasing map/chart    |

---

# Lecture Content Questions 

[**1**](Content_Part2.md)

Cluster sampling allows you to focus only on a specific area of interest. T/F

<!-- T -->

[**2**](Content_Part2.md)

IDW, also known as ________ distance weighting, is a spatial ________ method that allows us to create a raster dataset from a series of point samples.

<!-- Inverse, Intepolation -->

[**3**](Content_Part3.md)

Rank the following cities by population density from 1-7 (1 = most dense, 7 least dense)

|   |       City       |Area (Square Km)|Population (in Thousands)|
|---|------------------|---------------:|------------------------:|
|A  |Vancouver BC      |             115|                      675|
|B  |Burnaby BC        |              99|                      249|
|C  |New Westminster BC|              16|                       71|
|D  |New York City NY  |             783|                     8419|
|E  |Salisbury MD      |              37|                       33|
|F  |Paris FR          |             105|                     2175|
|G  |Anchorage, AK     |            5041|                      291|

<!-- 
1              Paris FR
2      New York City NY
3          Vancouver BC
4    New Westminster BC
5            Burnaby BC
6          Salisbury MD
7         Anchorage, AK
 -->

[**4**](Content_Part3.md)

Burnaby's population is closest to that of ________ but because they have different areas , they have very different population densities.  Vancouver's area is closest to that of ________ but because they have different populations, they have very different population densities.


[**5**](Content_Part3.md)

These discrepancies are attributable to something known as the ________ , because municipal boundaries are somewhat arbitrarily defined.  It is important to consider this issue when comparing values like population between different cities/regions/countries etc.

<!-- Correct:  **MAUP, modifiable areal unit problem** -->

[**6**](Content_Part3.md)

We can convert between raster and vector data models, but each time we do, we induce ________.  It is a bad idea to repeatedly convert between them.

<!-- 
**0**
Correct:  **Raster, Vector**
Half Pts:  rasyrt

**1**
Correct:  **Raster, Vector**
Half Pts:  

**2**
Correct:  **error, uncertainty, degradation, some amount of uncertainty, conversion errors**
Half Pts:  error/ difference/change, bias, spatial bias, distortion -->

[**7**](Content_Part3.md)

_______ describes by how close observations are to the true value.  _______ describes by how close observations are to each other.

<!-- 
[**8**](Content_Part3.md)

Select all that apply:

a. Accuracy and precision basically mean the same thing, they can be used interchangeably.
b. Accuracy and precision are distinct concepts but they are related.
c. Accuracy and precision are not important.
d. A set of observations can be accurate but imprecise.
e. A set of observations can be precise but inaccurate.
f. To be accurate, we first need to ensure our observations are precise.
g. It is better to be accurate than precise.
 b,d,e -->

<!-- 
[**QC10**]

It is important to ensure our data is in an appropriate map projection.  If you reproject a layer once, it generally won't cause you issues.  But each time you re-project a layer, it induces some ________ so if you re-project the same layer 20 times, the effects will ________ and could severely impact the quality of your data.
 -->

<!-- 
**0**
Correct:  **Error, uncertainty, level of uncertainty , bias, error / uncertainty, projection error**
Half Pts:  distortions

**1**
Correct:  **Cascade, Propogate, compound, increaes, accumulate, enlarge, excerbate, increase uncertainty, snowball, introduce error, compound/increase, add uncertainty, amplify**
Half Pts:  multiply, worsen, add up
 -->

[**8**](Content_Part3.md)

________ is when the something is poorly defined. ________ is when given a definition, there are multiple possible interpretations.

<!-- Correct:  **Vagueness, vague** -->





<!-- Correct:  **ambiguity, Ambiguous** -->

[**9**](Content_Part3.md)

A _______ is any flaw in our thinking.

<!-- Correct:  **Logical Fallacy** -->

<!-- 
### QC14 

A confidence interval is a metric that quantifies _______ .
 -->

<!-- **0**
Correct:  **precision, confidence in the average value of an estimate, confidence in the average value of a set of observations, confidence in the average value, a range of plausible values of a parameter, the precision of the data, uncertainty, the probability that a parameter will fall between a pair of values around the mean, the probability a parameter will fall between a pair of values around the same mean**
Half Pts:  the reliability of an estimate, certainty, degree of certainty, the confidence in x -->

<!-- 
### QC15

Measures like MAE, MSE, and RMSE are metrics that quantifiy _______ .  MAE and RMSE are different from MSE becaue MSE is not in the same ________ as the data.
 -->

<!-- **0**
Correct:  **Accuracy, the accuracy of observations, error**
Half Pts:  

**1**
Correct:  **Units**
Half Pts:   -->

[**10**](Content_Part3.md)

The Ecological/Atomistic fallacy arises when we take data that was collected in aggregate and apply it to an individual.  The Ecological/Atomistic fallacy arises when we take data that was collected in aggregate and aggregate it again.


<!-- **0**
Correct:  **Ecological, ecological fallacy**
Half Pts:  

**1**
Correct:  **Agregate, groupsa group, the group, aggregation**
Half Pts:   -->


[**11**](Content_Part3.md)

Slivers, overlaps, and gaps are three types of errors that arise when:

* Interpolating
* Digitizing
* Georeferencing
* Projecting

<!-- **0**
Correct:  **digitizing errors, digitization errors, errors that occur when features are digitised, error that can occur when features are digitized, errors that occur when digitizing, errors that can occur when features are digitalized, digitized features error, errors that occur during digitization of features**
Half Pts:   -->



[**12**](Content_Part3.md)

In many cases, GIS products don’t have obvious evidence of their own inadequacy.


<!-- 
**0**
Correct:  **Evidence, a standardized measure, obvious evidence , standardized measure, obvious evidence**
Half Pts:  have obvious , standardized measurements (obvious evidence)

**1**
Correct:  **Inadequacy, data quality, quality, data quality (inadequacy)**
Half Pts:  errors, error, uncertainty

 -->

---

# Lab Application Questions 

[13](Application_Part5.md)

Submit a .pdf of the model you created to identify the inundation zone.

[14](Application_Part5.md)

Submit a .pdf of the map you created to showing the updated inundation zone.


[15](Application_Part5.md)

Write a paragraph or two comparing the method used in the Module 5 model to identify the Inundation Zone vs. the method used in Module 4 model to identify the Inundation Zone.  **Things to consider:** What tools/steps were used in each model?  Which do you think produces a more useful result?  What are some potential pros/cons of the  different methods?  