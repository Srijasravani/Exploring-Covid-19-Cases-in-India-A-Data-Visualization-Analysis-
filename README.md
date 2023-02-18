# Covid-19
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
data = pd.read_csv(r"Latest Covid-19 India Status.csv")
data.head()
sns.relplot(x='Population',y='Total Cases', hue='Discharged',data=data)
sns.pairplot(data)
sns.catplot(x='Death Ratio',y='Total Cases', hue='Discharged',data=data)
