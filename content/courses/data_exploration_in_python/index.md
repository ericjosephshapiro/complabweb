---
title: "Data Exploration in Python"
date: 2024-12-26
lastmod: 2024-12-26
tags: ["Univariate statistics","Probability","Algorithms","Python"]
author: "tom mcandrew"
description: "This course provides an introduction to the fundamentals of programming in Python. Students will gain experience designing, implementing, and testing their Python code, as well as in using Jupyter Notebooks, and IPython for statistics and data analysis. Multiple programming paradigms will be explored. The course covers Python data types, input, and output, and control flow in the context of preparing, cleaning, transforming, and manipulating data. In addition, students will use Python to conduct exploratory data analyses, including computing descriptive statistics"
summary: "This course provides an introduction to the fundamentals of programming in Python. Students will gain experience designing, implementing, and testing their Python code, as well as in using Jupyter Notebooks, and IPython for statistics and data analysis. Multiple programming paradigms will be explored. The course covers Python data types, input, and output, and control flow in the context of preparing, cleaning, transforming, and manipulating data. In addition, students will use Python to conduct exploratory data analyses, including computing descriptive statistics"
cover:
    image: "dataexploration.png"
    alt: "dataexploration"
    relative: false
showToc: true
disableAnchoredHeadings: false
---

# Data Exploration in Python

## Abstract
This course provides an introduction to the fundamentals of programming in Python. Students will gain experience designing, implementing, and testing their Python code, as well as in using Jupyter Notebooks, and IPython for statistics and data analysis. Multiple programming paradigms will be explored. The course covers Python data types, input, and output, and control flow in the context of preparing, cleaning, transforming, and manipulating data. In addition, students will use Python to conduct exploratory data analyses, including computing descriptive statistics.

## Coordinates and Contact

- **Instructor:** Tom McAndrew  
- **Email:** [mcandrew@lehigh.edu](mailto:mcandrew@lehigh.edu)  
- **Office coordinates:** HST 175  
- **Office hours:** To be voted on by students | By appointment  
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3028.921968586107!2d-75.37903882408685!3d40.60954524388163!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c43fee03bfc589%3A0x98a474ea080cc523!2sHealth%2C%20Science%20%26%20Technology%20(HST)%20Building!5e0!3m2!1sen!2sus!4v1731542285433!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">width="700" height="500" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
---

## Class Logistics and Resources

### Class Time and Location  
- Tuesdays, Thursdays 3:00 PM - 4:15 PM in STEPS Room 121  

### Tentative Timeline  

| Topic                                                                                            | Timeline       | Materials                                  | Data Camp Lesson |
|--------------------------------------------------------------------------------------------------|----------------|--------------------------------------------|------------------|
| **Probability and Univariate Statistics**                                                                                                                                         | 
| Set Theory and properties of probability; Conditional Probability, and Discrete Random variables |  Week 1        | Hogg, McKean, Craig 1-1.3.2; 1.4, 1.5, 1.6 |
| Continuous random variables (including Uniform), Expectation                                     |  Week 2        | Hogg, McKean, Craig 1.7-1.10               | 
| Inequalities, Law of Large Numbers, and Bernoulli, Binomial, Poisson                             |  Week 3        | Hogg, McKean, Craig 3.1                    |
| Exponential, Gamma, Normal Densities                                                             |  Week 4        | Hogg, McKean, Craig 3.3.1, 3.4             |  
| Multivariate Normal Density                                                                      |  Week 5        | Hogg, McKean, Craig 2.1-2.3                |
| Simulation of Statistical Processes (Inverse CDF, Monte Carlo, and Accept/Reject)                |  Weeks 6 and 7 | Hogg, McKean, Craig 4.8                    | 
| Midterm                                                                                          |  Week 8        |  
| **Data, visualizations, application building**                                                   |
| Data Viz (Matplotlib, seaborn)                                                                   |  Week 9
| Data munging                                                                                     |  Week 10       | Chapter 2 in *Python Data Science Essentials by Alberto Boschetti, Luca Massaron* |
| Indexing, selection, merging, and joining                                                        |  Week 11       | Chapter 3 in *Python Data Science Handbook by Jake VanderPlas* |
| Split-Apply-Combine                                                                              |  Week 12       | Chapter 8, Groupby Operations: Split-Apply-Combine in *Pandas for Everyone: Python Data Analysis, 2nd Edition Daniel Y. Chen* |
| The Data Science LifeCycle                                                                       |  Week 13       | Chapter 1 in *Learning Data Science by Sam Lau, Joseph Gonzalez, Deborah Nolan* |
| Web-application and data viz                                                                     |  Week 14       | [Data: FluView For Subtypes](https://gis.cdc.gov/grasp/fluview/Novel_Influenza.html) |

---
## Textbook  
The course requires the textbook [Introduction to Mathematical Statistics](https://minerva.it.manchester.ac.uk/~saralees/statbook2.pdf) by Hogg, McKean, Craig, 8th Edition. 
The course will also follow several different books that are all available to Lehigh University students *free of charge*.
The materials can be accessed for free via Lehigh Unviersity Library.
The textbooks/materials are above in the Tentative timeline.

---

## Policies  

### Attendance  
Attendance is crucial. If sick, let the instructor know and stay home. An excused absence allows for makeup evaluations.

### Collaboration  
Work together, but submit your own answers. Collaboration on quizzes, midterms, and finals is not allowed.

### Frustration  
If frustrated, take a break, return later, and ask for help if needed.

---

## Technology  

### Computing  
We will use [Python 3](https://www.python.org/) for simulations and statistical training. 
There are several options for an integreated development environment to support Python programming.
Popular choices are:
1. VSCode [Link](https://code.visualstudio.com/)
2. sPYder [Link](https://www.spyder-ide.org/)
3. Jupyter Notebook [Link](https://jupyter.org/) <- Recommended for this course.

**Jupyter Cloud provided by Lehigh:**
Lehigh University provides a Jupyter Cloud, an easy to use platform for programmign in Python here ([Link](https://jupyter.cc.lehigh.edu/)
). **Note** to use Lehigh's Jupyter platform while not on campus Wi-Fi, you will need to logon to the University VPN.
Instructions for the VPN are here = [Link](https://lehigh.atlassian.net/wiki/spaces/LKB/pages/26677699/Windows+Mac+Linux+Download+and+Configure+the+VPN+client+Cisco+Secure+Client+prev.+AnyConnect)


**DataCamp:** Most, if not all, weeks of this course will ask students to use DataCamp for Python programming training.
DataCamp is provided by the University free of charge.

---

## Assignments  

### Grading Breakdown  

| Item         | Weight  |
|--------------|---------|
| Quizzes      | 25%     |
| Homework     | 50%     |
| Midterm      | 12.5%   |
| Final        | 12.5%   |

### Homework  
Homework is due in person, one week after assignment. Late homework grades are reduced as follows:
\begin{align*}
f(\text{grade}, \text{days late}) = \text{grade} \times e^{-0.35 \cdot \text{days late}}
\end{align*}
Late assignments beyond three days receive zero.  

### Exams
The Midterm is a take home project that blends: mathematical statistics, statistical programming, and simulaiton.
The Final is a take home project that asks students to build a fully functional web-application in python that will draw on all aspects of the course.
Quizzes are due by midnight on class days. Quizes are quick and meant to test class engagement.  

### Datacamp  
Datacamp assignments may accompany homeworks.  

### Extra Credit
Extra credit involves attending seminars and writing reflections, contributing as an additional quiz score.
These opportunities will be mentioned during the course.

---

## Accommodations for Students with Disabilities  
Lehigh University provides accommodations through Disability Support Services. More details are available [here](https://studentaffairs.lehigh.edu/disabilities).

---

## Principles of Our Equitable Community  
Lehigh University endorses [The Principles of Our Equitable Community](http://www.lehigh.edu/~inprv/initiatives/PrinciplesEquity_Sheet_v2_032212.pdf).  

---
