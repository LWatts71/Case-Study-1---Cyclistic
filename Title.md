Case Study 1 - Cyclistic
================
Luke Watts
2025-02-26

<center>

![](data:image/jpeg;base64,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)

</center>

Hello! My name is Luke Watts, and this is my first data analytics case
study - completed as the capstone project for my Google Data Analytics
Certification.

In this report I will walk you through the steps I took as I verified,
cleaned, processed, and analysed the data. I will then share with you my
insights and the conclusions that I made that informed my
recommendations for the Cyclistic marketing team and shareholders.

We will follow the established 6 step process of data analysis - Ask,
Prepare, Process, Analyse, Share, and finally Act.

## What is the scenario?

#### An excerpt from the case study notes;

You are a junior data analyst working on the marketing analyst team at
Cyclistic, a bike-share company in Chicago. The director of marketing
believes the company’s future success depends on maximizing the number
of annual memberships. Therefore, your team wants to understand how
casual riders and annual members use Cyclistic bikes differently. From
these insights, your team will design a new marketing strategy to
convert casual riders into annual members. But first, Cyclistic
executives must approve your recommendations, so they must be backed up
with compelling data insights and professional data visualizations.

#### Key Stakeholders

Lily Moreno, the founder of Cyclistic Executive Team Marketing Analytics
Team (your department)

#### Cyclistic Background Info

In 2016, Cyclistic launched a successful bike-share offering. Since
then, the program has grown to a fleet of 5,824 bicycles that are
geotracked and locked into a network of 692 stations across Chicago. The
bikes can be unlocked from one station and returned to any other station
in the system anytime.

Until now, Cyclistic’s marketing strategy relied on building general
awareness and appealing to broad consumer segments. One approach that
helped make these things possible was the flexibility of its pricing
plans: single-ride passes, full-day passes, and annual memberships.
Customers who purchase single-ride or full-day passes are referred to as
casual riders. Customers who purchase annual memberships are Cyclistic
members.

Cyclistic’s finance analysts have concluded that annual members are much
more profitable than casual riders. Although the pricing flexibility
helps Cyclistic attract more customers, Moreno believes that maximizing
the number of annual members will be key to future growth. Rather than
creating a marketing campaign that targets all-new customers, Moreno
believes there is a solid opportunity to convert casual riders into
members. She notes that casual riders are already aware of the Cyclistic
program and have chosen Cyclistic for their mobility needs.

Moreno has set a clear goal: Design marketing strategies aimed at
converting casual riders into annual members. In order to do that,
however, the team needs to better understand how annual members and
casual riders differ, why casual riders would buy a membership, and how
digital media could affect their marketing tactics. Moreno and her team
are interested in analyzing the Cyclistic historical bike trip data to
identify trends. Let us begin…

## Step 1: Ask

Business Task: Design marketing strategies aimed at converting casual
riders into annual members. Three questions will guide the future
marketing program: 1. How do annual members and casual riders use
Cyclistic bikes differently? 2. Why would casual riders buy Cyclistic
annual memberships? 3. How can Cyclistic use digital media to influence
casual riders to become members? Of all the business questions, I have
been assigned to answer the first one. Hence, I will focus on analysing
the relationships in the data between the annual members and casual
riders.

## Step 2: Prepare

To conduct an in depth analysis, we must obtain the Cyclistic historical
data trips from December 2023 to November 2024, from
[here](https://divvy-tripdata.s3.amazonaws.com/index.html) The data has
been made available by Motivate International Inc. under [this
license](https://divvybikes.com/data-license-agreement) Datasets have
been downloaded and stored locally in a folder “202312–202411_Cyclistic”
All 12 Data sets are standardized and have the same 12 columns of
information Due to data privacy issues, personal information has been
removed / encrypted

#### Perform ROCCC check:

Data is reliable as it us unbiased and represents the population fairly
due to having a large sample size. Data is original (Cyclistic is a
fictional company so technically data is actually not original but can
be considered so for the purpose of this case study). Data is
comprehensive- we have a full data set for the time frame stated and all
the info we need to answer the business task. Data is current, from the
last year up until present day. Data is not cited, but has been vetted
by Motivate International Inc.

Use R Studio to aggregate and manipulate the data, as in total, the
combined dataset will be large in scale.

#### Setting up the environment

Set the working directory to the local folder where the datasets are

``` r
knitr::opts_knit$set(file_location <- "C:/Users/lukew/Desktop/Case Study 1 - Cyclistic (R)/202312–202411_Cyclistic")
```

Let’s load the tidyverse, dplyr, lubridate, and markdown packages

``` r
library(tidyverse)
```

    ## ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
    ## ✔ dplyr     1.1.4     ✔ readr     2.1.5
    ## ✔ forcats   1.0.0     ✔ stringr   1.5.1
    ## ✔ ggplot2   3.5.1     ✔ tibble    3.2.1
    ## ✔ lubridate 1.9.3     ✔ tidyr     1.3.1
    ## ✔ purrr     1.0.2     
    ## ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()
    ## ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors

``` r
library(dplyr)
library(lubridate)
library(rmarkdown)
```

assign all the csv files in the working directory to a variable called
“aggregate_files”

``` r
aggregate_files <- list.files(file_location, full.names = TRUE, pattern = "*.csv")
```

read the .csv files in the aggregate_files variable and map them into a
single data frame called “aggregate_dataframe”

``` r
aggregate_dataframe <- map_df(aggregate_files, read_csv)
```

    ## Rows: 224073 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 144873 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 223164 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 301687 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 415025 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 609493 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 710721 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 748962 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 755639 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 821276 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 616281 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
    ## Rows: 335075 Columns: 13
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr  (7): ride_id, rideable_type, start_station_name, start_station_id, end_...
    ## dbl  (4): start_lat, start_lng, end_lat, end_lng
    ## dttm (2): started_at, ended_at
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

#### Initial data observation

lets check the column names for the combined data set as part of our
data check

``` r
colnames(aggregate_dataframe)
```

    ##  [1] "ride_id"            "rideable_type"      "started_at"        
    ##  [4] "ended_at"           "start_station_name" "start_station_id"  
    ##  [7] "end_station_name"   "end_station_id"     "start_lat"         
    ## [10] "start_lng"          "end_lat"            "end_lng"           
    ## [13] "member_casual"

lets check how many rows in the data frame

``` r
nrow(aggregate_dataframe)
```

    ## [1] 5906269

lets check the dimensions of the data frame

``` r
dim(aggregate_dataframe)
```

    ## [1] 5906269      13

lets look at a brief summary of the data frame

``` r
head(aggregate_dataframe)
```

    ## # A tibble: 6 × 13
    ##   ride_id          rideable_type started_at          ended_at           
    ##   <chr>            <chr>         <dttm>              <dttm>             
    ## 1 C9BD54F578F57246 electric_bike 2023-12-02 18:44:01 2023-12-02 18:47:51
    ## 2 CDBD92F067FA620E electric_bike 2023-12-02 18:48:19 2023-12-02 18:54:48
    ## 3 ABC0858E52CBFC84 electric_bike 2023-12-24 01:56:32 2023-12-24 02:04:09
    ## 4 F44B6F0E8F76DC90 electric_bike 2023-12-24 10:58:12 2023-12-24 11:03:04
    ## 5 3C876413281A90DF electric_bike 2023-12-24 12:43:16 2023-12-24 12:44:57
    ## 6 28C0D6EFB81E1769 electric_bike 2023-12-24 13:59:57 2023-12-24 14:10:57
    ## # ℹ 9 more variables: start_station_name <chr>, start_station_id <chr>,
    ## #   end_station_name <chr>, end_station_id <chr>, start_lat <dbl>,
    ## #   start_lng <dbl>, end_lat <dbl>, end_lng <dbl>, member_casual <chr>

lets inspect the overall structure of the data

``` r
str(aggregate_dataframe)
```

    ## spc_tbl_ [5,906,269 × 13] (S3: spec_tbl_df/tbl_df/tbl/data.frame)
    ##  $ ride_id           : chr [1:5906269] "C9BD54F578F57246" "CDBD92F067FA620E" "ABC0858E52CBFC84" "F44B6F0E8F76DC90" ...
    ##  $ rideable_type     : chr [1:5906269] "electric_bike" "electric_bike" "electric_bike" "electric_bike" ...
    ##  $ started_at        : POSIXct[1:5906269], format: "2023-12-02 18:44:01" "2023-12-02 18:48:19" ...
    ##  $ ended_at          : POSIXct[1:5906269], format: "2023-12-02 18:47:51" "2023-12-02 18:54:48" ...
    ##  $ start_station_name: chr [1:5906269] NA NA NA NA ...
    ##  $ start_station_id  : chr [1:5906269] NA NA NA NA ...
    ##  $ end_station_name  : chr [1:5906269] NA NA NA NA ...
    ##  $ end_station_id    : chr [1:5906269] NA NA NA NA ...
    ##  $ start_lat         : num [1:5906269] 41.9 41.9 41.9 42 41.9 ...
    ##  $ start_lng         : num [1:5906269] -87.7 -87.7 -87.6 -87.7 -87.6 ...
    ##  $ end_lat           : num [1:5906269] 41.9 41.9 41.9 41.9 41.9 ...
    ##  $ end_lng           : num [1:5906269] -87.7 -87.6 -87.6 -87.7 -87.6 ...
    ##  $ member_casual     : chr [1:5906269] "member" "member" "member" "member" ...
    ##  - attr(*, "spec")=
    ##   .. cols(
    ##   ..   ride_id = col_character(),
    ##   ..   rideable_type = col_character(),
    ##   ..   started_at = col_datetime(format = ""),
    ##   ..   ended_at = col_datetime(format = ""),
    ##   ..   start_station_name = col_character(),
    ##   ..   start_station_id = col_character(),
    ##   ..   end_station_name = col_character(),
    ##   ..   end_station_id = col_character(),
    ##   ..   start_lat = col_double(),
    ##   ..   start_lng = col_double(),
    ##   ..   end_lat = col_double(),
    ##   ..   end_lng = col_double(),
    ##   ..   member_casual = col_character()
    ##   .. )
    ##  - attr(*, "problems")=<externalptr>

lets get a statistical summary of the data by column (note that the
total number of N/A or blank entries for each column is also listed)

``` r
summary(aggregate_dataframe)
```

    ##    ride_id          rideable_type        started_at                    
    ##  Length:5906269     Length:5906269     Min.   :2023-12-01 00:00:03.00  
    ##  Class :character   Class :character   1st Qu.:2024-05-10 16:11:14.00  
    ##  Mode  :character   Mode  :character   Median :2024-07-15 02:26:14.63  
    ##                                        Mean   :2024-07-04 14:20:07.79  
    ##                                        3rd Qu.:2024-09-11 16:43:33.91  
    ##                                        Max.   :2024-11-30 23:52:17.41  
    ##                                                                        
    ##     ended_at                      start_station_name start_station_id  
    ##  Min.   :2023-12-01 00:04:12.00   Length:5906269     Length:5906269    
    ##  1st Qu.:2024-05-10 16:27:10.00   Class :character   Class :character  
    ##  Median :2024-07-15 03:12:37.78   Mode  :character   Mode  :character  
    ##  Mean   :2024-07-04 14:37:26.98                                        
    ##  3rd Qu.:2024-09-11 16:57:08.47                                        
    ##  Max.   :2024-11-30 23:57:43.00                                        
    ##                                                                        
    ##  end_station_name   end_station_id       start_lat       start_lng     
    ##  Length:5906269     Length:5906269     Min.   :41.64   Min.   :-87.91  
    ##  Class :character   Class :character   1st Qu.:41.88   1st Qu.:-87.66  
    ##  Mode  :character   Mode  :character   Median :41.90   Median :-87.64  
    ##                                        Mean   :41.90   Mean   :-87.65  
    ##                                        3rd Qu.:41.93   3rd Qu.:-87.63  
    ##                                        Max.   :42.07   Max.   :-87.52  
    ##                                                                        
    ##     end_lat         end_lng        member_casual     
    ##  Min.   :16.06   Min.   :-144.05   Length:5906269    
    ##  1st Qu.:41.88   1st Qu.: -87.66   Class :character  
    ##  Median :41.90   Median : -87.64   Mode  :character  
    ##  Mean   :41.90   Mean   : -87.65                     
    ##  3rd Qu.:41.93   3rd Qu.: -87.63                     
    ##  Max.   :87.96   Max.   : 152.53                     
    ##  NA's   :7340    NA's   :7340

## Step 3: Process

#### Cleaning

Data check complete. We move on to data cleaning / verification stage.
The code chunk below will include multiple pipe operations, explained
below, step by step. We will store the clean manipulated data in a new
data frame called cleaned_cyclistic_data. Then, we will select the
columns that are pertinent for our analysis (omitting the latitude and
longitude location data) Then, we will omit all n/a (blank/empty values)
Then, add new columns using the mutate function that list the date,
month name & weekday of each ride, as we might need to aggregate ride
data for each of these Then, create a trip duration column using the
difference in time between the started_at and ended_at trip columns (in
minutes), formatted as a numeric data type

``` r
cleaned_cyclistic_data <- aggregate_dataframe %>%
  select("ride_id", "rideable_type", "started_at", "ended_at",
         "start_station_name", "end_station_name", "member_casual") %>%
  na.omit() %>%
  mutate(date = as.Date(started_at),
         month = format(as.Date(started_at), "%B"),
         weekday = format(as.Date(started_at), "%A"),
         trip_duration = as.numeric(difftime(ended_at, started_at, units = "mins")))
```

perform data check of the new trip_duration column

``` r
min(cleaned_cyclistic_data$trip_duration)
```

    ## [1] -55.4257

``` r
max(cleaned_cyclistic_data$trip_duration)
```

    ## [1] 1509.367

min and max functions reveal erroneous data - trip duration cannot be
negative, and trip duration longer than one day is not relevant to this
analysis (probably bikes being removed for servicing or similar reasons)
we will store the filtered data in a new data frame called
filtered_cyclistic_data. select all original columns, plus the six newly
generated columns then filter out the undesirable results using the
filter function so that 1 minute \<= duration \<= 1 day

``` r
filtered_cyclistic_data <- cleaned_cyclistic_data %>%
  select("ride_id", "rideable_type", "started_at", "ended_at",
         "start_station_name", "end_station_name", "member_casual", "date", "month", "weekday", "trip_duration") %>% 
  filter(trip_duration >= 1, trip_duration <= (24*60))
```

#### Verification

let us do a quick verfication check of the cleaned data

are there any N/A values remaining?

``` r
colSums(is.na(filtered_cyclistic_data))
```

    ##            ride_id      rideable_type         started_at           ended_at 
    ##                  0                  0                  0                  0 
    ## start_station_name   end_station_name      member_casual               date 
    ##                  0                  0                  0                  0 
    ##              month            weekday      trip_duration 
    ##                  0                  0                  0

this confirms there are 0 N/A values

We then proceed to check if there are any duplicate “ride_id” entries
and remove them

``` r
any(duplicated(filtered_cyclistic_data$ride_id))
```

    ## [1] TRUE

duplicate IDs exist so let us remove those by using the distinct
function and assigning the output to a second filtered data frame

``` r
filtered_df_v2 <- filtered_cyclistic_data %>%
  distinct(ride_id, .keep_all=TRUE)
```

121 duplicate IDs have been removed so let us run the duplicate check
again

``` r
any(duplicated(filtered_df_v2$ride_id))
```

    ## [1] FALSE

returned result is FALSE, so no duplicates exist

recheck the trip_duration values to ensure that time frame is between 1
minute and 24 hours

``` r
min(filtered_df_v2$trip_duration)
```

    ## [1] 1

``` r
max(filtered_df_v2$trip_duration)
```

    ## [1] 1439.833

duration is confirmed as being between 1 and 1439 minutes

dataset has been reduced in size from 5906269 to 4202340 rows, which is
approx 29%

Lastly, we want to check the structure of our new data frame and see if
there are data types that do not match our column type

``` r
str(filtered_df_v2)
```

    ## tibble [4,202,340 × 11] (S3: tbl_df/tbl/data.frame)
    ##  $ ride_id           : chr [1:4202340] "84BFC1F137684EAB" "EEC92D30A70471E5" "1C33464DEEB1F23C" "E0A61810C305E5EC" ...
    ##  $ rideable_type     : chr [1:4202340] "classic_bike" "classic_bike" "electric_bike" "classic_bike" ...
    ##  $ started_at        : POSIXct[1:4202340], format: "2023-12-02 23:12:51" "2023-12-14 13:43:14" ...
    ##  $ ended_at          : POSIXct[1:4202340], format: "2023-12-02 23:21:01" "2023-12-14 13:44:14" ...
    ##  $ start_station_name: chr [1:4202340] "DuSable Museum" "California Ave & Division St" "Chicago State University" "Cottage Grove Ave & 51st St" ...
    ##  $ end_station_name  : chr [1:4202340] "Cottage Grove Ave & 51st St" "California Ave & Division St" "Chicago State University" "Cottage Grove Ave & 51st St" ...
    ##  $ member_casual     : chr [1:4202340] "member" "casual" "casual" "casual" ...
    ##  $ date              : Date[1:4202340], format: "2023-12-02" "2023-12-14" ...
    ##  $ month             : chr [1:4202340] "December" "December" "December" "December" ...
    ##  $ weekday           : chr [1:4202340] "Saturday" "Thursday" "Monday" "Monday" ...
    ##  $ trip_duration     : num [1:4202340] 8.17 1 16.92 1.57 2.57 ...
    ##  - attr(*, "na.action")= 'omit' Named int [1:1661547] 1 2 3 4 5 6 7 8 9 10 ...
    ##   ..- attr(*, "names")= chr [1:1661547] "1" "2" "3" "4" ...

data types are confirmed to be correct, so we can move on to the analyse
stage

## Step 4: Analyse

Now lets go back to our business question and try to answer it: How do
annual members and casual riders use Cyclistic bikes differently?

With our data, we can extract key information that will help us answer
this question. Here’s how we can approach it using the available data:

#### Comparing the number of rides per month

We can analyze and compare the monthly ride counts between casual riders
and members.

let us use ggplot2 to visualise this data as a bar graph: the factor
function reorders the months chronologically the position=“dodge”
function arranges the columns for rider type side by side, rather than
stacked the labs(fill) function is the legend formatting function the
scale_y_continuous function formats the y axis scale from exponential to
hundreds of thousands, to make it easier to interpret for the average
stakeholder / employee

<img src="Title_files/figure-gfm/plotting the monthly riders bar graph-1.png" width="150%" />

The hotter period of the year (especially the months of June, July,
August, September) have the highest number of rides for casual riders
and members Member numbers remain high from May-October, an even longer
period This pattern suggests that around the summer season, when there
is typically sunnier weather/less rainfall, bike usage tends to increase
This attracts both casual riders and members to utilize the bikes more
frequently

#### Now, we can also compare bike usage on days of the week

We can discover how casual riders and members differ in their bike usage
on different days of the week using a similar approach instead of using
the position=“dodge” function, we will use facet_wrap to seperate the
data for casual and member riders into 2 individual graphs the
guides(fill=“none”) argument removes the legend, which is not necessary

<img src="Title_files/figure-gfm/plotting the bar graph for daily rider data-1.png" width="150%" />

By analyzing the two graphs, we can clearly observe a distinct
difference in bike usage between casual riders and members Casual riders
usage tends to peak on weekends. This could indicate that casual riders
are those people who are likely to use the bikes for the purpose of
leisure / recreational activities / exploration during their free time
Members bike usage shows a gradual peak during weekdays. It also shows
higher and more consistent use overall. This implies that members use
the bikes for their transportation or work commute

#### Next, let us use ggplot2 to visualise the top 5 most popular start and end stations

If working with tableau, I would creates heatmaps of this data, but
within R some simple bar graphs will suffice First let us create two new
dataframes to reorder the data, called top_five_start and top_five_end

``` r
top_five_start <- filtered_df_v2 %>% 
  group_by(start_station_name, member_casual) %>% 
  summarize(row_count = n()) %>% 
  arrange(desc(row_count))
```

    ## `summarise()` has grouped output by 'start_station_name'. You can override
    ## using the `.groups` argument.

``` r
top_five_end <- filtered_df_v2 %>% 
  group_by(end_station_name, member_casual) %>% 
  summarize(row_count = n()) %>% 
  arrange(desc(row_count))
```

    ## `summarise()` has grouped output by 'end_station_name'. You can override using
    ## the `.groups` argument.

![](Title_files/figure-gfm/plotting%20the%204%20bar%20graphs%20for%20start%20&%20end%20stations,%20for%20both%20casual%20and%20member%20riders-1.png)<!-- -->![](Title_files/figure-gfm/plotting%20the%204%20bar%20graphs%20for%20start%20&%20end%20stations,%20for%20both%20casual%20and%20member%20riders-2.png)<!-- -->![](Title_files/figure-gfm/plotting%20the%204%20bar%20graphs%20for%20start%20&%20end%20stations,%20for%20both%20casual%20and%20member%20riders-3.png)<!-- -->![](Title_files/figure-gfm/plotting%20the%204%20bar%20graphs%20for%20start%20&%20end%20stations,%20for%20both%20casual%20and%20member%20riders-4.png)<!-- -->

Upon looking at the bar charts, it is apparent that both casual riders
and members exhibit distinct top 5 stations Implies that while the
specific stations may differ between the two groups, there *is*
consistency We can focus on that consistency when it comes to
advertising campaigns and increasing revenue from both groups

Interestingly, the starting stations and ending stations for each group
are almost identical - Top 4 “members” start & end stations are the
same, with only \#5 being a different station All 5 “casual” riders
start & end stations are the same, with just a reversal in order for \#3
and \#4 most popular stations Member riders are far more evenly
distributed between the most popular stations - only a few thousand
riders seperate \#1 and \#5 Whereas casual riders hugely prefer starting
and ending journeys at “Streeter Drive & Grand Avenue” They are almost
twice as numerous at \#1 compared to \#2-#5

#### Next, we can perform trip duration analysis. We can compare the trip lengths of casual riders and annual members

This analysis can provide insights into the average duration of rides
for each group

``` r
filtered_df_v2 %>% 
  group_by(member_casual) %>% 
  summarise(mean(trip_duration))
```

    ## # A tibble: 2 × 2
    ##   member_casual `mean(trip_duration)`
    ##   <chr>                         <dbl>
    ## 1 casual                         24.2
    ## 2 member                         12.6

Running the above code returns the result that casual riders use the
service for TWICE as long as member riders (24.2 mins vs 12.6 mins) This
result further supports the theory that casual riders use the bikes for
leisure/recreation, and members use them for commuting purposes We have
derived valuable insights from analysis so we can move on to the final
“Act” stage

The advertising team should take a 3 pronged approach:

1)  “Summer Spike” - deploy a seasonal advertising campaign in April /
    May to capitalize on the predicted uptick in bike usage during the
    hotter half of the year
2)  “The Big 5” - increased advertising at the most frequently used
    stations to take advantage of their popularity / high traffic for
    each rider type
3)  “Casual Courting” - enhance the appeal of weekend riding for casual
    riders by tying weekend bike rentals to other activities (e.g. using
    coupons for other businesses), or by offering weekend discounts or
    promotional offers

\##Share & Act

In reality, this is the stage where these findings would be presented to
the shareholders - the founder Lily Moreno and the executive team. After
answering questions and taking feedback, we would either revisit and
adapt the process and do further analysis, or proceed to act on the
recommendations put forward.

This denotes the end of my first case study. Woohoo!
