# Data Cleansing and Manipulation
The repository contains my data cleansing and manipulation projects using various tools, techniques and logics in python. Please view the readme section of each project for more details. 

## Libraries that I have used are as follows:
* `csv`
* `pandas`
![Pandas](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/pandas.png "Pandas")
* `numpy`
![NumPy](https://github.com/kennyfahad/Data-Visualization/blob/main/Data/numpy.png "NumPy")

* 'datetime`

* `Beautiful Soup`
![Beautiful Soup](https://github.com/kennyfahad/Data-Visualization/blob/main/Databs4.jpeg "Beautiful Soup")


# [Data Cleansing using basic Python Operations](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/blob/main/Data%20Cleansing%20through%20basic%20Python%20Techniques.ipynb)

## Museum of Modern Art Collection
The Museum of Modern Art (MoMA) acquired its first artworks in 1929, the year it was established. Today, the Museum’s evolving collection contains almost 200,000 works from around the world spanning the last 150 years. The collection includes an ever-expanding range of visual expression, including painting, sculpture, printmaking, drawing, photography, architecture, design, film, and media and performance art.

MoMA is committed to helping everyone understand, enjoy, and use our collection. The Museum’s website features 72,706 artworks from 20,956 artists. The artworks dataset contains 130,262 records, representing all of the works that have been accessioned into MoMA’s collection and cataloged in our database. It includes basic metadata for each work, including title, artist, date, medium, dimensions, and date acquired by the Museum. Some of these records have incomplete information and are noted as “not curator approved.” 

The follwoing work is down on the artiest dataset which contains 16,730 records, representing all the artists who have work in MoMA's collection and have been cataloged in MOMA's database. The dataset includes information about 'Title', 'Artist', 'Nationality', 'BeginDate', 'EndDate', 'Gender', 'Date' and 'Department'. It has been already enhanced from the dataset shared by MOMA which included basic metadata for each artist, including name, nationality, gender, birth year, and death year.

[Data](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/raw/main/Data/data.csv)

[Kaggle Link for more description](https://www.kaggle.com/datasets/momanyc/museum-collection?resource=download)

## Data Cleansing Problems Resolved 
* Unwanted special characters removed
* Standardized datasets to correct datatypes for e.g. `text > int`
* Missing values in 'Nationalities' and 'Gender' identified and replaced
* Dates standardized to address conventional use

### Cleaned dataset is available as csv [(`artists_updated.csv`)](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/blob/main/Data/artists_updated.csv)

# [Data Manipulation through classes definition](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/blob/main/Data%20Manipulation%20through%20classes%20definition.ipynb)

## About Dataset
The sample 2013 dataset consists of 481 records of NBA players and contains the following details:

'player', 'pos', 'age', 'team', 'g', 'gs', 'mp', 'fg', 'fga', 'fg.', 'x3p', 'x3pa', 'x3p.', 'x2p', 'x2pa', 'x2p.', 'efg.', 'ft', 'fta', 'ft.', 'orb', 'drb', 'trb', 'ast', 'stl', 'blk', 'tov', 'pf', 'pts', 'season', 'season_end'

[Data](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/blob/main/Data/nba.csv)

## Problem Statement
* To define different classes for this particular dataset which will be used for various analytics and data manipulation 

## Questions answered through class definition:
* Get full name of player with `.player_name`
* Get playing position of player with `.position` 
* Get name of player's team with `.team`
* Get age of player with `.age`  
* Get Players information in a Team
* Get no. of players in a team with `.num_players`
* Get Average age of players in a team with `.average_age`
* Getting comparison of teams in accordance with average age (Older/ Younger) with `.older_team`

# [DateTime problem resolved](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/blob/main/DateTime_Problem_Resolved.ipynb)

## About Dataset
The dataset has been scraped from The White House Visitor Logs and has been simplified to contain only name,	appt_made_date,	appt_start_date,	appt_end_date,	visitee_namelast,	visitee_namefirst,	meeting_room and	description
This is done to highlihgt and resolve only the datetime problem, which is one of the most prominent problems in datasets.I have used python's `datatime` module.
The `datetime` module supplies classes for manipulating dates and times. While date and time arithmetic is supported, the focus of the implementation is on efficient attribute extraction for output formatting and manipulation.
[Documentation](https://docs.python.org/3/library/datetime.html)

[Data](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/blob/main/Data/potus.csv)

## Problems resolved:
* Extract date from the dataset for date when appointment was made `2014-12-18T00:00:00`
* Extract date as well as time from appointment start `1/6/2015  9:30:00 AM`
* Extract date and time from appointment end `1/6/2015  11:59:00 PM`

The data then can be used to conduct data analytics on appointments with various officials in The White House. 

## Datetime Key
The following datetime key is very helpful:
* %d day in number
* %A day in words
* %a day in words but in aka
* %m month in number
* %B month in words
* %b month in words but in aka
* %Y year in 4 digits
* %y year in 2 digits
* %H  hours in 24 hours format
* %I  hours in 12 hours format
* %p am or pm
* %M minutes 
* %S seconds

# [Data Cleaning with Pandas](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/blob/main/Data%20Cleansing%20with%20Pandas.ipynb)

## About Dataset
The dataset contains information about Fortune 500 companies with following features:
company	rank	revenues	revenue_change	profits	assets	profit_change	ceo	industry	sector	previous_rank	country	hq_location	website	years_on_global_500_list	employees	total_stockholder_equity

## Problem statement:
The Fortune 500 dataset needs to be manipulated in order to deduce meaningful intelligence such as:
* Identification of missing values
* Finding of data elements within the dataset
* Filtering values to get the desired information
* Identifying highest number of employees working in a company
* Top employeers in each country

[Fortune 500 data](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/blob/main/Data/f500.csv)

The Laptops dataset needs to be cleaned to address the following issues:
* Editing column names which will make life easy for analytics
* Converting object types to intiger format
* Renaming columns in accordance with the underlying data
* Extracting information from within the column values
* Removing duplications in same values stored as different text
* Finding and filling missing values in the dataset

[Laptops data](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/blob/main/Data/laptops.csv)

## [Cleaned Laptops data](https://github.com/kennyfahad/Data-Cleansing-and-Manipulation/blob/main/Data/cleaned_laptops.csv)
