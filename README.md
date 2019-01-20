# Population distribution using OpenStreetMap

Allowed you to create a distribution map of the population using buildings coordinates with OpenStreetMap

## Getting Started

To run this program you need to generate un .json file with buildings's coordinates of city or a neighborhood. I used download a map from openstreetmap and then get the .json file using Spatial Management Desktop and the using MapShaper

### Prerequisites

import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib as plt
import json
from shapely.geometry import Polygon
import matplotlib.pyplot as plt
import geopandas as gpd
from numpy.random import RandomState, uniform
from shapely.geometry import Point
from shapely.geometry import shape 
import shapefile


### Installing


## Running the tests

To run a test, you need the write your .json's file name and write the number of the population of the area

### Break down into end to end tests

At the end, you will get a coordinate file with all the population projected in  buildings

```


## Built With

pandas
seaborn
matplotlib

from shapely.geometry import Polygon
import matplotlib.pyplot as plt
geopandas
import shapefile


## Contributing

(https://github.com/agaidus/census_data_extraction/blob/master/census_mapper.py

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Hugo Schoen ** 


