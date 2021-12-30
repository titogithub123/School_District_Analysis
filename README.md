# School District Analysis
## This report will help evaluate the math and reading testing grade levels of a local school district.
### Overview of School District Analysis.
The Analysis includes small and large schools from both public and charter schools in the area. The main areas of concern for the focus of this study is to determine the passing percentage of the different schools in the math and reading, catagories. As such, we have taken a look at the different factors that go into making a particualr school more or less likely to pass standarized reading and math test at a proffecient level. Some of the factors we took into consideration for this study are...

- School Name
- School Size
- Grade Level
- Gender
- Type of school
- Budget 
- Math Scores
- Reading Scores
- Overall Passing **%**

The idea behind the analysis was to see if there exists a correlation between class size and passing percentage and also to investigate if the amount of money budgeted per student also helps to increase or decrease the likelyhood of a particualr student passing the tests with high averages. 

### Results
During our research for the analysis it came to our attention that some students at a particular high school of a particular grade level were accused of cheating and it was tasked upon us to remove the affected students records from the summary and analysis. As such, the follwing description of the results of our investigation will focus primarly on the integrated results of the affected students math and reading scores having been stricken from the offical analysis.

### District Summary
As we can see from the images below removing the ninth grade test scores from Thomas High school had little to no bearing on the overall math and reading scores from the district as a whole, due to the fact that the ninth grade students represent a small fraction of the total kids in the district. There are approxamitly 461 Thomas High school ninth graders which represent only 1.18% of the total students in the school district.

As such, we can only imagine that removing them from the school district total will have little affect. However, where we will see a larger percentage decrease in the amount of passing reading and math scores will be at Thomas High School, specfically. But, for now let's compare the district totals, pre and post Thomas High School ninth graders. 

***District Summary*** - (Prior to Dropping Thomas HS ninth graders.)

![image](https://user-images.githubusercontent.com/93171738/147616803-925e5209-9db5-4e0b-a610-425e624a48a6.png)

***District Summary*** - (Post Dropping Thomas HS ninth graders.)

![image](https://user-images.githubusercontent.com/93171738/147678365-81c3cc97-96fb-49e3-a692-26b662c3a275.png)
### School Summary
As we may have imagined, removing the math and reading scores for all ninth graders from Thomas High school had very little affect on the othe schools in the district as their test scores remained primarly intact from how they were prior to the removal of the ninth grade students. 

### Thomas High School
The real suriprise in this analysis was how much the ninth grade class of Thomas High School contributed to the passing math score of students who passed both their math and reading test. Prior to the removal of the ninth grade class, the Thomas High School students presented the following passing percentages. 

- **Passing Math Score % - 93.27%**
- **Passing Reading Score % - 97.34%**
- **Overall Passing Both % - 90.94%**

However, after the removal of the ninth grade students we can see a precipitous drop in the passing math score %. This is probably due to the supposed fact that some of the children of the ninth grade class at Thomas High were engaged in some dishonest behavior. We can see from the image below the updated lower passing math score percent. 

![image](https://user-images.githubusercontent.com/93171738/147712071-6b92c7f4-2b17-4026-a827-a508019d438d.png)

As we can see the passing math score took the biggest hit from losing the ninth grade class, falling from 93.27% to 66.91%. An ominious sign that something fradulant may have been going on.  The other scores, namely the passing reading and overall passing scores remained relativley unchanged. 

### Math and Reading Scores by Grade
![image](https://user-images.githubusercontent.com/93171738/147712418-0c03fbaf-33ed-4d5b-b2f1-ae55bfb596d5.png) 

The general pattern for most of the schools appears to be that the reading scores and passed percentages are almost uniformly higher than the math scores and passing percentages at almost all the schools. 

![image](https://user-images.githubusercontent.com/93171738/147712430-0cc32526-3fc6-4581-aca7-7de26942d28a.png)

### Scores by School Spending, School Size and School Type
For the remainder of the analysis we can use the following DataFrame's to put into perspective what I believe is at the heart of the issue for determining which schools will most likely have higher math and reading scores as well as higher passing percentages. 

***Top 5 Schools***
![image](https://user-images.githubusercontent.com/93171738/147712994-487e9458-0dc0-42eb-bc62-fe9b99fc502e.png)

***Bottom 5 Schools***
![image](https://user-images.githubusercontent.com/93171738/147713028-8ab6987a-2538-46e6-987f-7eca97dfbb09.png)
### Scores by School Spending
It's an interesting fact that the "Per Student Budget" average score for the top 5 schools comes in at $606.40 and the average "Per Student Budget" for the bottom 5 schools comes in at $646.60. What this tells us is that budgeting more money per student does not necesarilly translate to higher test scores. As a matter of fact, the average Overall Passing Percentage for the top 5 schools is 90.74% while the average Overall Pasing Percentage for the bottomw 5 schools is only, 80.87%. 

What this tells us is that throwing money alone at the problem is not the solution to higher test scores there must be other variables we have to take into consideration. 

### Scores by School Size







