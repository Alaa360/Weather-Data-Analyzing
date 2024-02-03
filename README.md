# The Weather Project

The Weather data has some of Date/Time, Temperature C, Wind Speed, Visibility and Weather. 

Using Jupyter Notebook to dig deep in the Weather Dataset. Analyzed and interpreted data from 1000+ weather data records to identify weather in each date.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) or use the [Conda](https://conda.io/en/latest/) package manager


```bash
pip install pandas
pip install matplotlib
```
```bash
conda install pandas
conda install matplotlib
```

## Usage

```python
import pandas as pd
import matplotlib.pyplot as plt
```

## What does the Data show?

+ All the unique 'Wind Speed' values in the data.
+ No. of times when the weather was exactly 'Clear'.
+ No. of times when the wind speed was exactly 4 km/h.
+ Renaming column name from 'Weather' to 'Weather Condition'.
+ Calculating the mean of (Visibility).
+ All instances when 'Wind Speed is above 24' and 'Visibility is 25'.
+ Mean value of each column against each (Weather Condition).
+ Maximum and Minimum value of each column against 'Weather Condition'.
+ Records when the Weather Condition is fog.
+ All Instances when 'Weather is Clear' or 'Visibility is above 40'
+ All instances when:
"Weather is Clear" and "Relative Hum is greater than 50" OR "Visibility is above 40"

---


 
