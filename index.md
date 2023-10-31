---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# For courses with a single offering in the _config.yml,
# uncomment the following line and comment out the course-multi line

layout: course-single
#layout: course-multi
---
<br/>

# <a name="description">Overview</a>

{{ site.description }}

## <a name="goals">Learning Goals</a>

By the end of this course, students will

* summarize data using exploratory data analysis techniques
* identify sampling methods used to produce data.
* determine how samples differ from populations using probability
* create and analyze distributions of variables.
* use a sample to infer (or draw conclusions) about the population from which it was drawn.
* gain an appreciation for the diverse applications of statistics and its relevance to their lives and fields of study 

## <a name="resources">Resources</a>

We will be using the *Statistical Reasoning* textbook from the Open Learning Initiative. You will need to purchase ($25) access to this text, using the "Course Key" **MATH215**. You will use this website to submit your Checkpoints and various exercises to help me track your progress and provide targeted feedback to improve your understanding.

You will also need to make a free account on the Kaggle website linked below. This is where you be working through examples and exercises, creating your Lab notebooks, and writing your final Project.

Each week there will be assigned readings from the textbook. It is expected that you will have **read through the material before our Tuesday class times** and worked through the in-text exercises to check your understanding along the way.

For our statistical software, we will be using R for this course, but we will not following the R instructions in the textbook. Instead we will use the `tidyverse` version of R, which is specifically designed for easy analysis and plotting.

{% include resources.html content=site.resources %}

## <a name="additional-resources">Optional Resources</a>

These are some other online resources for learning statistics. You are not required to read them, but can use them for additional and diverse perspectives on the course topics.

{% include resources.html content=site.extra-resources %}

## Laptop Policy

Since the majority of our class sessions will be spent “doing statistics,” you will need to **bring your laptop to every session**. We will be working with our online courseware and software all the time. If you do not have access to a laptop, let me know and we will facilitate one. If you lack proficiency with computers, please let me know and I will work with you.
<hr>

# <a name="inclasscode">Code</a>

When you encounter a section of the text that uses R, **follow the instructions on the Kaggle documents below**. These documents will be great resources for working through the labs. It is critical that you not just read the documents, but **run the code and modify it** to test your understanding.

| Date | Topic |
|:----:|-------|
| R 24 Aug | [Examining Distributions](https://www.kaggle.com/code/markgoadrich/math-215-examining-distributions) |
| T 29 Aug | [Examining Relationships](https://www.kaggle.com/code/markgoadrich/math-215-examining-relationships) |
| T 5 Sep | [Sampling and Designing Studies](https://www.kaggle.com/code/markgoadrich/math-215-sampling-designing-studies) |
| T 2 Oct | [Estimation](https://www.kaggle.com/markgoadrich/math-215-estimation) |
| R 19 Oct | [Hypothesis Testing for Proportions](https://www.kaggle.com/code/markgoadrich/math-215-hypothesis-testing-proportion) |
| T 24 Oct | [Hypothesis Testing for Means](https://www.kaggle.com/markgoadrich/math-215-hypothesis-testing-mean) |
| T 31 Oct | [Independent and Matched Pairs](https://www.kaggle.com/markgoadrich/math-215-inference-for-relationships) |

<hr>

# Coursework

[*Adapted from Spencer Bagley and David Clark, via [Robert
Talbert](https://rtalbert.org/a-real-world-approach-to-deadlines/)*]

MATH 215 uses a **real-world policy** on due dates---but this may not
mean what you think!  In the *real* real world, due dates exist but
they are often not ironclad.  Assignments have due dates to help you 
make progress in the course and solidify your knowledge before moving on 
to something new. Your life and schedule may not perfectly coincide 
with the due dates I have chosen. If you need more time to
get the job done well, you email whoever set the deadline to ask if
you can have more time.  Studies have shown that deadline extension
requests---in moderation and when truly needed---often lead to
*better* employee evaluations (not to mention better work). [*See [Go
Ahead and Ask for More Time on that
Deadline](https://hbr.org/2021/12/go-ahead-and-ask-for-more-time-on-that-deadline)
by Ashley Williams*.]

**If you need an extension on a due date, email me and explain what
you need**, and it will probably be fine.  It helps if you propose a
concrete new deadline (*e.g.* "I can get it done by 5pm on
Wednesday").  If you ask for lots of extensions, we'll work together
to find a way to help you keep up.  Note, however, that late
submissions may not receive feedback as quickly as on-time
submissions.

If you have significant extenuating circumstances that cause you to
miss multiple deadlines, please [come to office
hours](markgoadrich.youcanbook.me) to discuss broader accommodations.  I'm
happy to be flexible, but it helps to know what you need so I can
figure out the best way to help.

{% include important.html content="You must be in communication with me anytime an assignment is late." %}

If you would like to improve an assignment after it has been graded and improve your grade, you may revise and resubmit the assignment until you do. This must be **within two weeks of receiving feedback**. If you need more than two weeks, *you must schedule a meeting with me to discuss your reasons for the delay*.

However, the above only applies if you **made a reasonable attempt at the assignment the first time**. You cannot turn in a half-finished assignment before the deadline and then “revise” it by completing the rest. If your assignment is only half-finished, you must request use late days as described above.

{% include important.html content="All work and revisions must be completed the day of the final exam period for this course at 5pm." %}

## <a name="hwqz">Checkpoints</a>

In each section, there will be Checkpoint exercises that you need to complete. These will be due **on Wednesdays at 5pm**. You may repeat the checkpoints to improve your score, and the **best score** will be recorded. I will be able to see your progress on these checkpoints and other exercises in the text.

These quizzes are designed to encourage you to study the course material throughout the semester rather than waiting until the midterm exams.

A **partially complete** checkpoint will earn at least 60% of the points available.

A **complete** checkpoint will earn at least 80% of the points available.

## <a name="labs">Labs</a>

Much of your experience with statistics in this course will be through weekly labs. Each lab will be assigned with time allotted to work through the materials in class, and will be due **on Saturdays at 5pm**. 

As you work to answer the questions in the labs, you will need to be recording your answers in a Kaggle notebook. Use the Markdown sections to write up your thoughts and answers to the prompts, and use Code sections to write R code and generate your answers. To submit your labs, you will download your notebook (it will be a *.ipynb file) and hand it in through Teams. Here are the notebook templates to get started with your lab work.

| #  | Name | 
|:--:|------|
|1 | [Examining Distributions (pg. 38)](https://www.kaggle.com/code/markgoadrich/math-215-lab-1-examining-distributions) | 
|2 | [Examining Relationships (pg. 66)](https://www.kaggle.com/markgoadrich/math-215-lab-2-examining-relationships) |
|3 | [Sampling and Designing Studies (pg. 87)](https://www.kaggle.com/markgoadrich/math-215-lab-3-sampling-and-designing-studies) |
|4 | [Probability](https://www.kaggle.com/code/markgoadrich/math-215-lab-4-probability) |
|5 | [Sampling Distributions](https://www.kaggle.com/code/markgoadrich/math-215-lab-5-sampling-distributions) |
|6 | [Estimation and Confidence Intervals](https://www.kaggle.com/markgoadrich/math-215-lab-6-estimation) | 
|7 | [Hypothesis Testing for Proportions](https://www.kaggle.com/code/markgoadrich/math-215-lab-7-hypothesis-testing-proportions) |
|8 | [Hypothesis Testing (pg. 175)](https://www.kaggle.com/markgoadrich/math-215-lab-8-hypothesis-testing) |

On these labs, you may work with a partner on the lab assignments. **Their name must be listed on any code you hand in as joint work**. A partnership should only turn in a **single copy** of the assignment.

A **partially complete** lab will include 
* correct code to answer each question
* minimal written answers to the lab prompts
* minimal data visualizations

A **complete** lab will include
* a clear narrative constructed from your written answers to the lab prompts
* correct code to answer each question
* richly labeled and titled data visualizations for each question
* full explanations of each step of your code and reasoning
* a reflection on your experience working through the lab.

## <a name="projects">Project</a>

| #  | Name | 
|:--:|-----|
|1 | [Final Project]({{site.baseurl}}/projects/finalproject.html)  | 

You will have a final project in this course, where you analyze a dataset with statistics, write a paper summarizing your conclusions about the data, and give a short presentation during our finals period. This will be similar to the labs, but will be using a data set and research questions of your choice.

**You must work individually on this project.** You may discuss concepts and ideas with your classmates, but the work you turn in must be your own. More details on the final project will be provided in the middle of the semester. All deadlines are noted on the course calendar.

## <a name="exams">Exams</a>

There will be two in-class exams, on Thursdays. They will consist of short answer questions along with writing and debugging code. The checkpoints and labs are great practice for the exams. There will be a review day the Tuesday before.

**There is no final exam**; you will complete a final project instead, as described above.

## <a name="checkins">Checkins</a>

Three times throughout the semester, you are expected to
make an office hours appointment for conversation and feedback on your progress in the course. Ideally, these checkins should be scheduled during the weeks shown
on the [course calendar](https://app.teamgantt.com/public/projects/calendar/2023-08-13?ids=3632637&projectIds=3632637&publicKeys=xejRn6hKircu&prefs=P2lkcz0zNjMyNjM3JnB1YmxpY19rZXlzPXhlalJuNmhLaXJjdQ%3D%3D).

## <a name="participation">Stats In The World</a>

Each of you will choose one class throughout the term to find statistics used in a piece of popular press about a current event. You will prepare a brief **presentation** (5 minutes) of the current event you chose and describe the statistics used in it. 
You may work in pairs for this assignment (8 minutes total).

Use [this form](https://forms.gle/6DNvcSbCQYi8uk3G7) to submit your topic, I will then assign you a presentation date.

A **complete** presentation will address how an understanding of statistics 
* made the information more valuable
* allowed you to consider it critically.

## <a name="attendance">Attendance</a>

Attending class and being an active participant in the class community
is one of the [most important contributors to your learning at Hendrix](https://www.hendrix.edu/Catalog/2023-2024/Academic_Policies_and_Regulations/Policies_and_Appeals/D_6_e__Class_Attendance/).
Attendance is especially important in this class since you will often engage in group learning activities. Active participation is expected in order to achieve higher grade levels in the course. 

If you know that you will be absent, please email me so that we can find accomodations. If there is an emergency, please get in touch with me as soon as is possible once the emergency is resolved. I trust you to be honest with me about your reasons for the absence (I do not need details), and honest with yourself about if you truly need to be absent.

## <a name="scale">Specifications Grading</a>

### A Level Work

* Complete 9 Labs + 1 Partially Complete
* Complete 18 Checkpoints + 2 Partially Complete
* Complete 2 Exams
* Complete Final Project
* Complete 3 Checkins
* Complete 1 Stats In The World Talk
* Abundant Participation in Classroom Activities

### B Level Work

* Complete 8 Labs + 2 Partially Complete
* Complete 16 Checkpoints + 3 Partially Complete
* Complete 2 Exams
* Complete Final Project
* Complete 2 Checkins
* Complete 1 Stats In The World Talk
* Active Participation in Classroom Activities

### C Level Work

* Complete 7 Labs + 2 Partially Complete
* Complete 14 Checkpoints + 4 Partially Complete
* Complete 1 Exam + 1 Partially Complete
* Partially Complete Final Project
* Complete 1 Checkin
* Participation in Classroom Activities

### D Level Work

* Complete 6 Labs
* Complete 12 Checkpoints
* Partially Complete 2 Exams
* Partially Complete Final Project
* Complete 1 Checkin
