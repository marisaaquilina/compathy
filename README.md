# Compathy
Web scrapes competency and empathy scores from professors on polyratings.com and converts it to a pandas dataframe

## Background
The expected and anecdotal perception that males tend to be more competent and females tend to be more empathetic is often reiterated in student perspectives. This can lend itself to biases in hiring practices or implicit perception biases among students. 

At Cal Poly, students can post an evaluation of their professor and score the professor's ability to 1) Present Material Clearly (synonymized as the Competency score for this dataset) and 2) Recognize Student Difficulties (synonymized as the Empathy score for this dataset).

This program outputs a .csv with the following data variables:
* Name: Professor name
* Dept: Gender (determined by student usage of the professor's pronouns in the evaluations)
* Num_Evals: Number of total evaluations
* Emp: Empathy score (out of 4)
* Comp: Competency score (out of 4)

## Getting Started
Run `python2 compathy.py` 
