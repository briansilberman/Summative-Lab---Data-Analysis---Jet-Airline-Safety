# Aviation Accident Analysis

Imagine you are part of a consulting firm tasked with analyzing the safety of commercial and passenger jet airlines. The client (an airline/airplane insurer) is 
interested in knowing what types of aircraft (makes/models) exhibit low rates of destruction and low likelihood of fatal or serious passenger injuries in the 
event of an accident. They are also interested in any general variables/conditions that might be at play. Your analysis will be based on aviation accident data 
accumulated from the years 1948-2023.

Our client is only interested in airplane makes/models that are professionally built and could still be active. Assume a maximum lifetime of 40 years for a make/
model retirement, and make sure to filter your data accordingly (i.e., from 1983 onward). They would also like separate recommendations for small aircraft vs. 
larger passenger models. In addition, make sure that the claims that you make are statistically robust and that you have enough samples when making comparisons 
between groups.

In this summative assessment, you will demonstrate your ability to:

- Use Pandas to load, inspect, and clean the dataset appropriately.
- Transform relevant columns to create measures that address the problem at hand.
- Conduct EDA: visualization and statistical measures to understand the structure of the data systematically.
- Recommend a set of airplanes that conform to the client's request and identify at least two factors contributing to airplane safety. You must provide supporting
evidence (visuals, summary statistics, tables) for each claim you make.

### Summary of Analysis Findings:
After completing my analysis, Boeing and Airbus are both very injury-safe manufacturers for small planes, and Boeing and Embraer can be relied upon for large 
planes. The makers safest from airplane destruction are also Boeing and Embraer for large planes, and Luscombe, Stinson, and Taylorcraft for small planes. Many of 
the popular airplane models are safe from injury, including Boeing 777s, Boeing 787s, Airbus A320s, Airbus A321s, and Airbus A330s. Bad weather causes higher risk 
of serious or fatal injuries during crashes, as well as higher risk for airplane destruction in the event of a crash landing. The most dangerous flight phases are 
maneuvering, climb, and descent.