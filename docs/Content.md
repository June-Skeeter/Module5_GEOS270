---
layout: default
title: Content
has_children: True
nav_order: 2
---

# Error, Spatial Bias, Logical Fallacies
{: .no_toc }

This week, we will be discussing errors, spatial bias, and logical fallacies.  We'll cover these topics on Wednesday.  But first we'll touch on some other things


<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
---



# Themes from Mid-Term Survey

## What are folks unsure about?

* Geographic coordinate systems and map projections.
* Spatial overlay/analysis methods

## Not remembering tools, nervous about exam, unsure about the project,, etc..

* GIS is **not** about memorization, it is about problem solving, critical thinking and reflection.  You'll almost always have access to the internet when doing GIS, if you don't know something, look it up!

* The exam will be open book.  You'll be able to complete it anytime during a 3-day window (Dec 13th - 15th).  You will have 6 hours to complete it.  The exam is **not** intended to take you six hours, I just don't want you to feel rushed/overwhelmed.
  * More details will be given next week.
  * I will try to give a thorough review for the exam on Dec 6th.


* I've given an extensive list of possible [project ideas](https://june-skeeter.github.io/FinalProjects_GEOS270/docs/Ideas.html).
  * You can also chat with your TAs in lab to think through ideas and get some tips.


* If need some help flushing the idea out and determining a workflow, or you are unclear on any material, please don't hesitate to drop by my office hours! (In person or on Zoom)
  * This week my office hours will stay as is (after class Wed, Thursday 2-3)
  * I will be offering extended office hours the last three weeks of term (specific timing tbd)
  * I'm happy to schedule zoom meetings at other hours (especially for folks in different time zones)

# Miscellaneous

* Formatting & typos
* Navigating github
* Audio quality
* Downloadable lectures


# Flowcharts

The flowchart is an important requirement for you final project and there will be a flowchart question on the final exam.

* Flowcharts are a useful tool for quickly summarizing your workflow.  It is important to be able to share what you've done and explain methods so people can trust your results.
* They can also be useful for planning a workflow.  You can draw out possible options, think through scenarios, and maybe catch logical flaws **before** you start doing an analysis.

There are a number of ways to create flowcharts.  You can draw them by hand, an ArcGIS Pro model can serve as an (ugly) flowchart, you can use power point, or you can try [Diagrams.net](https://app.diagrams.net/).  This site allows you to make aesthetically pleasing flowcharts quickly and easily, the video bellow gives you a quick overview of how to use the too.

<iframe width="560" height="315" src="https://www.youtube.com/embed/jq5NxMpOSKI?start=135" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


# Content Questions


## QC1

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

### QC2

Paris FR is roughly ________ times more dense than Salisbury, MD. (Nearest whole number is fine)

<!-- 23 -->

### QC3 

Burnaby's population is closest to that of ________ but because they have different ______ , they have very different densities.


### QC4

Vancouver's area is closest to that of ________ but because they have different ______ , they have very different densities.

### QC5

These discrepancies are attributable to something known as the ________ , because municipal boundaries are somewhat arbitrarily defined.  It is important to consider this issue when ________ different cities/regions/countries etc.

### QC

We can convert between ________ but each time we do, we induce ________ .  It is a bad idea to 

## QC

Accuracy is determined by how close observation(s) are to _______.

<!-- A true value/reality -->

## QC

Precision is determined by how close observation(s) are to _______.

<!-- Each other -->

## QC

Select all that apply:

a. Accuracy and precision basically mean the same thing, they can be used interchangeably.
b. Accuracy and precision are distinct concepts but they are related.
c. Accuracy and precision are not important.
d. A set of observations can be accurate but imprecise.
e. A set of observations can be precise but inaccurate.
f. To be accurate, we first need to ensure our observations are precise.
g. It is better to be accurate than precise.

<!-- b,d,e -->


## QC

It is important to ensure our data is in an appropriate map projection.  If you reproject a layer once, it generally won't cause you issues.  But each time you re-project a layer, it induces some _____ so if you re-project the same layer 20 times, the effects will _____ and could severely impact the quality of your data.

## QC

The MAUP is an issue that arises from the ________ of boundaries used to define a geographic unit/region.

## QC

The choice of boundaries can have drastic impacts on the ________ of a geographic unit/region.  For instance, the ______ of a census sub-division will be impacted because the sub-division's total _____ and area are impacted by the ________ used.

## QC

Larger census units ______ data over larger populations.

## QC

A _______ fallacy is a flaw in our thinking.
