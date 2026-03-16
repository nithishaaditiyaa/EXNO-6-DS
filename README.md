# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding :

Import required Libraries:
```
import seaborn as sns
import pandas as pd

```

Read the CSV File:

```
df=pd.read_csv("iris.csv")
df.head()

```

Join Plot:

```

sns.jointplot(x="petal_length", y="petal_width", data=df, kind="hex")

```

Pair PLot:

```

sns.pairplot(data=df, vars=["sepal_length","sepal_width"], hue="species")

```

Dist Plot:

```

sns.displot(df["petal_length"], kde=True)

```

Count Plot:

```

sns.countplot(y="species", data=df)

```

Box Plot:

```
sns.boxplot(x="species", y="petal_length", data=df)

```

Bar Plot:

```

sns.barplot(x="species", y="petal_length", data=df)

```

Violin Plot

```

sns.violinplot(x="species", y="petal_length", data=df)

```

# Result:
 Include your result here
