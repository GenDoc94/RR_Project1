---
title: "Reproducible Research: Peer Assessment 1"
output: 
  html_document:
    keep_md: true
author: "GenDoc94"
date: "2024-08-04"
---



## Loading and preprocessing the data
Loading the data

``` r
linkURL <- "https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip"
download.file(linkURL, destfile = "activity.zip")
unzip(zipfile = "activity.zip")
activity <- read.csv("activity.csv", header = TRUE, sep = ",")
file.remove("activity.zip")
```


## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
