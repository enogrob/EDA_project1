### Exploratory Data Analysis
#### Project 1
In order to get the graphics do the following:

1. Download the scripts (plit1.R, plot2.R, plot3.R, plot4.R) to a local directory.

2. Download the data from(see below) and save in in `data`:
<https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip>

```r
if (!file.exists("data")) dir.create("data")
fileUrl <- "https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2Fhousehold_power_consumption.zip"
download.file(fileUrl,destfile="data/household_power_consumption.zip", method="wget")
```

3. Unzip the file into the `data` subdirectory.

```r
unzip("data/household_power_consumption.zip", exdir="data")
```

4. Run the scripts accordingly.

```r
source("plot1.R")
source("plot2.R")
source("plot3.R")
source("plot4.R")
```

