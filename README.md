# Students Performance Analysis



## About Dataset
The dataset contained scores of `51 students` in `12 tests` conducted in a specific time frame (not mentioned in dataset). The dataset has been sourced from [Kaggle](https://www.kaggle.com/datasets/yapwh1208/students-score) under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) liscence.


## Dataset Features
- `Student_ID` : ID of individual students.
- `Test_1`, `Test_2`..... `Test_12` : Scores of individual students in different tests.


## Cleaning Dataset
The dataset is cleaned, all the test scores are normalized and numeric with no null values.


## Code & Analysis
Libraries used
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import klib
```
- Skewness for all the test scores are almost around zero, showing a kind of gaussian distribution suggesting a symmetrical distribution of test scores, with the majority of scores concentrated around the mean and approx equal number of scores on both sides.
- The average score in the tests shows a declining trend from Test_1 to Test_10 and a slight increase from Test_10 to Test_12, indicating decreasing enthusiasm and excitement for studies as the academic year progresses.
- The tests exhibit an increasing positive correlation towards test_12, indicating a higher level of correlation and interdependence among the tests. This shows that the tests were conducted for continous chapters in an academic year.
- Students with IDs 22000, 22031 and 22032 performed the best while 22022, 22005, 22010 and 22013 performed the worst.
