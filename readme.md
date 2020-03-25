<center><h2>Topics in Artificial Intelligence: Reinforcement Learning <br> University of San Francisco's MSDS 631-02 Summer 2020</h2></center>

<center><img src="https://imgs.xkcd.com/comics/progeny.png" style="width: 40%"/></center>

----
Course Description
----

This course will cover techniques in applied Reinforcement Learning (RL). Reinforcement Learning is one the most successful subdomains within Artificial Intelligence (AI). The fundamental idea in Reinforcement Learning studies is agents learn to take successful actions in an environment. Reinforcement Learning extends the usefulness of Machine Learning into new domains, such as video games, board games, and robotics. The course will focus on contemporary, practical applications of Reinforcement Learning. Topics will include fundamental Reinforcement Learning algorithms, such as multi-arm bandits and q-learning, and Deep Reinforcement Learning. 

This course is part of the [MS in Data Science program at the University of San Francisco](https://www.usfca.edu/arts-sciences/graduate-programs/data-science).

----
Logistics
----

__Instructor:__ Brian Spiering   
__Contact__: [Slack @BrianSpiering](https://msan-usf.slack.com/messages/DAMAXHTL5) (more preferred) | [bspiering@usfca.edu](mailto:bspiering@usfca.edu) (less preferred)  
__Office hours__: TBD | By Appointment   
__Grader__: Alice  
__Contact__: [Slack @alice](https://msan-usf.slack.com/messages/DJLJMRM5K) | [awang37@usfca.edu](awang37@usfca.edu) 

__Website__: [github.com/brianspiering/
rl-course](https://github.com/brianspiering/rl-course)    
__Communication__: Slack [`#reinforcement_learning_2020`](https://msan-usf.slack.com/archives/C010GN8CQ3W)  
__Location__: TBD   
__Section__: TBD

Prerequisite Knowledge
----

- Working knowledge of probability, statistics, machine learning, and deep learning.
- Intermediate level of Python (e.g., ability to create to classes).

Learning Outcomes
----

By the end of the course, you should be able to:  

1. Apply Reinforcement Learning techniques to solve complex, applied problems.
1. Define and identify examples of common Reinforcement Learning terms (e.g., agent, environment, state, and rewards).
1. Implement common Reinforcement Learning techniques (e.g., multi-arm bandits and q-learning) from scratch.
1. Create end-to-end Deep Reinforcement Learning applications.

----
Tentative Course Schedule
----

1.  (05/??) Welcome ∧ Intro to RL  
2.  (05/??) Multi-armed Bandits Redux
3.  (05/??) Contextual Bandits
4.  (05/??) Markov Decision Processes (MDP) 
5.  (06/??) Dynamic Programming
6.  (06/??) Q Learning
7.  (06/??) Value Function Approximation  
8.  (06/??) Deep Learning (DL) Refresher ∧ Deep Reinforcement Learning (DRL)
9.  (06/??) Deep Q-learning
10. (06/??) Proximal Policy Optimization (PPO)
11. (06/??) Deep Reinforcement Learning (DRL) Applications 
12. (06/??) Final Project Presentations

Topics Not Covered
-----

- “Good Old Fashioned AI”, aka expert / ruled-based systems
- Cutting-edge research 
- General discrete and continuous space search / optimization
- Game Theory, including minimax
- Psychology
- Neuroscience
- Genetic algorithms
- Simulated annealing
- Distributed computing
- Production applications
- Robotics
- Multiple agents
- This course is not a [complete survey of RL methods](http://louiskirsch.com/assets/posts/map-reinforcement-learning/methods.svg)
        
----
Textbooks
----

1. Reinforcement Learning: An Introduction by Richard S. Sutton and Andrew G. Barto. The standard textbook for RL [pdf](http://incompleteideas.net/book/bookdraft2017nov5.pdf)
1. Algorithms for Reinforcement Learning by Csaba Szepesvari A delightful walk-through of the most common RL algorithms [pdf](https://sites.ualberta.ca/~szepesva/papers/RLAlgsInMDPs.pdf)
1. [Artificial Intelligence: A Modern Approach](https://www.amazon.com/Artificial-Intelligence-Approach-Stuart-Russell/dp/9332543518). There should be edition coming out in April, 2020.
 
----
Grading
----

| Item           | Weight   |
|:---------------|:--------:|
| Participation  | 10%      |
| Exam           | 30%      |
| Labs           | 30%      |
| Final Project  | 30%      |
| __Total__      | __100%__ |

Each item's contribution is capped its respective percentage. The total course percentage is capped at 100%.

Currently, there is no extra credit. If there is any extra credit, it entirely at the discretion of the instructor.

We'll be using Canvas as the learning management system (LMS), aka gradebook. The instructional team will do their best to have Canvas accurately reflect your current scores in the course. However, Canvas may not 100% accurate all the time. In other words, your actual grade maybe significant different than it appears on Canvas. 

### Participation

I try to create an active learning environment in my classroom, which is incentivized with the _Participation_ grade. Attendance is mandatory, you can't participate if you don't attend. It is the responsibility of the student to attend all classes. If you have to miss class, due to sickness, job interviewing, or other circumstances, please notify your instructor by Slack in advance. Supporting documents (e.g., doctor’s notes) may be asked for to accompany absences.

Tardiness negatively impacts an active learning environment, thus will impact your participation grade.

You must show up to each session prepared. Each person is important to the dynamic of the class, and therefore students are required to participate in class activities. Expect to be "cold called". I call on students at random not to put you on the spot but to keep you engaged in the material at all times.

I expect you to be fully present and engaged in the classroom at all times.  

I except you follow the etiquette guidelines throughout the entire course. This is your warning etiquette. Every violation will negatively impact your total grade through the loss of participation points. The penalties scale exponentially:

|  | Participation points | Total points |
|:-------:|:------:| :------:|
| 1st | 10%  | .5%  |
| 2nd | 20%  | ??   |
| 3rd | 40%  | ??   |
| 4th | 75%  | ??  |
| 5th | 100% | 10% |

### Auditing Policy

If you are currently a MSDS student, you are welcome to audit any or all classes without my explicit permission. There are two criteria:

1. You must follow the etiquette policy. If you do not, you will be asked to leave.  
2. You must be in good standing with Career Services. During the summer session, students are required to take only one class so they have more time to focus on their job search. If you are on-track with your job search, you can use your extra time to audit my class. If you are not on-track with your job search, your time is better spent on getting back on track with your job search than auditing my class. 

### Exam

The single exam will be a combination of multiple choice, short answer, and programming questions. The tenative plan is to have a take-home exam. Date is TBD.

### Labs

The labs will be hands-on activities. The focus will be implementing algorithms from scratch or applying common libraries.

| Lab                      | Due Date & Time|
|:-------------------------|:--------------:|
| 1. Tower of Hanoi        | 05-??-20 9p|
| 2. Rock, Paper, Scissors | 05-??-20 9p|
| 3. Grid World            | 06-??-20 9p|
| 4. Tic, Tac, Toe         | 06-??-20 9p|
| 5. Basket Catch          | 06-??-20 9p|
| 6. Cart Pole             | 06-??-20 9p|

Late assignments will only be accepted for medical emergencies.

### Final Project 

In lieu of a Final Exam, there will be a Final Project due on 06-??-20. The Final Project will be the application of Reinforcement Learning techniques to model data or solve a __novel__ problem. 

More details are in Final Project Folder.

----
Grading
----

| Grade | Final Percentage |
|:-----:|:----------------:|
| A+    | = 100%           |
| A     | ≥ 93% and < 100% |
| A-    | ≥ 90% and < 93%  |
| B+    | ≥ 87% and < 90%  |
| B     | ≥ 83% and < 87%  |
| B-    | ≥ 80% and < 83%  |
| C+    | ≥ 77% and < 80%  |
| C     | ≥ 73% and < 77%  |
| C-    | ≥ 70% and < 73%  |
| F     | < 70%            |

Grading standards
----

The MSDS program considers a grade of "A" to represent exceptional work with respect to both the instructor's expectations and peer student achievements. I consider an "A" grade to be above and beyond what most students achieve. A grade of "B" represents the expected outcome, what is called "competence" in a business setting. A "C" grade represents achievements lower than the instructor's expectations for competence in the subject. A grade of "F" represents little or no work in the course.

Students with disabilities
-----

If you are a student with a disability or disabling condition, or if you think you may have a disability, please contact [USF Student Disability Services](https://myusf.usfca.edu/sds) (SDS) for information about accommodations.

Behavioral Expectations
----

All students are expected to behave in accordance with the [Student Conduct Code](https://myusf.usfca.edu/fogcutter) and other University policies.

Academic Integrity
-----

USF upholds the standards of honesty and integrity from all members of the academic community. All students are expected to know and adhere to the University's [Honor Code](https://myusf.usfca.edu/academic-integrity/).

You may not copy code from other current or previous students. All suspicious activity will be investigated and, if warranted, passed to the Dean of Sciences for action.  Copying answers or code from other students or sources during a quiz, exam, or for a project is a violation of the university’s honor code and will be treated as such. Plagiarism consists of copying material from any source and passing off that material as your own original work. Plagiarism is plagiarism: it does not matter if the source being copied is on the Internet, from a book or textbook, or from quizzes or problem sets written up by other students. Giving code or showing code to another student is also considered a violation. You must also abide by the copyright laws of the United States.

The golden rule: **You must never represent another person’s work as your own.** Credit to [Terence Parr](https://github.com/parrt/msds689).

I generously post all my materials to a public GitHub repo. However, you should not post any solutions to GitHub (or anywhere else on the Internet). __Publicly posting any solutions to any problems for this course will result in a failing grade for this course.__

If you ever have questions about what constitutes plagiarism, cheating, or academic dishonesty in my course, please feel free to ask me.

Counseling and Psychological Services (CAPS)
-----

CAPS provides confidential, free [counseling](https://myusf.usfca.edu/student-health-safety/caps) to student members of our community.

Confidentiality, Mandatory Reporting, and Sexual Assault
-------

For information and resources regarding sexual misconduct or assault visit the [Title IX](https://myusf.usfca.edu/TITLE-IX) coordinator or USF's [Callisto website](http://usfca.callistocampus.org/).
