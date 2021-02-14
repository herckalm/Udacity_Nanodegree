# Data Exploration of the performance of students in Mathematics and Science, based on the results of the PISA 2012 test

## by (Iraklis Kalamas)


## Dataset

> Quoting from the Organisation for Economic Co-operation and Development web site (http://www.oecd.org/pisa/):
> "The Programme for International Student Assessment (PISA) is the OECD's Programme for International Student Assessment. PISA measures 15-year-olds’ ability to use their reading, mathematics and science knowledge and skills to meet real-life challenges. More specifically PISA 2012 is the programme’s 5th survey. It assessed the competencies of 15-year-olds in reading, mathematics and science (with a focus on mathematics) in 65 countries and economies. In 44 of those countries and economies about 85 000 students also took part in an optional assessment of creative problem solving; and in 18 countries and economies, students were assessed in financial literacy."
> In my analysis I'll use a small part of the original dataset that is sufficient to answer my main question which is: to what extend the family structure (i.e. single - parent or not family, the parent's time spend with students, the presence or not siblings and the academic background of parent(s)) affect the performance of the students.
> In order to get the final dataset I did some preliminary wrangling in the original dataset. The full wrangling proccess is available in the Data_Cleaning_Proccess.ipynb ir Data_Cleaning_Proccess.html files.

## Summary of Findings

> From the gender distribution I saw that there is not any bias towards student's gender since female - male students are about 50% each.
> Students working more than 5 hours with their parent(s) is rare
> 53% of the students don't work with their parents
> 47% of the students work with their parents
> Most of the parents reach the upper secondary education level (82%)
> A very small percentage of parents doesn't have any education (1.7%)
> 34% of parents have a Bachelors degree
> None of the parents hold a Masters degree or higher
> One out of five families its a single parent family
> 70% of students has sibling(s)
> The scores are normally distributed
> Most of the students' scores are between 314 and 651 points
> The mean of the individual course distributions is very close to 480 points which is also the mean of Mean_Score
> The above facts shows that the evaluators of the tests did a balanced grading
> In math, male students have higher scores than female ones
> In science male students also have higher scores than female ones, but marginally
> The mean score favorites male studens
> It seems that the highest the parent education is the better the score is
> Students with parents who has at least the upper secondary (ISCED3) tend to perform above the scores mean
> When considering only number of hours between 0 and 5, there's a significant drop of about 70 points in the score, so studying with parents does not seems to be a factor of success
> As the hours studying with parent grows the performance is not clearly affected, meaning that sometimes the performance affected positively and sometimes negatively (maybe some students have problems with math and science that parents sometimes can solve and sometimes can't due to academic background)
> There is a weak negative correlation between scores and study time with parent
> I can see that when a student has one parent and siblings its performance affected negatively by 10 points in regard with the case that there is one parent with no siblings (nevertheless in both cases the performance is below the mean)
> In the other case students with two parents present tend to perform better with no siblings (the difference in this cas is about 50 points). Additionaly, here, students with no siblings are perform below mean than students with no siblings
> I can see that the presence of siblings is not a good factor for students performance even if parents spend significant time with students
> The greater the academic backround and the lack of siblings favors the students performance (by 40 points almost)
> The lack of education and the lack of siblings also favors the student's performance (but marginally)


## Key Insights for Presentation

> I spend time trying to polish my presentations in the maximum that I could and I'm satisfied with the results. I only did minor tweeks regarding figures and text sizes.