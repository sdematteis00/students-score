# Studying grades and what influences them
## Description
<img src="https://i.imgur.com/QyPECCx.png">
This report sets out to examine in detail the results of the analysis conducted on student grades. The primary objective is to identify the factors that influence students' grades and to examine the correlations between key variables in the context of education.

The analysis is based on a large sample of collected data, including detailed information on students' grades and socio-demographic variables. Advanced statistical techniques were employed to investigate the correlations between grades and potential influencing factors.

## Lenguage and Utilities Used
- [Kaggle](https://www.kaggle.com/datasets/desalegngeb/students-exam-scores)
- Python:
  - pandas,
  - numpy,
  - matplotlib,
  - seaborn

# Results
## Gender distribution of students
<img src="https://i.imgur.com/PRUQaMR.png">
The gender distribution within the student population surveyed is almost equal, with a slight majority of female students. This balance is crucial for grasping the nuances of gender dynamics and their potential impact on academic performance. It provides a preliminary insight into the relationship between students' gender and their academic achievements.

## The correlation between student grades and family situation.
<img src="https://i.imgur.com/KWCAAT1.png">
The initial graph, a heat map, demonstrates a positive correlation between parental education and student performance. This indicates that, on average, students with parents with higher levels of education tend to perform better on standardised tests than students with parents with lower levels of education. The heat map demonstrates the significance of this correlation, suggesting that parental education may influence students' educational opportunities and academic success.

<br><img src="https://i.imgur.com/6V3ZQ4p.png"></br>
The second graph, also a heat map, indicates a relatively weak positive correlation between parental marital status and student performance. This indicates that, on average, students from married families tend to achieve slightly higher scores on standardised tests than students from other types of families. However, the data demonstrate a notable degree of point dispersion, indicating that there is considerable variation in student performance within each parental marital status category.

## Distribution of grades in the various subjects
<img src="https://i.imgur.com/JfByr2W.png">

- <b>Writing:</b>
    The box plot illustrates that the majority of students achieved grades within the 60 to 90 range for the writing assessment, with a broader distribution around the median.
- <b>Reading:</b> Similarly, in reading, students' grades are concentrated between 60 and 90, with a significant concentration around the median range, indicating a similar distribution as in writing.
- <b>Mathematics:</b> The distribution of grades in mathematics is slightly different, with a higher concentration between 50 and 80. There are fewer extreme grades than in the other two subjects, indicating a more compact distribution around the median value.

<br><img src="https://i.imgur.com/CtXlUwe.png"></br>
The line graph illustrates a positive correlation between weekly study hours and students' grades. This indicates that, on average, students who invest more time in their studies tend to perform better on subject assessment tests than students who study less. However, the data indicate some degree of dispersion, suggesting that there is variability in students' grades within each category of study hours.

## Distribution of students by ethnicity
The graphs illustrate the distribution of students according to the ethnic groups identified in the database. It is important to note that ethnic groups are a very broad category, and unfortunately, the database does not provide more detailed information on the subdivisions. Nevertheless, five discrete groups can be discerned.
<img src="https://i.imgur.com/LWmnrX5.png">
The graphs demonstrate the proportion of students within each ethnic group. The data clearly indicates that Group C represents the majority of students. Groups B and D exhibit comparable values, with a notable number of students. Conversely, Groups E and A are represented as minorities, indicating a lower presence of students than the other groups.

## Grades by gender in each subject.
<img src="https://i.imgur.com/ZKatJZf.png">
The bar graph indicates a slight discrepancy in grades between male and female students. The data indicates that male students tend to achieve higher grades in mathematics, while female students typically perform better in reading and writing. Although the differences are not significant, these trends are consistent and warrant further investigation to gain a deeper understanding of gender dynamics in academic performance.

<b>The subsequent violin graphs serve to reinforce the findings presented in the bar graph.</b>
<img src="https://i.imgur.com/Ead2lzI.png">
<img src="https://i.imgur.com/taYp0KI.png">

## Considerations
The analysis presented in this report offers valuable insights into the factors that affect students' academic performance. It is evident that factors such as gender, family situation, ethnicity and study habits have a significant impact on academic performance. However, it is vital to consider some key considerations to better contextualise and utilise these data in improving educational strategies.<br>
### 1. Gender balance:
The near gender parity in the student population is a positive finding, as it allows performance to be analysed without significant bias due to the dominance of one gender over the other. However, the slight differences observed in results in mathematics, reading and writing indicate the possibility of underlying factors influencing the performance of males and females in different ways. Further investigation of these differences is essential to develop educational interventions that can close any gaps and support all students equally.

### 2. Influence of family situation:
The significant relationship between parental education level and student achievement highlights the pivotal role of the family context in determining academic success. This indicates that schools should consider implementing family involvement strategies and support programmes for parents with lower education levels. Furthermore, the weak correlation between parents' marital status and educational achievement indicates that other factors, such as the quality of family support and home environment, may be more relevant than simple family configurations.

### 3. Differences in subjects:
The disparity in grades across subjects underscores the necessity for tailored teaching methodologies. It is evident that students encounter greater challenges in mathematics than in other subjects. This necessitates the implementation of targeted strategies by educators to enhance the effectiveness of teaching methodologies and the provision of tailored support resources for this discipline.

### 4. Ethnic diversity:
The representation of different ethnicities among students highlights the necessity for inclusive education policies that address specific cultural and linguistic needs. While the database does not provide details on ethnic divisions, it is vital that schools adopt a sensitive and inclusive approach to guarantee that all students, regardless of their background, have an equal opportunity to succeed.

### 5. Study hours:
The positive correlation between weekly study hours and academic achievement serves to confirm the importance of commitment and consistency in study. However, the inconsistency of outcomes within each category of study hours indicates that the quality of study may be a key differentiating factor. It is therefore recommended that schools adopt a dual approach, encouraging greater commitment to study and providing tools and techniques for more effective study.


