# For executing the two jupyter notebooks click 'Run All Cells' and the entire notebook will be executed. All the cells have been already run and outputs are properly visible.

# The Random Forest Regressor model with hyper-parameter tuning in the 'Appliances Energy.ipynb' took 20 to 25 minutes to run. So, similar runtime can be expected for any other system.

# The libraries required for 'Appliances Energy.ipynb' are:
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split, GridSearchCV
from sklearn.linear_model import LinearRegression, Ridge, Lasso
from sklearn.ensemble import RandomForestRegressor
from sklearn.metrics import mean_squared_error, r2_score, mean_absolute_error
import statistics as stats
import math
import sys
import plotly.express as px

