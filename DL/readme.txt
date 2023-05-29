
import numpy as np
import pandas as pd
boston = pd.read_csv('/content/boston.csv')
data = pd.DataFrame(boston)
#First look at the data
data.head()
