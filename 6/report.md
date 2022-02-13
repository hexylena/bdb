---
author: Helena Rasche
date: 2022-02-07
title: Assignment 6 Working Methods - Initial Reflection Report
titlepage: true
logo: ../avans.jpg
abstract: |
  Given the previously sub-optimal Python lesson which relied on students individually completing assignments, a task with which they struggled and felt quite isolated, here we discuss the replacement of individual exercises with pair programming. This improved the lesson significantly, with the additional improvement of teaching an industry-relevant skill; pair programming is often used in the industry to decrease defects and improve the onboarding process.
bibliography: report.bib
classoption:
- justified
- a4paper
include-after:
- \includepdf[pages=-]{Lesson preparation form v2.pdf}
- \section{Supplementary Data}
- \includepdf[pages=-]{Responses.pdf}
colorlinks: true
---

# Pair Programming

Pair programming is a software development methodology requiring two programmers to work together to solve problems and implement code.

> One, the driver, writes code while the other, the observer or navigator, reviews each line of code as it is typed in. The two programmers switch roles frequently [@Williams]

![Screenshot of a teams call in which two students sit, one actively working on writing code, the other leading the discussion. One student's screen is showing CoCalc, a notebook platform where students can type code and immediately evaluate it's correctness. This platform allows us to write rich documentation, provide links to external resources, and write exercise problems which students can then easily work on individually or together.](sharing.png)

Here we adapt this to the teaching environment via use of breakout rooms with two students, and screen sharing permitting the same situation of a "driver" and a "navigator". This should reduce cognitive load and frustration amongst students and allow them to rely on each other more for technical discussions, rather than seeing the teacher as the primary source of information [@Williams_2001].

## Positives

This methodology should hopefully bring significant improvements for students as it has been empirically shown to be an effective learning methodology for students [@mendes2005investigating;@mendes2006replicated]. Specifically this technique has also been shown to be extremely beneficial for women in computer science and gives them better chances for success in future programming endeavours [@werner2004pair], potentially by changing the concept of programming from a solo activity to a collaborative activity as it often exists in practice. Given that in business and academia, programming often involves peer code review to ensure high quality results, this makes it an ideal fit for our educational practices and a very positive experimental change to make to classes.

## Pitfalls

However there are some notable pair programming pitfalls in a teaching environment, such as the student with more coding experience doing all of the work by themselves [@cliburn2003experiences;@Williams_2002;@mcdowell2003experimenting], or students failing to swap roles leading to a similar result. These issues can be mitigated through a number of methods including student self-reporting their contributions or lecturers taking a supervisory role [@Williams_2002]. @Mentz_2008 additionally reports success with the integration of the concepts of "Cooperative Learning" and provides guidelines for mitigating potential failure modes. These can be addressed easily via teacher intervention and were done so during the course, limited only by the availability of teacher and/or TOAs moving between groups.

## Feedback

Student feedback was extremely positive, averaging 4.35 for all measures. The students overall liked the use of pair programming in their learning environment and found that it invited them to actively participate in the lesson.

Question                                                                    | Min | Max | Mean | Std.Dev. | Median | Mode
--------                                                                    | --- | --- | ---- | -------- | ------ | ----
\scriptsize The teaching method(s) used in the lesson fit the content of the lesson.    | 4   | 5   | 4.41 | 0.49     | 4      | 4
\scriptsize I liked the teaching method(s) used in the lesson.                          | 3   | 5   | 4.33 | 0.62     | 4      | 4
\scriptsize The teacher's instruction was clear to me.                                  | 4   | 5   | 4.33 | 0.47     | 4      | 4
\scriptsize The used teaching methods invited me to active participation.               | 4   | 5   | 4.41 | 0.49     | 4      | 4
\scriptsize The teaching methods used fit my way of learning.                           | 3   | 5   | 4.33 | 0.62     | 4      | 4
\scriptsize I liked the teacher's approach in this lesson better than in other lessons. | 3   | 5   | 3.91 | 0.49     | 4      | 4
\scriptsize I thought it was a nice lesson.                                             | 4   | 5   | 4.75 | 0.43     | 5      | 5

They additionally provided comments on the above, filtered for comments[^fulldata] specifically concerning the aspect of pair programming:

[^fulldata]: The full response set is attached at the end.

- \small "The breakout rooms are very nice. It is a nice way to work with the students and get some interaction and get to work with the theory. For me the theory stick better."
- \small "It was a lot of information for one day but working on the excercises together helped a lot"
- \small "I think working in pairs in breakoutrooms really helped in solving some of the questions and getting some insight"
- \small "I think it was nice to work on it together in breakout rooms, [...]"
- \small "The alternation between explanations and making assignments was good."
- \small "Good mix between excersises and theory"

Given the feedback it can be concluded that this was a successful intervention and practice that should be continued throughout the rest of the period. Additionally given that there are two sections of this course, one taught by a teacher not employing this method, it will provide an opportunity to further confirm or refute the success of the experiment.

# Reflection

In this lesson a significant overhaul was made to the material to function better as an online lesson. Further an intervention of pair programming was applied via breakout rooms and pairing students off in duos. I decided in the first breakout room to give students some privacy and let them discuss together, while in the second round of breakout rooms I "walked around" and visited the various breakout rooms to see how students were getting on[^observing]. The breakout rooms went successfully and students shared their results at the end. This is a process I wish to automate in the future, sharing results back, in order to give students some anonymity while I discuss common issues I saw during their exercise. Here I could only comment on mistakes based on their final result (if I did not observe) or the process if I was present in the breakout room to see the specific error occur.

[^observing]: This proved to be quite useful, I could see students making mistakes I would not have noticed otherwise, or if I'd only seen the final result.

## Looking Back

Overall this went quite well, I saw students interacting well and switching off between roles but could not confirm the uniformity of switching each time. I think this was a very successful intervention based on my observations as a teacher and the reporting of the students.

## Awareness

Based on the research included here, I think I need to further improve my observation of the students, either transparently via the programming environment we're using, or directly via my presence in the breakout rooms. One of these options scales better, but it might leave students without a good source of advice when they encounter difficulties in the exercises. Whether this builds skills to overcome small challenges, or leaves them struggling when they need assistance is yet to be seen.

## Alternatives

Instead of pairing them in duos, I could try pairing them in threes but this might lead to one person sitting back and not participating, whereas the pair situation forces them to participate but doesn't risk them feeling isolated. Next time I should continue my experiments of whether or not to visit them in their individual breakout rooms during the exercises to examine what effects that has on students, and additionally survey them on their preferences to find a common solution that achieves both my goals of a more supportive learning environment while avoiding disrupting them or having them feel a stressful scenario where they pressured to defend a topic they do not know well.

## Trials

Given the results of @werner2004pair I'll be carefully watching the outcomes of my course compared to my colleague's to see how the women in my class feel compared to theirs, and if the difference is significant to help them implement pair programming in their class. However I need to be careful that I'm not blinded by the success of this methodology on a global scale, and make sure I am adapting to students who struggle with this model and prefer working on their own, perhaps to be determined via further student surveying.


# References

