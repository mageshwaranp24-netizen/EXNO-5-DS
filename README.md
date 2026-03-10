# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
import seaborn as sns
import pandas as pd

df=pd.read_csv("iris.csv")
df.head()
df.corr()
sns.heatmap(df.corr())
sns.jointplot(x='sepal_length',y='sepal_width',data=df,kind='hex')
sns.jointplot(x='sepal_length',y='sepal_width',data=df,kind='reg')
sns.pairplot(df)
sns.pairplot(df,hue='sepal_length')
sns.distplot(df['sepal_length'])
sns.distplot(df['sepal_length'],kde=False,bins=10)
## Count plot

sns.countplot(x='sepal_width',data=df)
## Count plot

sns.countplot(y='sepal_width',data=df)
## Bar plot
sns.barplot(x='sepal_width',y='petal_width',data=df)
## Bar plot
sns.barplot(x='petal_width',y='sepal_width',data=df)
df.head()
sns.boxplot(x='sepal_width', data=df)
sns.boxplot(x="sepal_width", y="petal_width", data=df,palette='Set1')
sns.boxplot(data=df,orient='h')
# categorize my data based on some other categories

sns.boxplot(x="sepal_width", y="petal_width", hue="sepal_width",data=df)
sns.violinplot(x="petal_width", data=df,palette='Set2')

```

# Result:
<img width="1920" height="1080" alt="Screenshot (176)" src="https://github.com/user-attachments/assets/da3b829a-8c9e-4782-8389-dfe285706011" />
<img width="1920" height="1080" alt="Screenshot (177)" src="https://github.com/user-attachments/assets/05eb039d-4937-4613-9707-5394c3a4a753" />
<img width="1920" height="1080" alt="Screenshot (178)" src="https://github.com/user-attachments/assets/4f79e821-39d9-42be-b625-65ffd1e0316e" />
<img width="1920" height="1080" alt="Screenshot (179)" src="https://github.com/user-attachments/assets/96087038-ef44-4095-a4e5-a668dcfec0b1" />
<img width="1920" height="1080" alt="Screenshot (180)" src="https://github.com/user-attachments/assets/b2fed6b4-819c-4434-9bfd-8070247b6d10" />
<img width="1920" height="1080" alt="Screenshot (181)" src="https://github.com/user-attachments/assets/147dd599-b209-41e7-ac6d-e112ad226618" />
<img width="1920" height="1080" alt="Screenshot (182)" src="https://github.com/user-attachments/assets/b31bca8a-820a-4ad4-a405-e8923da7e947" />
<img width="1920" height="1080" alt="Screenshot (183)" src="https://github.com/user-attachments/assets/a2e6fa41-c2ac-4c1d-8ac9-a8818edf05d2" />
<img width="1920" height="1080" alt="Screenshot (184)" src="https://github.com/user-attachments/assets/62eb6bb3-6046-4ad8-b736-a89a14774892" />
<img width="1920" height="1080" alt="Screenshot (185)" src="https://github.com/user-attachments/assets/4a6e4b74-73ee-4f74-9208-267187caae56" />
<img width="1920" height="1080" alt="Screenshot (186)" src="https://github.com/user-attachments/assets/b4504993-74ba-43ee-acb1-287cfe5fb0b9" />
<img width="1920" height="1080" alt="Screenshot (187)" src="https://github.com/user-attachments/assets/a5c1b89c-211f-4fc5-8655-91206491e79e" />
<img width="1920" height="1080" alt="Screenshot (188)" src="https://github.com/user-attachments/assets/40fd4dd0-8327-4933-a837-d89138011cac" />
<img width="1920" height="1080" alt="Screenshot (189)" src="https://github.com/user-attachments/assets/0499d1fd-83fd-4cd5-914c-472515725d93" />
<img width="1920" height="1080" alt="Screenshot (190)" src="https://github.com/user-attachments/assets/9f1a240d-d22f-4288-9274-2ce591fad182" />
<img width="1920" height="1080" alt="Screenshot (191)" src="https://github.com/user-attachments/assets/449347ac-7dae-44ef-8f5f-fb918e7a991d" />









 
