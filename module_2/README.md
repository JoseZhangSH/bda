# Module 2: Personal sensors and human behavior
Welcome to your practical assessment for Module 2 of MIT Big Data and Social Analytics.

## Objective
This module introduces:

> - the concept of data enrichment using various sources of external data to enrich your analyses;

> - How to leverage data collected using sensors to predict behavior; and,

> - Collecting data to help in, for example, validating your own hypotheses prior to designing social physics experiments.

A fundamental idea in social physics begins to emerge from this notebook. The idea is that paying attention to a person's social context is better at predicting their behavior than paying attention to their individual features (such as demographics).

Engage with the mentor team and fellow students in the forums to get help, and share your insights and learning experiences.

We hope that you enjoy this course, and that you will acquire and refine skills that are of use to you in your personal journey.

## Notebook 1: Sources of data
> **Notebook goal**: Use external data sources for data enrichment.

To start developing ideas around social context, it is perhaps best to start with what is already known in the public domain. This notebook explores the use of Python modules that can help in importing external data sets into your environments, for the purpose of merging these to data you have already collected to enrich your analysis. Depending on its source, external data from the public domain can be considered "trusted" or "untrusted." Irrespective of this categorization, you will always need to remember to take the five Rs of data quality into account.


> **List of exercises**:

> - Exercise 1: Enriching analysis with data from "trusted" sources.

> - Exercise 2: Pros and cons of using data from "untrusted" sources.

## Notebook 2: Introduction to Funf
> **Notebook goal**: Demonstrate familiarity with the key features of Funf.

The "Family and Friends" and "StudentLife" data sets used in this course were collected using, or inspired by, the Funf Open Sensing Framework,  an open-source, extensible sensing and data processing framework designed to provide a reusable set of functionalities that enable the collection, uploading, and configuration of a wide range of data signals accessible via mobile phones. In this notebook, you will explore what kind of personal behaviors can be predicted using such sensor signals.

> **List of exercises**
> - Exercise 1: Visualizing mobility trace patterns.
> - Exercise 2: Analysis and interpretation of behavior from mobility trace patterns (short range).
> - Exercise 3: Analysis and interpretation of behavior from mobility trace patterns (long range).


## Notebook 3: Collect your own data
> **Notebook goal**: Demonstrate familiarity with the Bandicoot toolbox for the collection and analysis of metadata from (Android) mobile devices.

An important and recurring theme in social physics is validating what you expect to observe in social contexts, using your own data. This also helps in guiding how to expand an experiment to pilot scale and large scale. In this notebook, you will be introduced to Bandicoot, an open-source Python toolbox, which can be used for collection, analyisis, and visualization of mobile phone metadata. This section demonstrates how it can be used to collect your own data. What is possible with these open frameworks (Python, Pandas, Funf, and Bandicoot) is impressive. To whet your appetite, you can read more about what is possible in a student's [blog post](http://sampaddock.com/blog/2016/8/7/heres-how-to-explore-your-personal-location-data) from a previous MIT Big Data and Social Analytics presentation.

> **List of exercises**
> - Exercise 1: Using Bandicoot for analysis.
> - Exercise 2: Interpreting calls of zero duration in call records.



**Notebook Contributors**:
**Andre Voges**, Mieszko Manijak, **Gorden Jemwa**, Arek Stopczynski, Xiaowen Dong, and Yves-Alexandre de Montjoye.
