# Compathy
Web scrapes competency and empathy scores from professors on polyratings.com and converts it to a pandas dataframe

## Background
The implict and sometimes anecdotal perception that males tend to be more competent and females tend to be more empathetic is often reiterated in student perspectives. These implicit biases are highly associated with performance misconceptions and unfair hiring practices. This program scrapes data that can be further explored to determine if there is evidence of a difference, between genders, in the empathy and competency scores of Cal Poly professors.

On polyratings.com, students can post an evaluation of a professor and score the professor's ability to:
1. Present Material Clearly (synonymized as the Competency score for this dataset)
2. Recognize Student Difficulties (synonymized as the Empathy score for this dataset)

This program outputs a .csv with the following data variables:
* Name: Professor name
* Dept: Gender (determined by student usage of the professor's pronouns in the evaluations)
* Num_Evals: Number of total evaluations
* Emp: Empathy score (out of 4)
* Comp: Competency score (out of 4)

## Getting Started
Run `python3 compathy.py` 
