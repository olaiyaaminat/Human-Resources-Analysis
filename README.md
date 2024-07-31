# Preamble

This project utilises the Gender pay gap dataset which contains 9 attributes which are Job title, gender, Age, Performance Evaluation, Education, Department, Seniority, 
Base pay, and Bonus. The attributes provided in this dataset can be tailored to an employee’s socio demographic data collected by an organisation for a workforce analysis. 


# Description of Dataset

As a workforce analyst I would explore the employee demographics characteristics, performance and compensation to improve strategy plan and development in the organisation.
This dataset contains both qualitative and quantitative attributes.
The qualitative attributes are Job title, gender, education, and department while the quantitative attributes are Age, performance evaluation, seniority, base pay, and bonus.
I selected Job title, gender, education, and department as qualitative attributes because of the descriptive but nonnumeric form of the attributes and age, performance 
evaluation, seniority, base pay, and bonus because of the numeric nature of the data.

As stated above the dataset contains 9 attributes. Below is the description of each attribute:

• 	Job title: Describes various positions within the organisation.

•	 Gender: Represents the gender of employee.

•	 Age: Represents the age of each employee.

•	 Performance Evaluation: Indicates the performance evaluation scores of each employee.

•	 Education: Describes the educational qualification of employees.

•	Departments: Represents the department employee works.

•	Seniority: Indicates the years of services of each employee.

•	Base pay: Describes the base salary of each employee.

•	Bonus:  Denotes the bonus amount received by employees.


# Data Preprocessing

For the suitability of analysis, I make use of python prompt to clean, transform the dataset. Firstly, I load my dataset and had a view of the rows and columns. 
I furthered by checking for null values in my dataset and renamed the column. I also checked for duplicated values and my data types. All this was done to ensure 
accuracy in my analysis.

# TASK 1
## Measure of Central Tendency 

To analyse the measure of central tendency (mean, median and mode) I have selected 9 attributes which are Age, Performance Evaluation, Base Pay, Seniority, Bonus, Department,
Gender, Job titles and Education. For finding the mean value(average) I have selected 7 attributes which are Age, Performance Evaluation, Base Pay, Bonus, Department, 
Gender, and Education. I choose the attributes to find the mean because of the quantitative nature that is they are numeric values however I considered Department,
Gender, and Education which are qualitative data but grouped by the quantitative attributes to gain more insight about the employee by summarising the mean of the data 
distribution.
For the median class, 4 attributes were selected (Age, Base Pay, Seniority and Bonus). This attribute contains numeric data that enables identifying the middle
value when the data is arranged in either ascending or descending order, as well as the central value that splits the data set in half equally. I furthered by exploring the 
data by finding the mode, I used 5 attributes which were Department, Gender, Job titles, Performance Evaluation and Education all categorical or qualitative dataset in nature. 
Selecting the attributes helps to highlight the most frequent occurrences in qualitative data, recognise patterns, and identify predominant categories.
As a workforce analyst, I investigated our employee’s salary structure, performance evaluation, reward and incentive programs, professional development, and compensation 
with the aim of exploring and gaining more insight through the workforce socio demographic dataset which will make an impact and inform decision for the organisation



### Mean Output

I started by finding the average age of employees using the “age” attribute which was 41.393 that is 41 years old. As such I understand the employee age distribution which 
can help the workforce design training programs for a specific age group and develop human resources strategy.The Mean Performance Evaluation 3.037 will help in identifying 
employees with consistency, high performance and trend across the organisation. Mean Base Pay 94472.653 will guide me as a workforce analyst,in ensuring that satisfactory wages are offered to keep top talent.

Mean bonus of employees 6467.161, these values will help in establishing incentive compensation systems that are reasonable and in line with employee contributions.
I proceeded in finding the mean base pay of employers by departments. This reveals average pays across departments and as an analyst I can make sure that compensation
is equitable and handle any possible problems with equitable pay across several departments.

The mean age of employee by their gender shows average of 41-year male and 42-year female respectively. This informed me on practicing equal support opportunity and
professional advancement through mentorship programs for employee. The Mean bonus of employee by education will provide the relationship between education and rewards.
This will help in providing professional development linked to bonuses. The average bonus received by employee vary by their levels of education. This analysis give insight 
on employees' average bonuses according to their educational level and give room for comparison as such organise career growth programs that are linked to bonuses. 

Analysing the mean age of employees by department gives an insight of the average employee age in each department. Knowing this will assist in modifying workforce plans 
for knowledge transfer, diverse hiring, succession planning,and focused training to match the unique requirements of every department's age groups.


### Median Output

Firstly, I used the age attribute to calculate the median age of employee which was 41 years old. This outcome will help me as a workforce analyst to develop age-inclusive
policies that will be more appealing to a wider spectrum of workers. The Median Base pay of Employees revealed 93327.5 this gives an insight into the employees’ salary distribution.
The median seniority of employees was 3, this shows the experience level of employees. This decision can be used to design a training and development program. The median bonus level 6507 will
be a useful tool for developing equitable and uniform bonus structures across various staff levels.

### Mode Output

I find the mode of job titles and the outcome revealed marketing associates was the most frequently occurred job titles. This informed me as a workforce analyst to coordinate 
succession planning and recruitment tactics to concentrate on these in-demand roles. Moreover, I explore the mode of departments where I discovered Operation department as the most occurrence this 
reveals the areas where most of the labour is based. Therefore, I can effectively distribute resources, optimise workflows,and handle possible problems in department.
The mode of education revealed high school as the frequent education level and the mode of Gender identified male as the common gender this can aid the design of a more 
balanced, equitable and diverse work environment.

The performance evaluation mode shows a rating of 5. This would aid in standardising evaluation criteria and identifying areas where performance assessment techniques need to
be improved.

# TASK 2

###  MEASURE OF SPREAD OR DISPERSION (RANGE, VARIANCE & STANDARD DEVIATION)

By analysing the measure of dispersion (range, variance &standard deviation) I selected 6 attributes which are age, bonus, base pay, seniority, department, performance evaluation. Firstly, I evaluated the range using 4 attributes which are age, bonus, base pay, and seniority because they are numeric or quantitative data which make it suitable for finding the range of value however, I also used a qualitative data (department) grouped by age to find the age range in each department. Using quantitative attributes enhances comprehension of how data points are distributed within these variables and the extent of variation.

Going forward, I analysed the variance and standard deviation of the employee with 4 attributes (age, bonus, base pay, seniority, performance evaluation) which are all quantitative. I used the groupby function in python with qualitative data (department) to find variability of age across the department. The degree of variability within each dataset can be determined by analysing the attributes which aid with consistency by providing a numerical value that indicates how far each data point is from the mean. 

As a workforce analyst I calculated the range to determine the spread between the minimum and maximum value within each attribute which provides an easy way to assess the degree of variation among attributes. The standard deviation and variance quantify the extent or degree or dispersion of the attributes. By investigating the dataset, I can make decision that will guide and develop initiatives that support and equitable and performance-based workplace.


### Range Output

The range of age among employees is 47 years, it reflects the age difference between the youngest and oldest workers. These aids my knowledge as a workforce analyst comprehension on the age diversity in the organisation and helps develop age-inclusive policies. Also, the range of employee’s bonus, 9590 which signifies the difference between the highest and lowest bonus by employee. This will assist in creating bonus structures that are just and inspiring as well as helping workforce to comprehend how additional money is distributed.The range of employee base pay was 145,518. This may help ensure equitable compensation systems at all organisational levels by evaluating income distribution and spotting possible discrepancies. I proceeded to find the range of employee seniority which helps workforce to comprehend the range of experience and term of service within the firm.
Furthermore, I find the range of age of employee by department, I used pandas group by function to group the department and then apply the min and max function to subtract. This gives the age range of each department which appears to be 47 for all department that is it is uniform. This can assist in creating bonus structures that are just and inspiring as well as helping workforce comprehend how additional money is distributed among age group across the department.


### Variance

The spread between numbers in a data set is measured as variance. I also find the variance of seniority employee which was 1.94 this will aid my knowledge as a workforce analyst in creating career development initiatives and mentoring programs that are appropriate for a range of experience levels. Moreover, the variance of employee performance evaluated will help in assessment procedures and introduction of focused training initiatives.The variance of employee age was explored which indicates that a greater age variability among employees is indicated by a higher variance in age. This variability will make it easier for me to create age-specific benefits that effectively serve a range of age groups.
Furthermore, the variance of base pay shows 641988565.314 this will aid fair compensation policies are followed and pinpoint areas where salary structures need to be adjusted. The variance of employee bonus will aid bonus distribution to make sure it is equitable and in line with performance.
I proceeded by finding the age of employees grouped by department. I then used the pandas function groupby to group the department and var() to find the variance, this gives the age of each employees by department in the dataset. This report shows me the distribution of ages in each department, which varied across departments. To facilitate a seamless transition when employees retire or take on new responsibilities, departments with a more diverse workforce may need to implement more complex succession planning techniques.


### Standard Deviation

I proceeded by finding the standard deviation of age, as a workforce analyst this output can be used to develop flexible policies that consider changing needs based on age differences. The standard deviation of base pay will aid distribution to assess how well salary policies are working and make necessary changes to stay competitive. The standard deviation of bonus would aid in reviewing bonus structure to reward employee’s performance effectively.
In performance evaluations, a higher standard deviation indicates a more widely distributed range of scores from the mean. Seniority standard deviation estimation can help in the development of comprehensive career advancement plans that consider the different experience levels of its workforce.The standard deviation of employee performance will help me to identify outliers or regions that need more uniform evaluation procedures to conduct fair assessments.
The standard deviation of age by department was achieved by grouping employees by department and using pandas function groupby and std() to find the standard deviation the output shows a fairly distributed age across the department this will help to make decisions based on employee age inclusion policies and ensuring strategy in each department.

# TASK 3

### PROBABILITY MASS FUNCTION

I used performance evaluation attributes from the dataset because of the discrete nature of the data which suit probability mass function analysis. Performance evaluation attributes contains limited set of distinct score between 1-5 which makes it more suitable for probability mass function analysis. To confirm the entire probability are discrete I calculated the probabilities of each unique value in the performance evaluation column which summed up to 1.
Computing the probability associated with each performance rating is made easier by computing the Probability mass function. It facilitates decision-making by providing a concise numerical representation of the probability that ratings will occur. The performance rating distribution would aid in identifying areas that may require improvement initiatives. Also, based on the probability distribution of performance evaluations, professionals can make well-informed decisions, carry out focused interventions, and develop strategies for improving overall organizational performance.
The performance evaluation analysis can give insight on the likelihood that an employee will receive a particular performance evaluation score, which helps to understand how employees' performance levels are distributed throughout the workforce. 

### PMF OUTPUT

I proceeded by visualising my performance evaluation for Probability Mass Function using bar chart, which quantify the likelihood of the outcome. I set the x axis as performance evaluation and y axis as probability and give it a tittle “Probability Mass Function for Performance Evaluation”. From the chart the rating is fairly distributed between employer with (4,5) and (2,3) rating. This will help in the assessment and planning of performance improvement areas by pointing out the organisation's strengths and shortcomings in employee assessments.

# TASK 4

### PROBABILITY DENSITY FUNCTION

I considered the base pay attribute because of the continuous nature of the dataset. A continuous variable is represented by the term base pay. Base pay offered details on how salaries are distributed among the various organisational levels understating it distribution better can be achieve by probability density function. Budget planning for salary increases, bonuses, or reorganizing compensation plans is made easier with the help of insights from the base pay PDF. 
Evaluating the equity and fairness of pay structures is made easier by looking at how "Base Pay" is distributed. It will assist workforce professionals in locating compensation disparities that may need to be addressed. This ensures that competitive salary structures are in place to draw and keep talent while adhering to financial constraints.

I generated the probability density function for the base pay attribute by calculating the relative frequencies of different base pay values showing the likelihood of occurrence of each base pay value in the dataset. The base pay PDF's insights aided budget preparation for pay increases, bonuses, or reorganising compensation schemes as well as effective resource allocation. The probability density function (PDF) analysis can be used to find anomalies in base pay distribution, such as differences between departments or genders. This will facilitate the resolution of possible pay equity and fairness concerns.

By visualising the probability density of base pay I used histogram and KDE plot (Kernel density estimation). I set the x axis as base pay and y axis as probability density from the chart I can conclude the base pay is a bit symmetric to the right. This insight can help to make well-informed decisions about budget allocations for compensation-related issues, performance-based incentives, and salary adjustments.


