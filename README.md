# Predicting-Tornadoes

## Project Purpose

The following dataset contains all tornadoes reported in the US from 1950 - 2021. Utilizng this data, we are attempting to identify which factors might be most predictive for identifying the magnitude and location of future tornados.

To achieve this, our team will be investigating the efficiacy of different machine learning models such as decision trees and gradient boosting.

**Project Questions**
Our primary questions coming into this project are as follows:
* What are the common characteristics of different tornado classifications?
* What information can be used be predict tornado magnitude?
* What is most likely magnitude classification for the next tornado?
* Where are tornadoes going to happen in the US?

* ## Dataset Content
Below is a break down of the columns initially including in our dataset
* `om` - a count of tornadoes during the year.
* `yr` - year
* `mo` - month (1-12)
* `dy`  - day (1-31)
* `date` - date in yyyy-mm-dd format
* `time` - time in HH:MM:SS format
* `tz`  - time zone. (All times except for unknown and 9=GMT were converted to 3=GMT)
* `st` - state
* `stf` - state FIPS number
* `stn` - number of this tornado, in this state, in thie year (discontinued in 2008)
* `mag` - F-scale. (EF-scale used after Jan. 2007) Values: -9 (unknown), 0 - 5
* `inj` - injuries
* `fat` - fatalities
* `loss` - estimated property loss information
  * 1 = <$50
  * 2 = \$50-500
  * 3 = \$500 - 5,000
  * 4 = \$5,000 - 50,000
  * 5 = \$50,000 - 500,000
  * 6 = \$500,000 - 5,000,000
  * 7 = \$5,000,000 - 50,000,000
  * 8 = \$50,000,000 - 500,000,000
  * 9 = \$500,000,000
* `closs` - estimated crop loss in millions of dollars (2007 onward)
* `slat` - starting latitude in decimal degrees
* `slon` - starting longitude in decimal degrees
* `elat` - ending latitude in decimal degrees
* `elon` - ending longitutde in decimal degrees
* `len` - length in miles
* `wid` - width in yards
* `ns` - number of states affected by this tornado
* `sn` - state number
* `sg` - tornado segment number
* `f1` - 1st county FIPS score
* `f2` - 2nd county FIPS score
* `f3` - 3rd county FIPS score
* `f4` - 4th county FIPS score
* `fc` - estimated F-scale rating in 2016. Valid for records altered between 1950-1982 (0=unaltered, 1 if previous rating was unknown)

dataset and column descriptions sourced from [kaggle](https://www.kaggle.com/datasets/michaelbryantds/tornadoes)

To explore how we prepared the data for modeling and our machine learning iterations, please see our other notebooks.
