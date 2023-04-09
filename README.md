# Ex03-Univariate-Analysis
### AIM:
To read the given data and perform the univariate analysis with different types of plots.

 ### ALGORITHM:
### STEP 1:
Read the given data.

### STEP 2:
Get the informations and type of datas.

### STEP 3:
Count the values using value_counts().

### STEP 4:
Describe the dataframe.

### STEP 5:
Do plots like boxplots,countplot,distribution plot,histogram plot

### PROGRAM:
### diabetes.csv
```
Developed by: D.Vinitha
Reference number:212222230175

import pandas as pd
data1=pd.read_csv("/content/diabetes.csv")
df1=pd.DataFrame(data1)
df1.info()
df1.dtypes
df1['BloodPressure'].value_counts()
df1.describe()
import seaborn as sns
sns.boxplot(x='BMI',data=df1)
sns.countplot(x='Age',data=df1)
sns.distplot(df1['BMI'])
sns.histplot(x='Age',data=df1)
df1.skew()
df.kurtosis()
```
### SuperStore.csv
```
import pandas as pd
data2=pd.read_csv("/content/SuperStore (1).csv")
df2=pd.DataFrame(data2)
df2.info()
df2.dtypes
df2["Postal Code"].value_counts()
df2.describe()
import seaborn as sns
sns.boxplot(x='Sales',data=df2)
sns.countplot(x="Sales",data=df2)
sns.distplot(df2['Sales'])
sns.histplot(x="Sales",data=df2)
df2.skew()
```
### OUTPUT
### diabetes.csv
### Info
![Screenshot 2023-04-09 210422](https://user-images.githubusercontent.com/121166004/230782382-ed8ce7dd-f5e5-4f4d-951f-512bc5c6b50d.png)

### Datatypes
![Screenshot 2023-04-09 210432](https://user-images.githubusercontent.com/121166004/230782404-2d29dda2-3312-4d63-ac7c-95305f356b68.png)

### value count
![Screenshot 2023-04-09 210449](https://user-images.githubusercontent.com/121166004/230782417-bf2a41f6-2d9a-4de4-8da0-c88e5d2cf746.png)

### Describe
![Screenshot 2023-04-09 210500](https://user-images.githubusercontent.com/121166004/230782478-69cbbec0-63a3-46fd-ae79-3f1631ec16b1.png)

### box plot
![Screenshot 2023-04-09 210525](https://user-images.githubusercontent.com/121166004/230782514-2ea74448-4749-47fa-9e55-bba366e3c641.png)

### countplot
![Screenshot 2023-04-09 210536](https://user-images.githubusercontent.com/121166004/230782541-5f72e6b6-262b-4b6c-9fe1-341039ab914e.png)

### Distribution plot

![Screenshot 2023-04-09 210548](https://user-images.githubusercontent.com/121166004/230782735-776232c8-968e-4764-827c-8380b65670b5.png)

### histogram

![Screenshot 2023-04-09 210614](https://user-images.githubusercontent.com/121166004/230782786-38750593-588f-4186-b1f7-82abf812dc49.png)

### skew()
![Screenshot 2023-04-09 210624](https://user-images.githubusercontent.com/121166004/230782834-24706676-b2da-4547-a235-43cd0c280a25.png)


### kurtosis()
![Screenshot 2023-04-09 210652](https://user-images.githubusercontent.com/121166004/230782853-16ca3929-433f-40cd-b0c3-70c1e3a87c02.png)


### SuperStore.csv
### Info
![Screenshot 2023-04-09 210744](https://user-images.githubusercontent.com/121166004/230782884-d7636dd0-b79e-42fc-b0eb-ec6d1f572611.png)

### Datatypes
![Screenshot 2023-04-09 210804](https://user-images.githubusercontent.com/121166004/230782935-d4e0afd2-cf90-4798-b9e8-908d9954293d.png)


### Valuecounts
![Screenshot 2023-04-09 210813](https://user-images.githubusercontent.com/121166004/230783030-44f9c2d6-376f-4b33-acad-cd51752f2e25.png)


### Describe
![Screenshot 2023-04-09 210821](https://user-images.githubusercontent.com/121166004/230783046-04c38c98-c484-417b-b722-4c475fe4d1de.png)


### Boxplot
![Screenshot 2023-04-09 210829](https://user-images.githubusercontent.com/121166004/230783074-06559e5e-1be3-457b-b2cb-fdc972722469.png)


### Countplot
![Screenshot 2023-04-09 210838](https://user-images.githubusercontent.com/121166004/230783097-071f5453-55ff-4cbe-9a51-4463c7dfa309.png)


### Distribution plot
![Screenshot 2023-04-09 210857](https://user-images.githubusercontent.com/121166004/230783119-aafe3fdd-52dd-4b60-80a4-a7fad1a1226f.png)


### Histogram plot
![Screenshot 2023-04-09 210904](https://user-images.githubusercontent.com/121166004/230783140-794cc086-b361-44a2-af00-93044c8c78be.png)


### skew()
![Screenshot 2023-04-09 210912](https://user-images.githubusercontent.com/121166004/230783165-628f657a-ced4-42eb-ba0a-656fbb784e05.png)


### RESULT
To read the given data and perform the univariate analysis with different types of plots is done successfully.
