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

{% include resources.html content=site.resources %}

## <a name="additional-resources">Optional Resources</a>

{% include resources.html content=site.extra-resources %}

## Laptop Policy

Please **bring laptops to class**. Much of our in-class time will be spent working through exercises and labs to increase your understanding of statistics.
<hr>

# <a name="inclasscode">Code</a>

We will be using R for this course, but not following the R instructions in the textbook. Instead we will use the `tidyverse` version of R, which is specifically designed for easy analysis and plotting. When you encounter a section of the text that uses R, please refer to the documents below. These documents will be great resources for working through the labs. It is critical that you not just read the documents, but run the code and modify it to test your understanding.


| Date | Topic | Code |
|:----:|------||-----||
| T 22 Aug | Examining Distributions | [Exercises](https://www.kaggle.com/code/markgoadrich/math-215-examining-distributions) |
| R 24 Aug | Examining Relationships | [Exercises](https://www.kaggle.com/code/markgoadrich/math-215-examining-relationships) |
<!--
| W 4 Sep | More Math and Functions | [Box Math](https://boxmath-yorgey.notebooks.azure.com/j/notebooks/BoxMath.ipynb) |
| F 6 Sep | Strings and Booleans | [Booleans](https://booleans-yorgey.notebooks.azure.com/j/notebooks/Strings%20and%20Booleans.ipynb)

-->

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

## <a name="labs">Labs</a>


Much of your experience with statistics in this course will be through weekly labs. Each lab will be assigned with time allotted to work through the materials in class, and will be due **on Saturdays**. 

On these labs, you may work with a partner on the lab assignments. Their name must be listed on any code you hand in as joint work. A partnership should only turn in a **single copy** of the assignment.


## <a name="projects">Project</a>

| #  | Name | 
|:--:|-----|
|1 | Final Project | 

You will have a final project in this course, where you analyze a dataset with statistics, write a paper summarizing your conclusions about the data, and give a short presentation during our finals period.

**You must work individually on this project.** You may discuss concepts and ideas with your classmates, but the work you turn in must be your own. More details will be provided in the middle of the semester.

## <a name="exams">Exams</a>

There will be two in-class exams. They will consist of short answer questions along with writing and debugging code.


There is no final exam; you will complete a final project instead, as described above.

## <a name="checkins">Checkins</a>

Three times throughout the semester, you are expected to
make an office hours appointment and discuss your progress in the course. This will include conversation and feedback about your current progress and understanding.
Ideally, these checkins should be scheduled during the weeks shown
on the [course calendar](https://app.teamgantt.com/public/projects/calendar/2023-08-13?ids=3632637&projectIds=3632637&publicKeys=xejRn6hKircu&prefs=P2lkcz0zNjMyNjM3JnB1YmxpY19rZXlzPXhlalJuNmhLaXJjdQ%3D%3D).


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
* Abundant Participation in Classroom Activities

### B Level Work

* Complete 8 Labs + 2 Partially Complete
* Complete 16 Checkpoints + 3 Partially Complete
* Complete 2 Exams
* Complete Final Project
* Complete 2 Checkins
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

