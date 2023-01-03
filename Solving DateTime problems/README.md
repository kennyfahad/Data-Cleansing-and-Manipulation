# About Dataset
The dataset has been scraped from The White House Visitor Logs and has been simplified to contain only name,	appt_made_date,	appt_start_date,	appt_end_date,	visitee_namelast,	visitee_namefirst,	meeting_room and	description
This is done to highlihgt and resolve only the datetime problem, which is one of the most prominent problems in datasets.I have used python's `datatime` module.
The `datetime` module supplies classes for manipulating dates and times. While date and time arithmetic is supported, the focus of the implementation is on efficient attribute extraction for output formatting and manipulation.
[Documentation](https://docs.python.org/3/library/datetime.html)

# Problems resolved:
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