# Introduction

This project provides data and visualization on the representation of former members of the National Socialist German Workers' Party (NSDAP) in the German Bundestag (Federal Parliament) during the Federal Republic of Germany.

# Data

The data on the representation of former NSDAP members in the German Bundestag is available in csv format at the following URL: https://github.com/danielkuhlen/nsdapmembers.bundestag/blob/master/btmembernazi.csv

## Downloading the Data in R

To download the dataset in R, you can use the `read.csv` function from the base R library.

Here is an example of how to use the `read.csv` function to download the data:

```
nsdap_data <- read.csv("https://github.com/danielkuhlen/nsdapmembers.bundestag/blob/master/btmembernazi.csv")
```

## Downloading the Data in Python

In Python, you can use the `pandas` library to download and read the csv file. To do this, you can use the `read_csv` function from the `pandas` library.

Here is an example of how to use the `read_csv` function to download the data in Python:

```
import pandas as pd

nsdap_data = pd.read_csv("https://github.com/danielkuhlen/nsdapmembers.bundestag/blob/master/btmembernazi.csv")
```

## Downloading the Data in Stata

In Stata, you can use the `import delimited` command to download and read the csv file. 
Here is an example of how to use the `import delimited` command to download the data in Stata:

```stata
import delimited "https://github.com/danielkuhlen/nsdapmembers.bundestag/blob/master/btmembernazi.csv", clear
```

# Citation

If you use this repository or its contents in your work, please cite it as follows:

Kuhlen, Daniel. (2023). nsdapmembers.bundestag: Data and visualization on the representation of former NSDAP members in the German Bundestag. GitHub repository. https://github.com/danielkuhlen/nsdapmembers.bundestag


