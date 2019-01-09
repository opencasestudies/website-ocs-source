+++
# About/Biography widget.
widget = "about"
active = true
date = 2016-04-20T00:00:00

# Order that this section will appear in.
weight = 5

# List your academic interests.
[interests]
  interests = [
    "Education",
    "Data Science"
  ]

+++

# The OCS project

## What problem are we addressing? 

An increase in demand for gateway training in statistics, biostatistics, and data science has led to changes in curriculum, specifically an increase in computing. While this has led to more applied courses, students still struggle with effectively deriving knowledge from data. This is primarily because (i) these courses frequently fail to frame the lectures around a real-world application; (ii) quantitative methods are typically illustrated _"with an unrealistically clean data set that fits the assumptions of the method in an equally unrealistic way. When students use this approach to solve problems in the real-world, they are unable to ... identify the most appropriate methodological approach when it is not spoon fed"_ (Hicks, 2018). 

## Problems with previously suggested solutions

In 1999, Nolan and Speed argued the solution was to teach courses through in-depth case studies derived from interesting problems, with nontrivial solutions that leave room for different analyses. This innovative framework teaches the student to make important connections between the scientific question, data and statistical concepts that only come from hands-on experience analyzing data. However, these case studies based on realistic challenges, not toy examples, are scarce. 

## What are we proposing as a solution?

We are now developing the `opencasestudies` educational resource of case studies, which demonstrate illustrative data analyses that can be used in the classroom to teach students how to effectively derive knowledge from data. The goal is for these case studies to be searchable, reproducible, and resusable. The long-term plan is for this repository to be scalable and sustainable with educational materials and case study templates that can be used to develop new case studies from outside contributors. 

## What do we mean by _case study_ ?

Here, we define the term _case study_ as an illustrative, complete data analysis in a real-world application, such as addressing obesity and risks to adolescent health:

1. Begins with an interesting scientific question or application for motivation: _Can we better identify patients in young, minority populations at risk for diabetes?_
2. Discusses how to access, gather, import, clean, and visualize data: _Data from electronic health records_
3. Exposes students to the thought process of combining computational and programming aspects with statistical concepts in a concrete example of data analysis. This is different from teaching either a programing language or a statistical methods class individually: 
_How can I use Monte Carlo simulations to simulate health outcomes? What does `relative risk` mean? Can I use machine learning to predict outcomes?_
4. Illustrates nontrivial solutions that leave room for different analyses of the data: _Are there possible biases to account for in the prediction model (e.g. selection bias, geographic information)?_
5. Teaches the student to effectively communicate results and to make connections between the scientific question, data and statistical concepts that only come from hands-on experience analyzing data.

