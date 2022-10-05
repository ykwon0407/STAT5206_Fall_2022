# Statistical Computing and Introduction to Data Science 

STAT5206 - Fall 2022

## Learning outcomes
- Understand basic programming
  - Manipulate data with different structures
  - Control flow
  - Functions
- Explore data via visualization
- Study statistical concepts via simulations
- Automate tasks with programming
- Understand basic optimization

### Prerequisites
- An introductory statistics class
  - Basic probability distributions (e.g. Gaussian, binomial distributions and their likelihoods)
  - Basic hypothesis testing (e.g. t-test)
  - Summary statistics
  - Histograms, boxplots, etc
- Multivariate calculus
  - Derivatives and functions
- Matrix operations and inverses of matrices
- You should be at least co-enrolled in a modeling class like regression

### Textbooks and references
- **Google!**
- Basics only - [Programming with Python by Software Carpentry (PPSC)](https://swcarpentry.github.io/python-novice-inflammation/)
- [Python concept notes (PCN)](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)
- [Python Data Science Handbook (PDSH)](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [LearningPython.org (LP)](https://www.learnpython.org/)

## (last update: Oct 4th) Timeline

|Date|Topic|Reference|Due|
|---|---|---|---|
|2022-09-09|- Introduction <br>- Python 101-1 (Variable 1, Function, Package) <br>- Numpy 1|- [PCN Chapter 1, 2, 3, 4, 6, 8, 11](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html) <br>- [PPSC Chapter 1, 2](https://swcarpentry.github.io/python-novice-inflammation/) <br>- [PDSH Chapter 2](https://jakevdp.github.io/PythonDataScienceHandbook/)||
|2022-09-16|- Python 101-2 (Variable 2, Loop) <br>- Numpy 2 <br>- OLS <br>- uni/bi-gram|- [PCN Chapter 5, 7, 11](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html) ||
|2022-09-23|- Python 101-3 (if/else, File I/O, Exception handling) <br>- AB testing|- [PCN Chapter 9, 10](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)|- HW0 (Sep 24th, 2:00 PM, NOT-GRADED) <br>- HW1 (Sep 25th, 11:59 PM)|
|2022-09-30|- Pandas 1 (DataFrame, Grouping) <br>- COVID-19|- [PCN Chapter 12, 14](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)||
|2022-10-07|- Pandas 2 (Merge, Timestamp) <br>- Visualization (matplotlib, seaborn) <br>- NYTimes|- [PCN Chapter 12, 15, 16](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html) <br>- [Set up your jupyter notebook environment with the command line](https://leewtai.github.io/setup/conda_and_navigator_setup.html)|- HW2 (Oct 9th, 11:59 PM)|
|2022-10-14|- Regular expression and interacting with APIs <br>- Data Wrangling Practice|- [PCN Chapter 13, 17](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)||
|2022-10-21|- Designing data pipelines|All previous PCN Chapter|- HW3 (TBA)|
|2022-10-28|**Midterm (in class)**|||
|2022-11-04|- Data use cases, relational data, and SQL <br>- Data quality concepts and data engineering|- [PCN Chapter 20](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)||
|2022-11-11|- Modeling data <br>- "Data science methods"|- [PCN Chapter 18](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)||
|2022-11-18|- Optimization <br>- Objective functions <br>- Bootstrap, permutation, and other simulations|- [PCN Chapter 19](https://leewtai.github.io/courses/stat_computing/lectures/learning_python_intro.html)||
|2022-11-25|**Thanksgiving NO CLASS**|||
|2022-12-02|**Amazing guest lecture**|||
|2022-12-09|- Validation <br>- Model evaluation|||
|TBD|Final|||


## Logistics
Class time: F 10:10am - 12:40pm, Location: 402 Chandler

### Teaching Team
Yongchan Kwon (yk3012)
  - Office Hours: Every Tuesday 2:30 PM - 4:00 PM and Every Wednesday: 7 PM - 8:30 PM at 901-C, School of Social Work.

Maria-Cristiana Girjau (mg4345)
  - Office hours: Every Thursday 9:00AM - 11:00 AM at the 10th floor lounge, School of Social Work.

### Grading
If your final grade is in [93-97), you will earn at least an A, [90-93) will earn at least an A-, [87-90) will earn at least a B+, etc. A grading curves may occur depending on the class performance but I will not curve downwards. I will not give out A+ for this class.

#### - Homeworks (25%)
- Late homeworks will receive 0 credit
- No make-up homeworks will be granted even if you registered late to the class
- If you want to learn how to set up Jupyter Notebooks with R, follow these [instructions](https://leewtai.github.io/setup/conda_and_navigator_setup.html)
- Please read these important things related to [submitting homeworks on Ed](https://leewtai.github.io/courses/stat_computing/ed_hw_faq.html)

#### - Exams (65%)
- Midterms (30%)
- Final (45%)

#### - Participation (10%)
- In class participation
- Online question posting (non-private) and answers are all ways to achieve this
- I will reach out after the midterm if you are at risk of missing some points here.

##### Exam accomodations
In order to receive disability-related academic accommodations for this course, students must first be registered with their school Disability Services (DS) office. Detailed information is available online for both the [Columbia](https://health.columbia.edu/content/disability-services) and Barnard registration processes.

Refer to the appropriate website for information regarding deadlines, disability documentation requirements, and [drop-in hours](https://health.columbia.edu/getting-care/drop-offices/disability-services-drop-hours)(Columbia)/intake session (Barnard).


For this course, students are not required to have testing forms or accommodation letters signed by faculty. However, students must do the following:

·         The Instructor section of the form has already been completed and does not need to be signed by the professor.

·         The student must complete the Student section of the form and submit the form to Disability Services.

·         Master forms are available in the Disability Services office or online: https://health.columbia.edu/services/testing-accommodations


## Expectations
- Take chances!
  - Break the code in lecture
- Give feedback in office hours or e-mail, don't waste your time if you think a topic is not helpful
- Participate and ask questions, this is not easy!
  - In class: forecast what should be done, compare with what is happening, then summarize the difference.
  - Online: describe what you observe, describe what you expect, communicate clearly.
  - To each other: summarize the conversation to ensure you're listening and think constructively before criticizing.
- **THE MOST IMPORTANT** Academic honesty: https://www.cs.columbia.edu/education/honesty/

### Acknowledgement
A lot of these materials are based off the materials from [Prof. Wayne Tai Lee](https://leewtai.github.io/)'s [STAT5206 homepage](https://leewtai.github.io/courses/stat_computing/syllabus_5206.html).


