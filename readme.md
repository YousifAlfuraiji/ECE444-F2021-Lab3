# CARTE Education Pathways

## ECE444 Lab 3: Docker
Edited by: Yousif Al-Furaiji

This repo is a clone of https://github.com/nelaturuk/education_pathways

### Acitity 5: Feedback on Education Pathways application
#### Functional Requirement:
A function requirement of this system is the ability to do course code search. At the moment, the website does search using only course names. I would improve on this by making it able to search by course code which is something my peers and I find very helpful on other course planning websites.

#### Non-functional Requirement:
A non-functional requirement of this system is having a more convenient search. For example, when I search "software", ECE444 is on the top of the list but when I search "software engineering", the course is fourth on the list. I would improve on this by changing course listing order priority to show what a user more likely wants first. Currently, ECE444 seems to be fourth on the list due the top three courses having "software engineering" in the course description section, which is not what a student usually searches for.

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
