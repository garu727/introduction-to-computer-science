# Lesson 2.1: Loops

## Learning objectives

Students will be able to...

* Define **loop** in a programming context.
* Explain why loops are useful.
* Implement simple repeat and forever loops.
* Apply loops to reduce redundancy in scripts.

## Material and Preparation

* [Do now 2.1](do_now_21.md)
* [2.1 slide Deck](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/slidedecks/TEALS%20SNAP%202.1.pptx)
* [Exterior angles review](Geometry_Exterior_Angles.pdf)
* [Lab 2.1 - Squares and triangles Redux](lab_21.md) ([docx](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/Unit%202%20Word/Lab%202.1%20Triangles%20and%20Squares%20Redux.docx)) ([pdf](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/Unit%202%20PDF/Lab%202.1%20Triangles%20and%20Squares%20Redux.pdf)).
* Looping real world examples
  * [Water cycle](https://pmm.nasa.gov/education/water-cycle)
  * [Still I Ris"](https://m.poets.org/poetsorg/poem/still-i-rise)
  * [Happy](https://genius.com/Pharrell-williams-happy-lyrics)
* [Example](http://snap.berkeley.edu/snapsource/snap.html#present:Username=brettwo&ProjectName=Lesson%202.1%20Example)
* [Unit 2 Tips](unit_2_tips.md)
* Video Resource: [https://youtu.be/XbZqfRGPom0](https://youtu.be/XbZqfRGPom0)
  * Video Quiz: See Additional Curriculum Materials accessed from the TEALS Dashboard.

## Pacing guide

| Duration   | Description                                   |
| :---------- | :--------------------------------------------- |
| 5 minutes  | Welcome, attendance, bell work, announcements |
| 15 minutes | Lecture and examples                          |
| 25 minutes | Squares and Triangles Activity             |
| 10 minutes | Debrief and wrap-up                           |

## Instructor's notes

### Lecture

Introduce and discuss concepts of code redundancy and readability. Remind students that a program can be written in many different ways that are functionally equivalent.

* Ask students to speculate as to why one version of a program might be better or worse.
  * Possible answers: more efficient (in time or space), shorter code, more elegant/readable code.

Show [this example](https://snap.berkeley.edu/snap/snap.html#present:Username=andrewspiece&ProjectName=Lesson%202.1%20Example) to demonstrate unreadable program and give examples on how the **repeat** blocks (loops) can help make more concise scripting.

* Show students the script, ask what it does, then ask if they can think of ways to improve it.
* Attempt to get students to realize that the script is _redundant_ and could be simplified if there were a way to execute a block of script more than once.

#### Introduce loops

Begin with general definition: _A type of block that causes other code to run multiple times in succession_.

Use real world loops to introduce the concept:

* [Water cycle](https://pmm.nasa.gov/education/water-cycle)
* [Still I Rise](https://m.poets.org/poetsorg/poem/still-i-rise) by Maya Angelou
* [Happy](https://genius.com/Pharrell-williams-happy-lyrics) by Pharrell Williams

#### Introduce specific loops

The **repeat** block runs the body of the loop the specified number of times.

  ![Repeat block](images/repeat.png)

* Number of iterations can be a value, variable, or reporter.

The **forever** block runs the body of the loop nonstop until the script is ended.

  ![Forever block](images/forever.png)

It can be stopped either by clicking the stop sign or by any version of **Stop** Block.

  ![Stop block](images/stop.png)

The **repeat until** runs the body of the loop until the specified condition becomes true.

  ![Repeat until block](images/repeat_until.png)

Save detailed discussion of this loop until conditionals are introduced.

Walk through [examples](http://snap.berkeley.edu/snapsource/snap.html#present:Username=brettwo&ProjectName=Lesson%202.1%20Example) of **repeat** Block and **forever** Block

* Emphasize usefulness in reducing redundancy and complexity, especially for repetitive tasks.

### Activity

Direct students to complete ["squares and triangles redux"](lab_21.md) individually.  

* If available, students should use their solutions to Lab 1.3 as a starting point.  Ensure students "Save as..." before starting on the new lab to not overwrite their original project (part 1.1).
* If student solutions for Lab 1.3 are not available, or are not correct, provide a correct implementation (the solution to Lab 1.3 can be found on the TEALS Dashboard under Additional Curriculum Materials).

Encourage students to try to use as few blocks and have as little script duplication as possible to draw each shape while still creating understandable scripts.
  
* Once students complete part 2.1, the remaining parts should go much more quickly as they all follow the same basic pattern.

### Debrief

Discuss one or two student solutions to part 2.2. Ask students to think about what the script would look like without loops.

Discuss one or two students solutions to part 3.1. Point out how unwieldy the script for these two shapes would be without loops.

## Accommodation and differentiation

* More advanced students can add additional shapes, including a five-pointed star without interior lines.  
* Particularly advanced students can be encouraged to build pictures by combining multiple shapes (e.g. a house built of squares of various sizes).
* For students struggling with the mathematics, make the [exterior angles review](Geometry_Exterior_Angles.pdf) available showing various shapes and their respective angles as a reference for students through unit 2.
