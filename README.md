# codsoft-task1
The Titanic Survival Prediction.

Titanic Prediction task1 #Codsoft #Task1 #internship #datascience

Explanation:

1st:

i used the pandas DataFrame object named “df”. The read_csv function is used to read the CSV file and create a DataFrame object. Head is used to display rows.



2nd:

The shape attribute of a Pandas DataFrame object returns a tuple containing the number of rows and columns in the DataFrame.

The describe method of a Pandas DataFrame object generates descriptive statistics that summarize the central tendency, dispersion, and shape of a dataset’s distribution, excluding NaN values.



3rd:

The countplot function from the Seaborn library to create a bar plot of the number of passengers who survived and did not survive on the Titanic, grouped by passenger class. The x parameter specifies the column in the DataFrame that contains the survival information, while the hue parameter specifies the column that contains the passenger class information.

4th:

Then we group the DataFrame df by the “Sex” column and calculates each group's mean of the “Survived” column. The resulting DataFrame contains two rows, one for each sex, and one column, which is the mean survival rate for that sex.

5th:

 Then we import the LabelEncoder class from the sklearn.preprocessing module. It then creates an instance of the LabelEncoder class named labelencoder. The fit_transform method of the labelencoder object is then called on the “Sex” column of the DataFrame df. This method encodes the values in the “Sex” column as integers and replaces them in the DataFrame. The head method is then called on the DataFrame object to display the first few rows of the data in the DataFrame.

6th:

The isna method of a Pandas DataFrame object returns a DataFrame of the same shape as the original DataFrame, with True values where the original DataFrame has NaN values and False values elsewhere. The sum method is then called on the resulting DataFrame to count the number of missing values in each column.

7th:

Then we drop the Age column, drop means we remove that column, because i only need the passengers class and their gender, to find the prediction of their survival.

8th:

Now create two new variables x and y. The variable x is a DataFrame that contains the “Pclass” and “Sex” columns of the DataFrame df. The variable y is a Series that contains the “Survived” column of the DataFrame df.

9th:

 the predict method of a logistic regression model named log to predict the survival of a passenger on the Titanic based on their passenger class and sex. The predict method takes an array of input values and returns an array of predicted output values. In this case, the input array contains two values, the passenger class and sex of the passenger, and the output array contains a single predicted value, either 0 or 1, which indicates whether the passenger survived or not.

The if-else statement is then used to print a message indicating whether the passenger survived or not based on the predicted value.

Thanks !!
