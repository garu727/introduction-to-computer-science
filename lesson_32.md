# Lesson 3.2: Combining loops and conditionals

## Learning objectives

Students will be able to...

* Combine loops with conditionals to create models with repeated but conditional behavior.

## Materials and preparation

* [Do now 3.2](do_now_32.md)
* [3.2 slide deck](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/slidedecks/TEALS%20SNAP%203.2.pptx)
* [Lab 3.2 - What goes up...](lab_32.md) ([docx](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/Unit%203%20Word/Lab%203.2%20What%20Goes%20Up.docx)) ([pdf](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/Unit%203%20PDF/Lab%203.2%20What%20Goes%20Up.pdf))
* [Unit 3 tips](unit_3_tips.md)

### Video resources

* [https://youtu.be/MegYWakO1yw](https://youtu.be/MegYWakO1yw)
* Video quiz: See additional curriculum materials accessed from the TEALS dashboard.

## Pacing Guide

| Duration   | Description                                   |
| ---------- | --------------------------------------------- |
| 5 minutes  | Welcome, attendance, bell work, announcements |
| 10 minutes | Review, lecture and introduce activity        |
| 30 minutes | Gravity activity                              |
| 10 minutes | Review and wrap-up                            |

## Instructor's notes

### Review and lecture

Review loops and conditionals

* Ask students what loops do, when they are useful, and what blocks exist.
  * Loops cause code to execute multiple times.
  * Loops can help reduce redundancy and increase readability.
  * Contains three loops: repeat, forever, and repeat until.
* Ask students what conditionals are for and when they are useful.
  * conditionals are used to execute a block of code only under certain circumstances.
  * Encourage discussion about previous activities.
  * Fill in understanding gaps when necessary.

Demonstrate combining loops and conditionals

* Present **repeat until** and **forever if** blocks.

  ![Repeat Until Block](images/repeat_until.png)
  
  ![Forever Block](images/forever_if.png)

* Ask students to suggest when these constructs might be useful.
  * **repeat until** is useful when a loop needs to run not for a set number of iterations, but until some situation occurs.
  * **forever if** is useful when a script should execute _any time_ a condition is true, for the duration of the program.
  * Point out that the condition in **repeat until** is a termination condition, while in **forever-if** it is a continuation condition.

Introduce the concept of modeling

* **Modeling:** building a system to simulate the behavior of a real-life phenomenon by simplifying or ignoring certain details.
* Ask students to suggest systems or concepts that might need to be modeled.
* Discuss important considerations when designing and implementing a model.
  * Lead students to realize that most sacrifice some amount of accuracy or realism for simplicity.

### Activity

Students should complete "What Goes Up..." lab individually.

Mention that the program written in this lab will be helpful for the end of unit project.

### Debrief

## Accommodations and differentiation

* Take care to ensure that all students have a functional program by the end of the lab to avoid putting some students at a disadvantage starting the project.
* If many students struggle, consider releasing your own solution after the lab has been completed in class.
* Ask the more advanced students to assist struggling students. It is vital that all students complete this lab in advance of starting the project.
* Advanced students can consider increasing the realism of their gravity model by adding acceleration and/or beginning to implement jumping.
