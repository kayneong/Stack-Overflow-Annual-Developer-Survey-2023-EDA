# Stack-Overflow-Annual-Developer-Survey-2023-EDA

## Project Title
Exploratory Data Analysis of the Stack Overflow Annual Developer Survey 2023

## Project Overview 
The survey was fielded from May 8 to May 19, 2023. The median time spent on the survey for qualified responses was 17 minutes.
Respondents were recruited primarily through channels owned by Stack Overflow. The top 5 sources of respondents were onsite messaging, blog posts, email lists, meta.stackoverflow posts, banner ads, and social media posts.
[Official Stack Overflow published report](https://survey.stackoverflow.co/2023/)

The goal of this project is to explore the dataset containing responses collected from the Stack Overflow Annual Developer Survey 2023 and create visualizations for insights that will answer the following guiding questions. 
- Are you more likely to get a job as a developer if you have a Master's degree?
- What are the job roles that pay the most for developers?
- How does coding experience affect the level of pay? 
- What's the most popular method of learning to code?

## Business Understanding
The survey was conducted to deliver industry-leading insights regarding the developer community. It was designed for various types of developers to stay up to date with the evolving developer experience, technologies that are rising or falling in favor, and to understand where tech might be going next.

## Data Understanding
The public survey dataset can be found here: [Stack Overflow Annual Developer Survey](https://insights.stackoverflow.com/survey). The dataset contains rows representing each respondent and each column representing their responses to each question in the survey. A copy of the survey can be found in this project's repository files for reference. There were many missing and ambiguous values in some of the columns and the rows containing these values were removed according to the analytical task requirements throughout the project. More details can be found in the Python notebook file of the project as well. 

## Evaluation of analysis
The following main visualizations below were generated to provide insight with regards to our guiding questions. 

![image](https://github.com/kayneong/Stack-Overflow-Annual-Developer-Survey-2023-EDA/assets/150570357/f6382342-7c37-4312-ab96-dd3f5c539777)
![image](https://github.com/kayneong/Stack-Overflow-Annual-Developer-Survey-2023-EDA/assets/150570357/a829cf27-e841-4b6c-bdc4-e3a9b09f30bf)
![image](https://github.com/kayneong/Stack-Overflow-Annual-Developer-Survey-2023-EDA/assets/150570357/7f42f93c-ffc7-4874-96f3-6b8d3ded7ad7)
![image](https://github.com/kayneong/Stack-Overflow-Annual-Developer-Survey-2023-EDA/assets/150570357/3b65cfb8-61a1-43b8-afd4-f56ed6d068ff)

## Conclusion 
A compilation of our responses to the guiding questions:

**1. Are you more likely to get a job as a developer if you have a master's degree?**

Yes, approximately 29.5% of professional developers that were surveyed do possess a Master's degree or higher (Professional degree). However, possessing just a Bachelor's degree may also be sufficient as most developers do (46.8%)

**2. What are the job roles that pay the most for developers?**

Senior roles such as Senior Executives and Engineering Managers earned the most for developers that responded. Apart from these senior roles, other high-paying job roles include Marketing/Sales Professionals, Site Reliability Engineers and Experience Developers. Prospective students or employees looking to attain a higher salary can work towards building their knowledge, skillsets and resumes to match the job description of these roles and increase chances of employment in these roles.

**3. How does coding experience affect the level of pay?**

The number of years of professional coding experience appears to be the the determining factor for higher compensation and salaries as three of the highest-paid roles ('Senior executive', 'Engineering manager' and 'Engineer,site reliability') have, on average, more than 10 years of professional coding experience. However, some roles such as 'System Administrator' and 'Academic researcher' do not pay as highly, highlighting the pay disparity between job roles despite given similar number of years of experience

**4. What's the most popular method of learning to code?**

Across all age groups, learning from online resources such as videos, blogs and forums seems to be the most popular method of learning to code especially for young developers under 18 years old. However, older developers (aged 55 and above) differ and seem to lean towards traditional educational material such as books or other forms of physical media. This could be due to generational differences in terms of educational upbringing as well as the availability of online resources during the earlier life stage of these older developers. Nevertheless, online resources such as videos, blogs and forums continue to be the second most popular method of learning for these older developers, showing the increasing significance of these less traditional learning resources. Out of the various online resources listed, technical documentation and Stack Overflow are the top online resources people use when learning to code, with blogs rounding out the top three.

**Next steps**

For a follow-up project, we can construct a logistic regression model to predict whether a responder is a professional developer based on their highest level of formal education. If the model is evaluated to be performing well enough, a close look at the model's coefficients can give us further insight as to how much each level of formal education affects the odds of being a professional developer.
