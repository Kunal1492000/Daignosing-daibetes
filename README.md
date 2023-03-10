# Daignosing-daibetes
In this project, you’ll imagine you are a data scientist interested in exploring data that looks at how certain diagnostic factors affect the diabetes outcome of women patients.

You will use your EDA skills to help inspect, clean, and validate the data.

Note: This dataset is from the National Institute of Diabetes and Digestive and Kidney Diseases. It contains the following columns:

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration at 2 hours in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure
SkinThickness: Triceps skinfold thickness
Insulin: 2-Hour serum insulin
BMI: Body mass index
DiabetesPedigreeFunction: Diabetes pedigree function
Age: Age (years)
Outcome: Class variable (0 or 1)



























 Pregnancies  Glucose  BloodPressure  ...  DiabetesPedigreeFunction  Age  Outcome
0            6      148             72  ...                     0.627   50        1
1            1       85             66  ...                     0.351   31        0
2            8      183             64  ...                     0.672   32        1
3            1       89             66  ...                     0.167   21        0
4            0      137             40  ...                     2.288   33        1

[5 rows x 9 columns]
9
768
Pregnancies                 0
Glucose                     0
BloodPressure               0
SkinThickness               0
Insulin                     0
BMI                         0
DiabetesPedigreeFunction    0
Age                         0
Outcome                     0
dtype: int64
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 768 entries, 0 to 767
Data columns (total 9 columns):
Pregnancies                 768 non-null int64
Glucose                     768 non-null int64
BloodPressure               768 non-null int64
SkinThickness               768 non-null int64
Insulin                     768 non-null int64
BMI                         768 non-null float64
DiabetesPedigreeFunction    768 non-null float64
Age                         768 non-null int64
Outcome                     768 non-null object
dtypes: float64(2), int64(6), object(1)
memory usage: 54.1+ KB
None
       Pregnancies     Glucose  ...  DiabetesPedigreeFunction         Age
count   768.000000  768.000000  ...                768.000000  768.000000
mean      3.845052  120.894531  ...                  0.471876   33.240885
std       3.369578   31.972618  ...                  0.331329   11.760232
min       0.000000    0.000000  ...                  0.078000   21.000000
25%       1.000000   99.000000  ...                  0.243750   24.000000
50%       3.000000  117.000000  ...                  0.372500   29.000000
75%       6.000000  140.250000  ...                  0.626250   41.000000
max      17.000000  199.000000  ...                  2.420000   81.000000

[8 rows x 8 columns]
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 768 entries, 0 to 767
Data columns (total 9 columns):
Pregnancies                 768 non-null int64
Glucose                     763 non-null float64
BloodPressure               733 non-null float64
SkinThickness               541 non-null float64
Insulin                     394 non-null float64
BMI                         757 non-null float64
DiabetesPedigreeFunction    768 non-null float64
Age                         768 non-null int64
Outcome                     768 non-null object
dtypes: float64(6), int64(2), object(1)
memory usage: 54.1+ KB
None
     Pregnancies  Glucose  BloodPressure  ...  DiabetesPedigreeFunction  Age  Outcome
0              6    148.0           72.0  ...                     0.627   50        1
1              1     85.0           66.0  ...                     0.351   31        0
2              8    183.0           64.0  ...                     0.672   32        1
5              5    116.0           74.0  ...                     0.201   30        0
7             10    115.0            NaN  ...                     0.134   29        0
..           ...      ...            ...  ...                       ...  ...      ...
761            9    170.0           74.0  ...                     0.403   43        1
762            9     89.0           62.0  ...                     0.142   33        0
764            2    122.0           70.0  ...                     0.340   27        0
766            1    126.0           60.0  ...                     0.349   47        1
767            1     93.0           70.0  ...                     0.315   23        0

[376 rows x 9 columns]
['1' '0' 'O']
