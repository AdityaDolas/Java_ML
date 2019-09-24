# Java_ML

# Step 1: Download Weka library
## Download page: http://www.cs.waikato.ac.nz/ml/weka/snapshots/weka_snapshots.html
## Download stable.XX.zip, unzip the file, add weka.jar to your library path of Java project in Eclipse.

# Step 2: Prepare Data
## Create a txt file "weather.txt" by following the following format:
@relation weather

@attribute outlook {sunny, overcast, rainy}
@attribute temperature numeric
@attribute humidity numeric
@attribute windy {TRUE, FALSE}
@attribute play {yes, no}

@data
sunny,85,85,FALSE,no
sunny,80,90,TRUE,no
overcast,83,86,FALSE,yes
rainy,70,96,FALSE,yes
rainy,68,80,FALSE,yes
rainy,65,70,TRUE,no
overcast,64,65,TRUE,yes
sunny,72,95,FALSE,no
sunny,69,70,FALSE,yes
rainy,75,80,FALSE,yes
sunny,75,70,TRUE,yes
overcast,72,90,TRUE,yes
overcast,81,75,FALSE,yes
rainy,71,91,TRUE,no

# Step 3: Training and Testing by Using Weka

## This code example use a set of classifiers provided by Weka. It trains model on the given dataset and test by using 10-split cross validation.I will explain each classifier later as it is a more complicated topic.



