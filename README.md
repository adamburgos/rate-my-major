# Rate My Major

Kaggle dataset used: College Majors and their Graduates

The objective is to rank every listed major based on multiple factors. Majors are usually ranked one dimensionally, like expected salary. The goal of this website is to add more variables into the equation in order to get a better and more comprehensive list of the best majors.

Explanation of each CSV 👇

⭐ AllAges.csv:
The all-ages.csv file contains data on the total number of students in a major, the number of employed graduates, the number of unemployed graduates, the unemployment rate of graduates, the median salary of graduates, and the 25th and 75th percentile salaries of graduates from the major

Major_code: The code associated with the major. (Integer)
Major_code: The code associated with the major. (Integer)
Major_category: The category of the major. (String)
Total: The total number of students in the major. (Integer)
Employed: The number of employed graduates from the major. (Integer)
Employed_full_time_year_round: The number of employed graduates from the major who are employed full-time year-round. (Integer)
Unemployed: The number of unemployed graduates from the major. (Integer)
Unemployment_rate: The unemployment rate of graduates from the major. (Float)
Median: The median salary of graduates from the major. (Integer)
P25th: The 25th percentile salary of graduates from the major. (Integer)
P75th: The 75th percentile salary of graduates from the major. (Integer)

⭐ GradStudents.csv:
This file contains data on the number of graduates and non-graduates from various majors, as well as their employment and salary statistics

Major_code: The code associated with the major. (Integer)
Major_code: The code associated with the major. (Integer)
Major_category: The category of the major. (String)
Grad_total: The total number of graduates from the major. (Integer)
Grad_sample_size: The sample size of graduates from the major. (Integer)
Grad_employed: The number of graduates employed. (Integer)
Grad_full_time_year_round: The number of graduates employed full-time year-round. (Integer)
Grad_unemployed: The number of graduates unemployed. (Integer)
Grad_unemployment_rate: The unemployment rate of graduates. (Float)
Grad_median: The median salary of graduates. (Integer)
Grad_P25: The 25th percentile salary of graduates. (Integer)
Grad_P75: The 75th percentile salary of graduates. (Integer)
NonGrad_total: The total number of non-graduates from the major. (Integer)
NonGrad_employed: The number of non-graduates employed. (Integer)
NonGrad_full_time_year_round: The number of non-graduates employed full-time year-round. (Integer)
NonGrad_unemployed: The number of non-graduates unemployed. (Integer)
NonGrad_unemployment_rate: The unemployment rate of non-graduates. (Float)
NonGrad_median: The median salary of non-graduates. (Integer)
NonGrad_P25: The 25th percentile salary of non-graduates. (Integer)
NonGrad_P75: The 75th percentile salary of non-graduates. (Integer)
Grad_share: The share of graduates in the major. (Float)
Grad_premium: The difference between the median salary of graduates and non-graduates. (Integer)

⭐ MajorsList.csv:

This file contains a list of majors and their associated categories

Major_code: The code associated with the major. (Integer)

⭐ RecentGrads.csv:

The file recent-grads.csv provides data on the employment and salary outcomes of recent college graduates

Major_code: The code associated with the major. (Integer)
Major_code: The code associated with the major. (Integer)
Major_category: The category of the major. (String)
Total: The total number of students in the major. (Integer)
Employed: The number of employed graduates from the major. (Integer)
Unemployed: The number of unemployed graduates from the major. (Integer)
Unemployment_rate: The unemployment rate of graduates from the major. (Float)
Median: The median salary of graduates from the major. (Integer)
P25th: The 25th percentile salary of graduates from the major. (Integer)
P75th: The 75th percentile salary of graduates from the major. (Integer)
Rank: The rank of the major in terms of popularity. (Integer)
Sample_size: The sample size of graduates from the major. (Integer)
Men: The number of male students in the major. (Integer)
Women: The number of female students in the major. (Integer)
ShareWomen: The percentage of female students in the major. (Float)
Full_time: The number of graduates employed full-time. (Integer)
Part_time: The number of graduates employed part-time. (Integer)
Full_time_year_round: The number of graduates employed full-time year-round. (Integer)
College_jobs: The number of college jobs held by graduates from the major. (Integer)
Non_college_jobs: The number of non-college jobs held by graduates from the major. (Integer)
Low_wage_jobs: The number of low-wage jobs held by graduates from the major. (Integer)

⭐ WomenSTEM.csv:

This file contains data on the popularity, gender breakdown, and median salary of STEM majors

Rank: The rank of the major in terms of popularity. (Integer)
Major_code: The code associated with the major. (Integer)
Major_code: The code associated with the major. (Integer)
Major_category: The category of the major. (String)
Total: The total number of students in the major. (Integer)
Men: The number of male students in the major. (Integer)
Women: The number of female students in the major. (Integer)
ShareWomen: The percentage of female students in the major. (Float)
Median: The median salary of graduates from the major. (Integer)

