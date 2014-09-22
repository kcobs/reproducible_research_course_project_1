## Introduction 

This project forms part of the [Reproducible Research course on Coursera](https://www.coursera.org/course/repdata). The goal of this project is to give the student an opportunity to conduct an analysis that is reproducible: "the ability of an entire [study] to be reproduced, etheir by the researcher or by someone else working independently" ([Wikipedia](http://en.wikipedia.org/wiki/Reproducibility)).

To this end, the assignment requires students to conduct an analysis and to consequently produce a report by following a [literate programming](http://en.wikipedia.org/wiki/Literate_programming) approach, where text and code are weaved toghether in a human-readable format. This type of report will be produced with [knitr](http://yihui.name/knitr/).

## Analysis

### Data
The data for the analysis is sourced from a personal activity monitoring device. This device collects data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November in 2012. The data is available [here](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip). The variables included in the data are:

* steps: Number of steps taken in a 5-minute interval
* date: The date on which the measurement was taken in YYYY-MM-DD format
* interval: A unuiqe identifier for the 5-minute interval in which measurement was taken

Missing values are coded as "NA". The dataset contains 17,568 observations and is stored in a comma-sperated value (CSV) format.

### Report

The following sections need to be present in the report:

* Loading and processing the data
* The mean total number of steps taken per day
* Daily patterns
* Comparing daily patterns with daily patterns where missing values are imputed
* Comparing differences between weekdays and weekends in daily patterns

The report needs to be saved in a R Markdown format (`.Rmd`) and commited to a [GitHub](http://www.github.com) repository. The Markdown and HTML files resulting from using the `knit2html()` function need to be submitted as well.

## Usage

* Clone the repository
* CD into the cloned repository
* Open R
* Set the working directory to the cloned repostory
* Run `library(knitr)`
* Run `knit2html(input = 'report.Rmd')`
* Look at `report.html`