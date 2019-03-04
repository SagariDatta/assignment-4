# Assignment #4

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Spring-2019/assignment-4/master)

### This assignment is OPTIONAL

### Due Date: Friday 3/15 by 5pm

### GitHub Invitation Link

The invitation link for this week is:

https://classroom.github.com/a/vsJqHXyw

## Description

In this assignment, we'll explore restaurant review data available through the [Yelp Dataset Challenge](https://www.yelp.com/dataset/challenge). The dataset includes Yelp data for user reviews and business information for 10 metropolitan areas. The `data` directory in this repository includes data files for reviews and restaurants in 3 of these cities: Cleveland, Pittsburgh, and Charlotte. These cities were chosen since the data is not too large — the data for the other cities can be downloaded from the Yelp download page. For this assignment, you are welcome to analyze data any of the three cities.

This assignment is broken into two parts:

#### Part 1: testing how well sentiment analysis works.

Because Yelp reviews include the number of stars given by the user, the Yelp data set provides a unique opportunity to test how well our sentiment analysis works by comparing the number of stars to the polarity of reviews.

#### Part 2: analyzing correlations between restaurant reviews and census data

Analyzing the frequencies of different sets of words in Yelp reviews can offer insight into urban culture. Specifically, we'll test the correlation between household income (using census data) and different types of restaurants, extracted from review data.

#### Background readings

- [Does sentiment analysis work?](http://varianceexplained.org/r/yelp-sentiment/)
- [The Geography of Taste: Using Yelp to Study Urban Culture](https://www.mdpi.com/2220-9964/7/9/376/pdf/1)

## Assignment details

A skeleton Jupyter notebook is available in this repository that will walk you through the steps of the assignment. The completed notebook should be submitted as your assignment.

## Submission

We'll be using GitHub for assignment submission again. You can set up your own private repository on GitHub for this assignment using the link below.

The invitation link for this week is:

https://classroom.github.com/a/vsJqHXyw

## Installing the necessary dependencies

**The Python dependencies used for this assignment are the same as through week 5. If you've updated your local environment already for week 5, you shouldn't need to install any more dependencies. If not, follow the instructions below.**

First, download the `environment.yml` file in this repository to your computer.

**Important**: if you are on a Windows machine, make sure that `.txt` wasn't appended to the file name when you downloaded it. If so, you will need to rename it so the file ends in `.yml`.

Then you can run, from either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa
```

where `musa` should be the name of the environment you have been using.

**Important:** If you are starting a Jupyter notebook through the command line, you must activate the environment before you start a notebook:

```
conda activate musa
jupyter notebook
```

If you are starting through Anaconda Navigator, be sure to select the right environment (change `base` to `musa`) before hitting the `Launch` button!
