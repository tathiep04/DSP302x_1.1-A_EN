# DSP302x_1.1-A_EN
Data Analysis with Python


Data Analysis with Python

1. SQL and Database

1.1. Overview

SQL: Structured English Query Language 
Database management system (DMS) – relational database management system (RDMS): my SQL, Oracle Databse,
Db2 on IBM Cloud Lite.
1.2. Basic SQL

Cú pháp cơ bản:

DDL.
DML.
CREATE TABLE
SELECT statement with conditions
COUNT, DISTINCT, LIMIT
INSERT statement
UPDATE, DELETE
GROUPBY, HAVING, BETWEEN, IN.
Định nghĩa về relationship: One-to-one, many-to-many relationship.

1.3. Relational database diagram.

Intermediate SQL
Built-in functions.
Aggregate functions: Sum, minimum, maximum, average.
Scalar functions.
String functions: Uppercase, lowercase.
“Date and time” function: day, month, day of month, day of week, day of year, week, hour, minute, and second.
Sub-queries(nested selects statements).
Join operators (Left/Right join, Inner join, Outer join, etc…)
Keys of Table: Primary keys, foreign keys
1.4. Acessing DB using Python

Một số API cơ bản:

MySQL C API: Low level access.
psycopg2 API: PostgreSQL databases.
IBM_DB API: IBM DB2 databases.
dblib API: SQL server databases.
ODBC: For Windows.
Các phép truy nhập DB cơ bản:

Tạo table.
Load data.
Query data. 
2. Data analysis and Visualization

2.1. Các thư viện cơ bản

Pandas
Numpy
SciPy
Matplotlib (plt)
Seaborn (sns)
2.2. Data Wrangling

Handle missing data: Drop/Replace.
Data formating: Dtypes.
One-hot enconding.
2.3. EDA(Exploratory Data Analysis) – Phân tích dữ liệu

Function in Pandas: describe(), value_counts, groupby().
Pivot methods in Pandas.
Correlation: Definition, usage and visualization on sns.
2.4. Data normalization – chuẩn hóa dữ liệu

Standard Scaler.
Min-Max.
Z-score.
Normalization.
2.5. Matplotlib

Matplotlib’s architecture: Back-end layer, artist layer and scripting layer.
Basic plot: Line plot, Area plot, Histogram plot, Bar plot, 3D plot.
Specialized plot: Pie plot, box plot, scatter plot.
2.6. Advanced Visualization Tools:

Waffle chart: Your own Python function.
Word cloud: Mueller's word cloud generator.
Plotly:
Scatter plot and pie chart.
3D plot.
Dealing with time-series data.
Seaborn:
Advantages/Disadvantages compared to matplotlib.
Basic syntax.
Seaborn regplot function.
Geospatial Visualization with Folium:
Cài đặt.
Các hàm cơ bản với long/lat value.
Choropleth map.
