# Lesson 4.1: Introduction to lists

## Learning objectives

Students will be able to...

* Explain the concept of a `list` in a programming context.
* Identify scenarios in which lists are useful.

## Materials and preparation

* [4.1 slide deck](https://github.com/TEALSK12/introduction-to-computer-science/raw/master/slidedecks/TEALS%20SNAP%204.1.pptx)
* [Unit 4 tips](unit_4_tips.md).
* Paper/writing implements for each group of students.
* Large poster paper and markers will allow for display of the algorithms, but standard paper will work fine.

## Pacing guide

| Duration   | Description                                   |
| :---------- | :--------------------------------------------- |
| 5 minutes  | Welcome, attendance, bell work, announcements |
| 10 minutes | Introductory discussion                       |
| 10 minutes | Students write Solar System algorithm         |
| 10 minutes | Debrief                                       |
| 10 minutes | Translate algorithms into pseudocode     |
| 10 minutes | Debrief and wrap-up                           |

## Instructor's notes

### Introductory discussion

Describe the solar system and hook your students in with a way to collect and store new information and discoveries.

### Activity

In small groups, students will write an algorithm for adding new Solar System discoveries to a collection of older ones. The process should be complete and detailed so that a person can unambiguously follow the steps.

* The process itself will seem relatively simple.  Ensure students think not only about the steps to be taken but the necessary materials and resources.
* Ensure that the algorithm would work for any discovery of any name size and does not make assumptions. e.g SUPER MEGA COOL ASTEROID, etc.
* Pay particular attention to when the various materials are needed.
* The key here is that the student will need to constantly be referencing this same pool of discoveries e.g. Pool, Pool + 1 discovery, Pool + 1 discovery + another etc. etc.

Instruct students to think about how they would write a script to complete this task.  They need not write actual script, but should write pseudocode to attempt to solve the problem.  

* After groups have finished, explain to them that usually scientists organize their discoveries alphabetically not by recently discovered. Challenge them to create an algorithm that organizes their new discoveries with their old discoveries alphabetically.

The ultimate conclusion should be that they need a way to store the entire collection of discoveries, and operate on individual parts of the collection.

### Debrief

In attempting to write pseudocode, students should realize that they need variables to store the discoveries, but do not know ahead of time how many variables will be necessary. Clever students may want to simply store the message in a single variable using the **join** block.  This approach can work if they choose an unambiguous delimiter (space won't work if there are multi-word sections of the message), and is effectively the same as using a list.

Point out that, thus far, they have not seen a way to store an arbitrary number of data values. They have needed a separate variable for each value, which must be created ahead of time.

Briefly introduce the concept of a list as a means of storing multiple values in a single location.  Lists have the useful property of not having a static size, so any number of values can be added at any time.

## Accommodations/Differentiation

As in the PB&J activity, discourage stronger students from dominating the conversation and instead ask them to take on a leadership role and help other group members find issues.

Struggling students can be given permission to use a higher level of abstraction, ignoring certain details that other students will attend to.
