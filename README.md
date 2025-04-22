# linear-regression-model
   1.	Loading the Data
A CSV file containing two columns, X and Y, is read into a Pandas DataFrame.
	2.	Exploratory Data Analysis (EDA)
The dataset is inspected using .head(), .tail(), and .sample() to view sample records. Basic information such as shape, column types, and summary statistics is obtained using .info() and .describe().
	3.	Handling Missing Values
Null values are checked and handled. Missing numerical values are imputed with the column mean. An additional approach also includes dropping rows with nulls.
	4.	Removing Duplicates
Duplicate rows are identified and removed to maintain data integrity.
	5.	Outlier Detection and Removal
The Interquartile Range (IQR) method is used to detect outliers. Boxplots are used to visualize the data before and after outlier removal.
	6.	Feature Scaling
	•	MinMaxScaler: Scales numerical features to a [0, 1] range.
	•	StandardScaler: Standardizes features by removing the mean and scaling to unit variance (mean = 0, std = 1).
