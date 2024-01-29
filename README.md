# Introduction

This project looks at two sets of data. The first set gives us detailed information about how students perform in math and reading. The second set tells us about the basic features of schools, like their type, how many students they have, and their budget. Our main goal is to combine these datasets to see if there's a connection between how well students do in school and the type of school they go to. Essentially, we're trying to find out not just how students are performing, but also if the kind of school they attend has any effect on their performance.


<img src= "https://github.com/ElleNaazB/pandas_challange/blob/main/PyCitySchools/education.png">

## The Analysis  

The execuded code (<a href="https://github.com/ElleNaazB/pandas_challange/blob/main/PyCitySchools/PyCitySchoolsScript.ipynb">HERE</a>) provides a district-level summary of keymetrics from the combined <a href="https://github.com/ElleNaazB/pandas_challange/blob/main/PyCitySchools/Resources/schools_complete.csv"> school</a> and <a href="https://github.com/ElleNaazB/pandas_challange/blob/main/PyCitySchools/Resources/students_complete.csv"> students</a> data. 

Here are the key findings: 

- <strong>Total Schools:</strong> There are 15 schools in the district.
- <strong>Total Students:</strong> The district has a total of 39,170 students.
- <strong>Total Budget:</strong> The combined budget for all schools in the district is $24,649,428.00.
- <strong>Average Math Score:</strong> The average math score across the district is approximately 78.99.
- <strong>Average Reading Score: </strong>The average reading score is about 81.88.
- <strong>Percentage Passing Math:</strong> Around 74.98% of students passed math (scoring 70 or above).
- <strong>Percentage Passing Reading:</strong> Approximately 85.81% of students passed reading.
- <strong>Overall Passing Rate: </strong>The overall passing rate, considering students who passed both math and reading, is about 65.17%.

<strong> Understanding School Performance and Resources :</strong>
In different schools, students' performance in math and reading varies. On average, students score around 79% in math and do a bit better in reading, with an average score of about 82%. When it comes to passing these subjects, about 75% of the students pass math, and around 86% pass reading. However, looking at students who pass both subjects, the rate drops to about 65%.

The performance differs across various schools. For instance, schools like Cabrera and Griffin have higher math scores, above 83%, while schools like Bailey and Figueroa score lower, below 78%. This trend is similar in reading, where Cabrera and Griffin also perform well. The passing rates in math vary significantly among schools, but more students pass reading than math in most schools. Overall, charter schools like Cabrera and Griffin have a high success rate, with more than 90% of students passing both subjects.

Looking at how students perform across different grades, we see consistent math scores within the same schools, and charter schools generally have higher scores across all grades. The same stability is observed in reading scores, with charter schools again showing higher performance.

The financial aspect of the schools shows some interesting trends. There are 15 schools in total, catering to about 39,170 students, with a combined budget of $24.65 million. Interestingly, schools that spend less per student (less than $585) tend to have better scores and passing rates. On the other hand, schools that spend more, especially over $645 per student, see lower performance. In terms of school size, smaller (less than 1000 students) and medium-sized (1000-2000 students) schools perform better than larger ones (2000-5000 students), which face challenges in maintaining high passing rates.

In a comparison between charter schools and district schools, charter schools are noticeably outperforming district schools in both math and reading. The gap in overall passing rates is significant, with over 90% of students in charter schools passing both subjects, compared to about 54% in district schools.

This overview presents a clear picture of how different factors like school type, size, and resource allocation impact student performance in district schools.
