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

Output :

<img width="719" height="581" alt="Screenshot 2026-03-16 195335" src="https://github.com/user-attachments/assets/02c564b8-fdd5-4cc8-8c3b-db9fb14a8ca9" />
<img width="731" height="578" alt="Screenshot 2026-03-16 195328" src="https://github.com/user-attachments/assets/0f8ef18c-c959-41e6-b724-c185957e9db1" />
<img width="728" height="570" alt="Screenshot 2026-03-16 195322" src="https://github.com/user-attachments/assets/7ebd7fec-ecb8-447e-99eb-61e86d6aecf3" />
<img width="798" height="574" alt="Screenshot 2026-03-16 195316" src="https://github.com/user-attachments/assets/15c31592-ffdf-4c7a-99e5-d372602a9fa6" />
<img width="656" height="655" alt="Screenshot 2026-03-16 195309" src="https://github.com/user-attachments/assets/5d8a5ff7-c983-4d81-a542-1488be8b2577" />
<img width="818" height="647" alt="Screenshot 2026-03-16 195302" src="https://github.com/user-attachments/assets/60476c0e-641d-4327-8ce8-f01df29d3a9e" />
<img width="734" height="734" alt="Screenshot 2026-03-16 195255" src="https://github.com/user-attachments/assets/dbbb1fe6-62f6-4f93-ad08-dad12ddcb4b9" />
<img width="1031" height="263" alt="Screenshot 2026-03-16 195228" src="https://github.com/user-attachments/assets/d4c9a1be-1a0a-46bc-91fc-6c50c978d2fc" />



# Result:
 Include your result here
