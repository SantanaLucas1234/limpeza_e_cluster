!pip install kneed

import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.cluster import KMeans
from sklearn.preprocessing import StandardScaler, OneHotEncoder,LabelEncoder
from kneed import KneeLocator


df=pd.read_csv("/content/shopping_trends.csv")
df.head(1)
