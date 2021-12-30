# School District Analysis
## This report will help evaluate the Math and Reading Testing Grade Levels of a Local High School District.
### Overview of School District Analysis.
The Analysis includes small and large schools from both public and charter schools in the the school district. The main areas of concern for the focus of this study is to determine the passing percentage of the different schools in the math and reading, categories. As such, we have taken a look at the different factors that go into making a particular school more or less likely to pass standardized reading and math test at a profecient level. Some of the factors we took into consideration for this study are...

- School Name
- School Size
- Grade Level
- Gender
- Type of school
- Budget 
- Math Scores
- Reading Scores
- Overall Passing **%**

The idea behind the analysis was to see if there exists a correlation between class size and passing percentage and also to investigate if the amount of money budgeted per student also helps to increase or decrease the likelihood of a particular student passing the tests with high averages. 

### Results
During our research for the analysis, it came to our attention that some students at a particular high school of a particular grade level were accused of cheating and it was tasked upon us to remove the affected students records from the summary and analysis. As such, the following  description of the results of our investigation will focus primarily on the integrated results of the affected students math and reading scores having been stricken from the official analysis.

### District Summary
As we can see from the images below removing the ninth-grade test scores from Thomas High school had little to no bearing on the overall math and reading scores from the district as a whole, due to the fact that the ninth grade students represent a small fraction of the total students in the district. There are approximately  461 Thomas High school ninth graders which represent only 1.18% of the total students in the school district.

As such, we can only imagine that removing them from the school district total will have little effect. However, where we will see a larger percentage decrease in the amount of passing reading and math scores will be at Thomas High School, specifically. But, for now let's compare the district totals, pre and post Thomas High School ninth graders. 

***District Summary*** - (Prior to Dropping Thomas HS ninth graders.)

![image](https://user-images.githubusercontent.com/93171738/147616803-925e5209-9db5-4e0b-a610-425e624a48a6.png)

***District Summary*** - (Post Dropping Thomas HS ninth graders.)

![image](https://user-images.githubusercontent.com/93171738/147678365-81c3cc97-96fb-49e3-a692-26b662c3a275.png)
### School Summary
As we may have imagined, removing the math and reading scores for all ninth graders from Thomas High school had very little effect on the other schools in the district as their test scores remained primarily  intact from where they were prior to the removal of the ninth grade students. 

### Thomas High School
The real surprise  in this analysis was how much the ninth-grade class of Thomas High School contributed to the passing math score of students who passed both their math and reading test. Prior to the removal of the ninth grade-class, the Thomas High School students presented the following passing percentages. 

- **Passing Math Score % - 93.27%**
- **Passing Reading Score % - 97.34%**
- **Overall Passing Both % - 90.94%**

However, after the removal of the ninth-grade class we can see a precipitous drop in the passing math score %. This is probably due to the supposed fact that some of the students in the ninth-grade class at Thomas High were engaged in some dishonest behavior. We can see from the image below the updated lower passing math score percent. 

![image](https://user-images.githubusercontent.com/93171738/147712071-6b92c7f4-2b17-4026-a827-a508019d438d.png)

As we can see the passing math score took the biggest hit from losing the ninth grade-class, falling from 93.27% to 66.91%. An ominous sign that something fraudulent may have been going on. The other scores, namely the passing reading and overall passing scores remained relatively unchanged. 

### Math and Reading Scores by Grade
![image](https://user-images.githubusercontent.com/93171738/147712418-0c03fbaf-33ed-4d5b-b2f1-ae55bfb596d5.png) 

The general pattern for most of the schools appears to be that the reading scores and passed percentages are almost uniformly higher than the math scores and passing percentages at almost all the schools. 

![image](https://user-images.githubusercontent.com/93171738/147712430-0cc32526-3fc6-4581-aca7-7de26942d28a.png)

### Scores by School Spending, School Size and School Type
For the remainder of the analysis, we can use the following DataFrame's to put into perspective what I believe is at the heart of the issue for determining which schools will most likely have higher math and reading scores as well as higher passing percentages. 

***Top 5 Schools***
![image](https://user-images.githubusercontent.com/93171738/147712994-487e9458-0dc0-42eb-bc62-fe9b99fc502e.png)

***Bottom 5 Schools***
![image](https://user-images.githubusercontent.com/93171738/147713028-8ab6987a-2538-46e6-987f-7eca97dfbb09.png)
### Scores by School Spending
It's an interesting fact that the "Per Student Budget" average score for the top 5 schools comes in at $606.40 and the average "Per Student Budget" for the bottom 5 schools comes in at $646.60. (A $40.20 per student, difference.) What this tells us is that budgeting more money per student does not necessarily translate to higher test scores. As a matter of fact, the average Overall Passing Percentage for the top 5 schools is 90.74% while the average Overall Passing Percentage for the bottom 5 schools is only, 80.87%. 

This fact goes a long way towards confirming that throwing money alone at the problem is not the solution to higher test scores; there must be other variables we have to take into consideration. 

### Scores by School Size
I believe we can also find a correlation between school size and how likely a student at that school is, to do well in their math and reading test scores. For example, the average school size for the top 5 schools is 1,641 students. On the flip side, we see that the average school size of the bottom 5 schools is 3,852 students. That's an average of approx. 42% more students per school. It's no wonder that lower school size can equate higher scores since the schools with lower total students can probably cater a little more to the personal need of their students to help them succeed. 

### Scores by School Type
The last factor we'll look at is scores by school type. It should come as no surprise  all the top 5 schools are charter schools and all the bottom 5 schools are district schools. The charter schools while not spending more money per student offer a smaller class size which in turn helps to better prepare students for standardized test by offering them more personal attention than you can hope to receive  at a public, district school. 

### Summary
In summation, we see that dropping the ninth-grade students from Thomas High School  had a negligible effect on the overall student performance and had a more significant effect on the final tally for Thomas High School. However, there are some conclusions we can draw from analyzing the pre- and post- dropping of the Thomas HS ninth graders. 

- Avg. Math Scores were slightly higher prior to dropping the ninth graders.
- Avg. Reading Scores seem to have stayed the same. 
- % Passing Math, decreased  when we took out the Thomas HS ninth graders.
- % Passing Reading, also went down after we took out the ninth graders. 

For your time and your attention, Thank You.

Your Local Data Specialist,

Humberto Sandez
