<div align="center">
<h1>Data roles and skill set</h1>

<p>

With GPT, some data positions have become quite famous, especially data scientists, but there are others that deserve the same attention. In this repository I will show what they are, what are the main activities they develop and the set of skills they exercise.
It is open for discussion, I'll try to keep it updated as I change my opinions (which I certainly will).
</p>

<h2>
About the ""method"" I chose.
</h2>
<p>
I listed the most used abilities in the data area and compressed them until they were in common use between at least 2 positions. 
It is important to point out that I did not focus only on hard skills and that soft skills are just as important.
I gave grades from 1 to 10 (based on my experience) according to the use and the necessary level of knowledge for that skill.
</p>
</div>
<hr>

<h2 align='center'>Skill explanations</h2>


> <strong>Applied math.</strong>

<p>
Applied mathematics is the area of mathematics that looks for ways to solve problems in companies especially in areas of finance, expansion, logistics and marketing, it is widely used (mandatory skill for people who deal with data) in data-oriented companies.
The grades increase as the position needs to be closer to business-related indicators such as revenue, operating costs, CHURN, retention, etc.
</p>
<hr>

> <strong>Advanced math.</strong>
<p>
Firstly, with advanced mathematics focused on data I mean the use of some areas such as calculus, probability, advanced statistics, linear regression among many other areas, it is distinguished from applied mathematics because, unlike it, advanced mathematics does not pass by """lots of changes""" in functions due to business rules, as opposed to applied math which is basically modeled by business rules.
</p>
<hr>

> <strong>SQL</strong>
<p>
Although it is quite obvious that functions around data must have knowledge in SQL, this knowledge does not have the same levels in different positions. SQL subsets are responsible for this great differentiation of levels since many of the positions do not necessarily need to know DCL, DDL, DML commands.
The levels serve precisely to separate the subsets, following this line of reasoning I created a "straight line of wisdom".
</p>
<b>DQL > DTL > DQL ADVANCED > DML > DDL > DCL</b>
<hr>

> <strong>Programming</strong>
<p>
Programming is very present in the data areas, whether in languages such as python, scala, pl/sql for creating routines and pipelines or M, DAX for manipulating data in specific software.
The increase in grades in the various areas has to do with how much code the job requires you to write thoughtfully
along with the languages and the framework that you will use in your day to day.
</p>

<hr>

> <strong>Business</strong>
<p>
With business I took the liberty to add some soft skills like communication and general market knowledge in the (imaginary) equation.
Knowledge about the business in which the company you provide your services is basic for any position, be it development, commercial, marketing, etc., but how much business do you need to understand to be able to act minimally in the positions? I didn't use any mathematical formula or quantitative driver to define this, just my experience and knowledge in BI functions.
</p>

<hr>

> <strong>Infra</strong>
<p>
The infra skill refers to knowledge of deployment, monitoring pipe lines, identifying bottlenecks and needs, it is basically focused on software and frameworks such as docker, terraform, cloud architecture, metadata, among others, it is very similar to the set of devops practices.
Particularly it is a skill 8 or 80.
</p>

<hr>

> <strong>No/low code softwares</strong>
<p>
Some positions require you to use some no/low code software for developing dashboards, pipeline, documentation, deployment, etc. The different levels are related to how much knowledge you should have about these tools and how much you will use them in your day-to-day life.
</p>

<hr>

> <strong>Ponderation</strong>
<p>
<b>The weight of the skill is greater in relation to the difficulty in learning its basics.</b>

Weighting is an attempt to say how complex a position is in relation to the activities it performs and which are listed in the method. the account is

<i>((Applied math * 1) + (Advanced math * 4) + (SQL * 2) + (Programming * 3) + (Business * 1) + (Infra * 3) + (No/low code * 1) / 15)</i>

The weights of the weights were based on experience learning certain things related to skills and on informal surveys of some developers and data professionals.

The higher the grade, the greater the difficulty. <strong>DON'T</strong> take it as true.
</p>

<hr>

<div align="center">
<h2>Positions</h2>
_<h3>Data analytics.</h3>
<p>
The data analyst works in the opposite direction of the data scientist, focusing on talking about how and why things happened rather than making hypotheses about what might happen.
</p>
<p>
This position usually works by participating more actively in meetings and creating dashboards so that the company's activity points can consume or that it can help in decision making, either making the analyzes more accurate or delivering the data as chewed up as possible using a lot of visualization like tools.
It gives good points to no/low code software because knowledge of tools like power bi, tableau, excel, pentaho, etc.
they are in high demand for vacancies and are allocated good working hours. Applied mathematics and business follow the same path, generating insights with data and extracting information that generates value for the business requires knowledge about them.
</p>
<p>
For SQL and advanced math you don't need in-depth knowledge, you often won't need to elaborate complex queries or do a linear regression calculation.
</p>

- <h4 align='left'>Data analytics skills set points.</h4>

![data-analytics](https://user-images.githubusercontent.com/103412179/229837100-3c78d047-3679-4974-9d96-25261db28e30.png)
<div align="center">
_<h3>Data engineer.</h3>
<p>
Quoting the good article by Maxime Beauchemin, former data engineer at Facebook now Meta, data engineers are much closer to their older brother Software Engineer than to their younger brother Data Scientist that's why instead of creating machine learning models, deep learning, data visualization or anything related, first of all a data engineer he creates the necessary tooling to abstract as much as possible from technical activities related to modeling, mining and manipulation of data, creating pipelines, data lakes and data warehouses.
</p>
<p>
Data engineers are responsible for database modeling, mining and data manipulation, this explains why I gave SQL a 10 in the skill along with 10 in programming like routines in Python with Airflow or creating pipelines in Scala due to the large amount of data. 
In the day to day of a data engineer at IDEAL, reports or visualizations are not created for use on commercial fronts, nor machine learning or deep learning models, which is why the low grade in applied and advanced mathematics. The high score on infra is due to the fact that data engineers are very responsible for deployment environments, therefore knowledge in docker, terraform, cloud, etc.
they are in great demand in vacancies and occupy good hours of work.
</p>

- <h4 align='left'>Data engineers skills set points.</h4>


![data-eng](https://user-images.githubusercontent.com/103412179/229837083-f7e623e2-d8fe-489f-a5b4-1fcdd9327563.png)
</div>

<div align="center">
_<h3>Data ops.</h3>

<p>
Yes, I know that data ops is not a person occupying a vacancy, but a culture equal to devops, but there was a materialization of the culture in which a person was leading the fronts for data ops, as happened in devops, in fact, other positions were born derivatives of dataops like ml ops which is basically data ops focused only on machine learning, so I think it's fair to materialize the culture in this text.</p>
<p>
A dataops mainly takes care of monitoring pipelines, studying business needs, new possibilities and improvements. He ensures data security, reliability and quality, but he also participates in budget meetings and architecture definitions, abstracting that responsibility from data engineers, so obviously he gives full marks in infrastructure and also in business. The reason for the high score in programming is due to the configuration of environments and knowledge in the most diverse software aimed at deployment and the software life cycle. Even though it seems counterintuitive to ensure data quality and I didn't give high marks in SQL, I don't think advanced knowledge of SQL is needed to do this. The grade in Advanced Mathematics is explanatory and the reasonable grade in Applied Mathematics is due to the participation in financial issues that are related to the operational costs of keeping the applications available and with a satisfactory level of use.
</p>

- <h4 align='left'>Data ops skills set points.</h4>

![data-ops](https://user-images.githubusercontent.com/103412179/229837092-17042e40-3faf-466a-9e1f-437e92fac315.png)
</div>

<div align="center">
_<h3>Data scientist.</h3>

<p>
Data science is probably the most famous position on data in recent times. Her reputation is equally equivalent to the difficulty of becoming one, because the activities that a data scientist performs are extremely complex, even with the tools abstracting most of the things that are more complex, such as complex calculations, collecting and cleaning data.
</p>
<p>
The high marks in both math skills is self explanatory, you need to know both very well to develop artificial intelligence models that make sense for your business, this goes directly with business knowledge which is also needed but not at a very high level. In the ideal world, the data scientist is abstracted from functions that involve infra and even the collection and cleaning of data, a minimum knowledge is enough. With the popularization of AI, several no/low code software are emerging that abstract most of the complex tasks in the day-to-day of a data scientist, but knowledge in programming is still necessary, mainly in languages ​​such as R and Python and their frameworks which are references in the area and therefore the medium score in programming.
</p>

- <h4 align='left'>Data scientist skills set points.</h4>

![data-sci](https://user-images.githubusercontent.com/103412179/229837096-85c0224c-ea7b-475a-975a-d825af357693.png)
</div>
</div>
<hr>

<h3> Some considerations </h3>

<p>
Perhaps you have already heard of some other functions such as ML Engineer, BI Specialist or others, these functions exist but they are consistent with the business model in which it is mentioned, they are usually ramifications of the 4 mentioned above
</p>
