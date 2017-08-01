# Udacity-Lesson6-MiniProject2

Makeover of the infographics:

How India Eats 
From HUFF POST INDIA
Source: Union Goverment's Sample Registration System Baseline Survey 2014.
Link: http://viz.wtf/image/162284459410

Further References used:
Indian States:  https://en.wikipedia.org/wiki/Administrative_divisions_of_India#Zones

Data captured from initial graph, State-Code has been extended with full State name

Code    State                   Vegetarians Non Vegetarians
JK      Jammu and Kashmir       31.45       68.55
PB      Punjab                  66.75       33.25
UK      Uttarakhand             27.35       72.65
HR      Haryana                 69.25       30.75
DL      Delhi                   39.5        60.5
RJ      Rajasthan               74.9        25.1
UP      Uttar Pradesh           47.1        52.9
GJ      Gujarat                 60.95       39.05
MP      Madhya Pradesh          50.6        49.4
BR      Bihar                   7.55        92.45
AS      Assam                   20.60       79.4
JH      Jharkhand               3.25        96.75
WB      West Bengal             1.4         98.6
MH      Maharashtra             40.2        59.8
CG      Chhattisgarh            17.95       82.05
OD      Odisha                  2.65        97.35
TS      Telangana               1.3         98.7
KA      Karnataka               21.1        78.9
AP      Andhra Pradesh          1.75        98.25
KL      Kerala                  3           97
TN      Tamil Nadu              2.35        97.65


Things I would like to improve compared to the original visualization:
* Overlapping bubble difficult to understand - use a simple bar chart instead
* Abbreviations in region names - use full state name instead
* Numbers with varying decimal places - just show rounded percentages
* not all numbers sum up too 100% (change GJ Non Veggies from 39.45 to 39.05) - data to be corrected

What I could not (yet) do:
* Assign data to a map (still need to learn more about dimple.js, d3.js, and DataMaps: http://datamaps.github.io/)
* In the end I would like to color the different states of India according to the percentage of vegetarians (color scale from green to red), 
  so that I can visualize the north west to east change from vegetarians to non-vegetarians in a simple manner.
