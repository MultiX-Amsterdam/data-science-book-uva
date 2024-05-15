---
title: Syllabus
layout: default
nav_order: 1
---

# Course Syllabus
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

- TOC
{:toc}

(Last updated: Mar 19, 2024)

{: .highlight }
> Data science is about turning rich data into **actionable insight** and making data **impactful**!

This course aims to familiarize you with various data science pipelines using examples with different data types.
It is suitable for students who already have some experience in processing data and will work (or are currently working) with a large amount of data, especially focusing on obtaining insights from data through prediction or explanation techniques.
This course is not intended to cover all topics in data science exhaustively.
Instead, it introduces ways of working with structured (e.g., sensor measurements) and unstructured data (e.g., text and image).
Additionally, it also introduces topics on crowdsourcing and multi-modal learning.

It is important to keep in mind about the following of this course:
- We do not aim to teach you details in programming, machine learning, statistics, or visualization. Instead, we will teach you how to integrate various techniques (e.g., data wrangling, statistical analysis, data modeling, data visualization) together to perform a data science task.
- We assume someone already collected datasets for you, and we do not teach you how to collect data in the real world. Data collection is a topic that could take a very long time to explain and is mostly out of the scope of this course.
- We mainly discuss data science in the development environment. We do not cover techniques in the production environment, such as detecting concept drift, performing A/B testing, monitoring model performance continuously, retraining and finetuning models, versioning models and data, using parallel computing, getting user feedback with qualitative or quantitative studies, etc.

{: .note }
> Notice that the course instructor writes the syllabus from the first-person perspective. The target audience for this document is students, and thus, we use "you" to refer to the students who are reading this document.

## Learning Goals

By the end of the course, we expect you to be able to:
- Explain important components in the entire data science pipeline
- Explain common data science modeling techniques and evaluation metrics
- Use the Python Pandas and Numpy libraries to preprocess structured data
- Implement deep learning modeling techniques using the Python PyTorch library
- Perform given data science tasks and experiments with images, text, and structured data using Python
- Reflect critically on the model performance using experiments with different settings and metrics
- Obtain meaningful insights from data analysis for the given data science tasks

## Prerequisites

This course expects you to have the following prior knowledge:
- Intermediate level of Python programming (e.g., knowing different data types and data structures, knowing how to set up the Jupyter Notebook programming environment)
- Basic level of machine learning (e.g., knowing what supervised and unsupervised learning means, understanding the differences between classification and regression)
- Basic level of information visualization (e.g., knowing how to draw plots using Python packages, understanding the differences between a bar chart and histogram)

## Course Structure

This course has 8 weeks in total.
Weeks 4 and 8 will be used for mid-term and final exams.
Except for weeks 4 and 8, each week has two lectures (hoorcollege) and a seminar (werkcollege).
Week 4 has only one lecture for discussing the mid-term exam (no seminars).
Week 8 only has the final exam (no lectures and no seminars).
Refer to the [overview page](index#schedule) for the course schedule.

{: .important }
> Lectures (hoorcollege) will be given in English, as well as all the teaching materials (e.g., lecture slides, Jupyter notebooks) and assessment materials (e.g., exam questions, exam instructions, assignment content). Seminars (werkcollege) will be given in either Dutch or English, depending on the TA’s choice.

Course materials contain slide decks, Jupyter notebooks, and three modules (structured data processing, text data processing, and image data processing).
Each module contains three parts (preparation, tutorial, and assignment) for learning how to perform different data science tasks.
Modules are designed to have you work to have hands-on experiences.

## Virtual/Physical Settings

In principle, lectures are given in person in the physical classroom.
The teaching team will open a virtual classroom link to live stream the lectures (refer to Canvas for the link).
If we cannot give the physical lecture due to unexpected situations, we will make an announcement on Canvas to give the lecture only in the virtual classroom.

It is important to notice that when we give the lecture in the physical classroom, the virtual classroom will be muted and not be actively monitored.
It is very challenging for the course instructor to pay attention to both the physical and virtual audiences, and priority will be given to people who attend the physical classroom.

We will also do our best to record the lectures (with the camera pointing to the course instructor’s face only) and make the recordings available on Canvas.
However, there is no professional support for recording in the course, so there is no guarantee of the recording quality.
For example, you may experience poor sound quality or incomplete lectures in the recorded video.

In principle, seminars are in-person only.
If the TAs cannot attend the physical classroom due to unexpected situations, they may choose to give the seminars virtually.

## Grading

Your final grade is based on assignments and exams:
- 10% weight for reflective writing of the assignments from three modules; each counts as one-third of the total 10%
- 40% weight for the mid-term exam
- 50% weight for the final exam

There is one resit for the course, which counts as 90% weight.
There is no opportunity to do the resit for the reflective writing (10% weight).
According to the [UvA rule](https://www.uva.nl/en/about-the-uva/policy-and-regulations/rules-and-regulations/teaching/teaching.html#Model-regulations), the most recent grade will apply in the event of a resit regardless of the outcome.
This means that if you take the resit, your resit score will override the weighted sum of your mid-term and final exam grades.

{: .warning }
> The final exam and the resit will be more difficult than (or at least as difficult as) the mid-term exam since you have more time to study the materials. The resit will be at least as difficult as the final exam.

The base grade for each exam is 1, and there is no minimum grade requirement for each exam.
The base grade only applies when you attend the exam.
If you miss the exam, the grade will be 0 for that exam.
However, according to the [OER rule](https://student.uva.nl/onderwerpen/onderwijs-en-examenregelingen-oer), you need to get at least 5.5 in the final score (i.e., the weighted sum of the scores of all exams and assignments) to pass the course.
After each exam, the teaching team will grade the exam and release the grades as soon as possible.
After the grade is released, we will announce on Canvas how students can inspect their exam results.

## Reflective Writing of Assignments

{: .important }
> Assignment instructions and materials will all be in English.

After doing each assignment, you will need to complete and submit a reflective writing questionnaire on Canvas to explain what you learned from doing the assignment and how you learned the knowledge.
The reflective writing questionnaires will be graded, but the assignments themselves will not be graded.
This means that you only need to submit the reflective writing questionnaire using the template that we provide on Canvas (or [can be downloaded here](files/reflective-writing-template.docx)).
Deadlines for submitting the reflective writing questionnaires are on Canvas and also the [schedule outline](index#schedule-outline).
Grading rubic of reflective writing is on Canvas (or [can be downloaded here](files/reflective-writing-grading-rubric.docx)).

{: .note }
> The reflective writing questionnaire can be completed in either Dutch or English.

We expect you to do the assignments by yourself and discuss them with the TAs in the seminars.
You can work on the assignments with other students.
The questions in mid-term and final exams can be similar to those in the assignments.
Doing the assignments also helps you greatly in preparing for the exams.

Instead of checking assignments, we choose to provide assignment answers and use the [reflective writing technique](https://wac.umn.edu/tww-program/teaching-resources/using-reflective-writing) to encourage students to monitor their own learning progress.
We are now in the era of generative AI tools (e.g., ChatGPT), and we believe that, eventually, generative AI tools will be integrated into our workflow.
Due to this, we no longer feel the need to check your assignments, as the answers (specifically related to coding) can be obtained from generative AI tools.
Besides, your feedback and reflections can also greatly help us improve the teaching materials for future students.

## Submission and Late Policy

We are very strict on late submissions and how you submit your work.
This policy applies to all students in the course, including those who retake the course.
You must submit your work to Canvas.

{: .warning }
> We do not accept submissions via email.

Please carefully consider your submission time and do not wait until the last moment to do so.
Late submissions within 24 hours receive no penalty.

After 24 hours of the deadline, you can still submit the reflective writing assignments by the end of Friday of the course's final week (i.e., by the end of Friday of Week 8) in the Amsterdam time zone.
But you will receive only 50% of the points.
For example, if you should have 10 points for your submission, you will only get 5 points as a result (due to submitting the assignment more than 24 hours late).

For special requests (e.g., deadline extensions) due to personal circumstances that impact your learning, please check the [Support for Students Wellness](#support-for-students-wellness) section.

## Exams

{: .important }
> Exam instructions and materials will all be in English since the course materials are in English. In this way, we can match the exam questions clearly with course materials.

Exams are onsite and will be conducted using the [ANS system](https://ans.app/).
You will have access to the Jupyter Notebook software for computation during the exam.
You can use the question mark "?" syntax to [access the IPython help](https://ipython.readthedocs.io/en/stable/interactive/python-ipython-diff.html#accessing-help) to check the documentation of functions.

{: .warning }
> It is not allowed to do exams at home or remotely at other locations. You will have no internet access during the exams.

Exams contains only multiple-choice questions to test your general knowledge of data science and also coding knowledge.
We will provide mock exams for you to practice.

We will use guess correction for your score on the multiple-choice questions.
Details about how the ANS system uses guess correction is in [this online document](https://support.ans.app/hc/en-us/articles/360014340098-Guess-correction).

{: .warning }
> The University of Amsterdam owns the materials in this exam (e.g., the question sets), which means the materials are copyright-protected. You must keep the exam content confidential and are not allowed to copy or distribute the content in any form.

### Cheat Sheet

During the exam, you may bring an A4-size cheat sheet with you.
You can choose to handwrite or print the content on both sides of the cheat sheet.
After the exam, you can take the cheat sheet back with you.

The cheat sheet is designed to reduce your workload in memorizing details (e.g., math equations) and also help you prepare for exams.
For example, maybe there are parts that confuse you when you study course materials, and you may put them in the cheat sheet.
Another example is that you may put bullet points that can help you recall information (e.g., some important concepts).

### Exam Preparation

Please refer to the [schedule outline](index#schedule-outline) for the mid-term and final exams' coverage range.
To prepare for the exams, please make sure that you prepare the materials that are in the coverage range.
Below is a suggested plan:
- Redo assignments and practices, as well as check their answers
- Study lecture slides and all the provided Jupyter notebooks
- Rewatch lecture recordings
- Prepare your one A4-size page cheatsheet (double-sided) while studying

Regarding math, as a general rule of thumb, if a math equation is on the slide, and we explained it in the lecture, it means that the equation may appear in the exam (in different ways).
For example, the cosine similarity and softmax equations are in the slides (which we explained in the lecture), so they may appear in the exam (e.g., by asking you to compute them or why we need them).
Another example is that you need to understand how a decision tree works, including how to compute entropy and the misclassification error, as well as how they are used for splitting tree nodes.
However, the likelihood function appears in the slides, but it is not explained in detail, so this means the exam will not ask detailed math questions regarding the likelihood function (but may still ask high-level questions, such as why we need it).

Regarding math equations specifically, you need to know what they are doing at a high level.
For example, what is the purpose of having a loss function?
What do they measure?
What are the loss functions that can be used for regression?
We will provide equations for complicated functions (like entropy) in the question description or exam instruction.
But we will not provide equations for simpler things like accuracy, precision, recall, and f-score (or anything related to computing these metrics).

Regarding coding, multiple choice questions in the exam can contain coding-related questions.
For example, we may put some code in the question description and ask you to select the option that best explains what the code is doing (or the expected output of the code).
This means that you need to really do the assignments and practices to write the code, as they can appear in the exam as multiple-choice questions.
However, you do not need to worry about the code that is not in the tasks that we ask you to do in the assignments and practices, such as the code in the blocks other than the assignment parts in the structured processing tutorial notebook.
In other words, you only need to care about the code in the answers block and also the code mentioned in the course slides.

For the final exam specifically, we aim to focus more on the newly introduced materials that are not covered in the mid-term exam, but the distribution of exam questions may change.
This means that you still need to prepare and rehearse the materials that are covered in the mid-term exam.
There will be questions about PyTorch in the final exam.
But we will not test coding about PyTorch.
However, there may be high-level questions regarding PyTorch, such as the content of the notebook in the PyTorch Tutorial lecture and the practice of implementing a PyTorch pipeline.

### On the Exam Day

{: .important-title }
> Important Notice on the Exam Day
>
> - There are scrap papers at the exam location, and we will provide them to you if you need them.
> - Please make sure to bring your ID. We will check your ID at the exam location.
> - You are only allowed to enter the exam room up to 30 minutes past the exam starting time. You are not allowed to leave the exam room during the first 30 minutes and last 15 minutes of the normal exam schedule. The purpose of the rule is to prevent fraud (during the first 30 minutes) and disturbance (during the last 15 minutes). This is the university's rule and we need to follow it.
> - You can only bring pens, snacks, drinks, the A4-size cheat sheet, and your ID to the exam room. Other things are not allowed and must be stored in the lockers, such as books, mobile phones, smart watches, coats, bags, etc.
> - If you really need to go to the toilet, please raise your hand and notify the invigilators. An invigilator will need to accompany and wait for you outside the toilet.
> - When you finish the exam, you need to sign the attendance list before leaving the room.

{: .warning }
> Anyone who arrives more than 30 minutes late cannot participate in the exam. This is the university's rule.

## Policy for Retaking This Course

For students who followed the course last year, we add a reflective writing of assignments to grading (which counts as 10% of the final grade).
You can carry over the scores for mid-term or final exam to this year, but they will only add up to at most 90% of the grade.
For example, if you carry over the final exam score, it will only count as 50% of the total grade this year.
The mid-term exam will count as 40%. This means that you will need to do the reflective writing to be able to get the remaining 10%.

## Hygiene

Please follow [the advice from RIVM](https://www.rivm.nl/en/respiratory-infections) (National Institute for Public Health and the Environment) regarding coronavirus measures.
If you have symptoms associated with COVID-19 or any respiratory infections, please stay home.
You can use the online lecture live stream, the lecture recordings, and TicketVise on Canvas to participate in the course, as documented in the [virtual/physical settings](#virtual-physical-settings) and [communication principles](#communication-principles).

## Course Registration

For general course registration, please refer to the [UvA document](https://student.uva.nl/en/topics/course-registration).
The Faculty of Science handles registration procedures.
The teaching team does not handle course registration matters.
If you want to register for the course but you are late, or if you have problems signing up for the course, please get in touch with the following email: <vakaanmelding-fnwi@uva.nl>

## Change Groups

The course study groups (the ones with letters for your seminars, such as “Group A”) are automatically assigned.
Before the course starts, if you need to change the study groups (e.g., to move to a different seminar time), you need to follow the GLASS system's rules.
Please refer to the instruction in the [course registration document](https://student.uva.nl/en/topics/course-registration) to submit a request using the GLASS system.

After the course starts, you can still request group changes.
The general rule is that you need to find someone who is willing to switch groups with you.
Then, both of you need to send a message on Canvas or by email to the course coordinator to confirm your willingness to switch groups. People who follow this rule will receive higher priority in the group change.

You can also contact the course coordinator to change groups without finding a person who is willing to switch groups with you, and we will do our best to accommodate your needs.
People who go this route will receive lower priority.

{: .important }
> We cannot guarantee a successful group change in all the above cases (either following the general rule or just submitting preferences), as the teaching team needs to balance the workload among teaching assistants.

## Course Attendance

This course will not track attendance (e.g., lectures, seminars).
We expect students to follow their own learning progress.
You do not need to notify the teaching team and the TAs in case of absence.

## Fraud and Plagiarism

This course follows the [UvA Fraud and Plagiarism Regulations](https://student.uva.nl/en/topics/plagiarism-and-fraud).
When in doubt, please consult the “Regulations Governing Fraud and Plagiarism for UvA Students” document in [this UvA link](https://www.uva.nl/en/about-the-uva/policy-and-regulations/rules-and-regulations/teaching/teaching.html#Rules-and-regulations).

## Communication Principles

Class members are expected to treat others with mutual respect and appreciation regardless of any differences.
It is our intent that students from diverse backgrounds and perspectives be well served by the course.
In this way, we can create a safe environment for discussions.

The best ways to contact TAs and the teaching team outside the lectures and seminars are via TicketVise (similar to the discussion board) on Canvas, the Inbox message on Canvas, or email.
We prefer TicketVise as the questions can be allocated to the teaching team members based on their types.
Also, other students may have the same question and thus can check TicketVise to get answers.
Please keep in mind that responses from TAs and the teaching team could be delayed due to weekends or holidays.

All course announcements will be on Canvas.
We expect students to monitor Canvas periodically for any changes in deadlines, or any other announcements.

{: .important-title }
> Moving the Discussion at the Speed of Trust
>
> In group discussions, lectures, and seminars, please follow the principles below:
> - Practice mutual respect
> - Be an active listener
> - Do not make assumptions, ask questions
> - Suspend judgment
> - Invite and honor the diverse range of opinions and experiences

## Academic Code of Conduct

- OK to discuss assignments or projects with classmates
- OK to use existing solutions as part of your projects or assignments (but you need to clarify your contributions and cite the source properly)
- OK to publish your project portfolio (e.g., source code) after the course is over
- `NOT OK` to ask someone to do assignments or projects for you
- `NOT OK` to copy solutions or written content from classmates
- `NOT OK` to pretend that someone's solution or idea is yours
- `NOT OK` to post solutions for your assignment or course exams online
- ASK the teaching team if unsure

## Support for Students Wellness

If you experience mental health concerns or stressful events that can interfere with learning and daily activities (such as strained relationships, increased anxiety, substance use, feeling down, difficulty concentrating, and lack of motivation), UvA services are available.
You can learn more about (confidential) mental health services available on campus in [this UvA link](https://student.uva.nl/en/topics/mental-health).

As documented in the [OER rule](https://student.uva.nl/onderwerpen/onderwijs-en-examenregelingen-oer), for any personal circumstances that impact your studies (e.g., illness, disability, or family issues), contact your [study advisor](https://student.uva.nl/en/topics/study-adviser).
Exceptions can only be made if the study advisor contacts the teaching team for special arrangements, and these exceptions sometimes may require approval from the examination committee.

## Accommodations for Students with Disabilities

If you have a disability and require accommodations, please take a look at [this UvA link](https://student.uva.nl/en/topics/studying-with-a-disability-dyslexia-or-chronic-illness) to request special facilities or additional resources.

## Policy for Using Generative AI Tools

We allow students to use generative AI tools (such as ChatGPT) in assignments or projects (not exams) to boost their productivity, such as creating code, wrangling data, copy-editing text, checking grammar errors, etc.
However, it is important to know that generative AI tools come with risks that can also negatively impact your grade if you use them.
For example, large language models like ChatGPT tend to hallucinate arbitrary content, give misinformation, and provide fake sources/citations.
You should perform fact-checking and carefully verify the generated content.
If your work has misinformation or nonsense content, your grade for the work will likely be deducted.

If you are not familiar with generative AI tools, we recommend checking the follow e-learning module:
- [Responsible use of Generative Artificial Intelligence (GenAI) in education](https://rise.articulate.com/share/MyfLgG-cXE1a7XBuctQhndpJB-BgpYny#/)

You do not need to report the usage of generative AI, as we see it as a tool that people will integrate naturally into their workflow.
If you are interested in the motivation of allowing the use of generative AI in this course, please check the following paper:
- [Van Dis, E. A., Bollen, J., Zuidema, W., van Rooij, R., & Bockting, C. L. (2023). ChatGPT: five priorities for research. Nature, 614(7947), 224-226.](https://www.nature.com/articles/d41586-023-00288-7)

Our opinion is largely aligned with the views in this paper.
We prefer embracing its benefits so that we can jointly understand how people use it, and thus can provide us opportunities and reflections about how this kind of tool should be used or regulated in the future.

## Resources

We curated a [list of resources](resources) that inspired the development of this course. The course instructor greatly appreciates them.

## FAQ

Below is a list of commonly asked questions and their answers.

**Q1: Can I take exams remotely?**
- You have to do the exams on-site (in the physical exam room). It is not allowed to do exams remotely (e.g., at home).

**Q2: What should I do if I have missed (or need to miss) an exam, such as due to medical issues or personal reasons?**
- The best option is to take the resit, which is designed for these situations. The resit schedule is on [DataNose](https://datanose.nl).

**Q3: I want to change the seminar group. What should I do?**
- Read the [Change Group section](#change-groups) in this syllabus.

**Q4: I need help in course registration (e.g., I register the course late). What should I do?**
- Read the [Course Registration section](#course-registration) in this syllabus.

**Q5: What is the cheatsheet for the exam and how should I prepare for that?**
- Read the [Exams section](#exams) in this syllabus.

**Q6: What to do if I have conflicts with my exam schedule (e.g., two exams are at the same time)?**
- Contact the program coordinator or [study adviser](https://student.uva.nl/en/topics/study-adviser) for solutions.

**Q7: Can I reuse the partial grade from last year?**
- Read the [Policy for Retaking This Course section](#policy-for-retaking-this-course) in this syllabus.

## Acknowledgements

We greatly appreciate the help from the teaching administration and management team of the UvA Informatics Institute in supporting this course.
We also greatly thank the following open-sourced course for inspiring the set-up of this course:
- [IOB4-T3: Machine Learning for Design in TU Delft](https://ml4design.com/ml4design.2021-2022/)
