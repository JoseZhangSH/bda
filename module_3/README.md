# Module 3: First-order analysis and data exploration
Welcome to your practical assessment for Module 3 of MIT Big Data and Social Analytics.

## Objective:
When performing an analysis, you need to validate all of your assumptions, and be able to logically describe what you want to do, before selecting a method of execution. Using the WiFi access point information contained in the StudentLife data set from Dartmouth College you will:
- Explore the fundamental ideas of first-order analysis and data exploration;
- Explore the differences between noise and bias, and how you can reduce their impact in a data analysis project; and
- Apply basic statistical and visual data interrogation methods.

Engage with the tutor team in the forums if you get stuck, or if you learn something that you think is useful.

We hope that you enjoy this course, and acquire skills that are of use to you in your personal journey.

## Notebook 1: Data exploration: Test your intuition about BSSIDs
> **Notebook goal**: Justify your assumptions about the data and hypotheses using your own behaviors and patterns.

The easiest way to validate your assumptions about the data generated is by testing data using your own behaviors and patterns. Once you have developed a working hypothesis, you need to consider cases where the behaviors of others do not necessarily align with your own. This notebook introduces BSSIDs in more detail, and revisits some of the concepts around testing on yourself. It also repeats some of the data exploration steps for a single user, and offers you the chance to think about what you would expect to see in the data.


####  List of exercises:
>   - **Exercise 1:** Using Pandas's ``describe()`` and ``info()`` methods to review data.
  -  **Exercise 2:** Access point identification.
  - **Exercise 3 [Advanced]:** Trending access point information.

## Notebook 2: Exploring noise vs. bias
> **Notebook goal**: Show the difference between bias and noise.

Bias and noise (variance) are the two sources of error that are invariably found in data. Understanding the differences between these types of errors, and how you can identify and mitigate these, is an important task prior to conducting analysis. This notebook will utilize a generated data set to demonstrate the difference between noise and bias, and introduce the concept of working with image files as input to your analysis. While we do not recommend that you attempt any image processing on the supplied environment, it is important to understand that you are not just restricted to text files or databases as input to your analyses.

####  List of exercises
>   - **Exercise 1:** Reducing the effect of bias in data.
  - **Exercise 2:** Understanding the effect of increasing sample size on the shape of noisy and biased data.


## Notebook 3: Geotagging WiFi access points
> **Notebook goal**: Apply basic statistical and visual data interrogation to data.
This notebook starts by geotagging access points for a single user (in the first section) and then moves on to repeat the exercise for a large data set (in the second section). The goal is to identify stationary and non-stationary WiFi routers in the StudentLife data set. This is the first time that you will start to work with the full record set, and you will need to make sure that you shut down any other notebooks that are not in use, to ensure that you have the maximum amount of resources available to complete the exercise. You will iterate through a directory, load the various files, identify just under 700 000 geotags, and perform a number of transforms on the data set.


####  List of exercises:
>   - **Exercise 1:** Identification of stationary WiFi routers.
  - **Exercise 2 [Advanced]:** Identification of non-stationary WiFi routers.

<br></br>

**Contributors**:
**Andre Voges**, **Mieszko Manijak**, **Gorden Jemwa**, **Arek Stopczynski**, Xiaowen Dong, and Yves-Alexandre de Montjoye.
