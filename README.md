# Perceptron_Project_189
___
This folder holds the 16ML course material pertaining to Perceptrons. Resources for both intructors and students are contained.  These include course notes, a slide deck, quiz questions with answers, and a coding assignment with answers.  The material taught this weel is meant to enforce an understanding of Linear Models and how they can be used.  At this point, we can expect the students to have a good understanding of Python and Linaer Algebra. For this unit, pertinant Linear Algebra material you can build off of is Inner Products, Matrix Multiplication, Least Squares, and OMP.
___
## Usage
Instructors are encouraged to release the included notes to the students the day they give their lecture on Perceptrons.  This lecture should follow what is written in the slide deck.  When teaching the students, we want to first make a connection to biology.  This will help ground the student's knowledge in something they are already familiar with, and it will help them understand how perceptrons are related to Neural Networks at large.  After establishing this, you can get into the mechanics of how to mathematically represent a perceptron.  Make sure to make connections to 16A material whenever possible.  When talking about the update algorithm and convergence, make sure to talk about trying to minimize loss and the need for linearly seperable data.
<br>
After listening to the lecture and reading the notes, students are encouraged to take the provided quiz.  These questions are not meant to be overly complicated, they are just testing whether or not students absorbed what they were supposed to from the lesson.  Tell students to re-read the notes if they cannot pass the quiz.
<br>
Release the coding assignment 24 hours after you give lecture.  This will give students a change to internalize the material and take the quiz before jumping into the more difficult work.  The first Perceptron notebook is intended enforce students understanding of the structure of a Perceptron.  They will be building one from scratch and not using any pre-built tools.  This is to teach students what is going on behind the hood and can illuminate how and when they should be using the pre-built libraries.  The Perceptron notebook is more difficult, it should teach students how to use Scikit Learn in the contex of Audio Processing.  It is critical that students understand how to use these libraries for Linear Classification.  This part of the notebook also touches on topics such as Discrete Forier Transforms and Featurization.  Everything they have to implement personally will not require a deep understanding of those topics, but it is helpful if they are familiar with the information.  Students should be given a week to complete this, although it is expected to only take 8-9 hours.
<br>
<br>
By the end of this week, students should have an understanding of what a Perceptron is, how to contruct one, and how it relates to Neural Networks as a whole.  They should have a feeling for when to use linear classification, even getting a taste of how to turn non-linear problems into linear ones through featurization.  Most importantly, we want them to have gained comfortablility with using Scikit Learn and the functions it provides for doing linear classification.   
___
## Navigation
**Coding_Assignments** <br>
The jupyter notebook coding assignments for the week are located in the Coding_Assignments folder. This holds all relavent coding material for instructors and students.
* **Start_Perceptron_Intructor** - First Perceptron Notebook with answers filled in and all cells run.  This goes along with the notebook that the students are completing first.  Intructors will use this as a reference when assisting students, note that this is not the only way to implement the solutions.
* **Start_Perceptron_Student** - First Perceptron Notebook with none of the answers filled in.  Students should complete this notebook before moving onto _Perceptron_Student_.
* **Perceptron_Intructor** - Second Perceptron Notebook with answers filled in and all cells run.  This goes along with the notebook that the students are completing second.  Intructors will use this as a reference when assisting students, note that this is not the only way to implement the solutions.
* **Perceptron_Student** - Second Perceptron Notebook with none of the answers filled in.  Students should tackle this notebook after they complete _Start_Perceptron_Student_. 

**Lecture_Material** <br>
The lecture material for this week can be found in the Lecture_Material folder.  Within this folder you will find two subfolders named Notes and Slides. 
* **Notes** - This folder holds all of the material related to the notes for the week
  * **Perceptron_Notes** - PDF containing the Perceptron notes for the week.  This file should be provided to students so that they can review the material they learned in lecture.
* **Slides** - This folder holds the slide deck for the week along with any supplementary material
  * **Perceptron-Slides** - PDF of a slide deck for the lecture on Perceptrons
  
**Quizzes** <br>
The quiz material for the week can be found in this folder.
* **Perceptron_Quiz** - PDF of a 10 question quiz about Perceptrons.  This document contains both the questions and the answers.  Can be provided to students as is so that they can check their understanding of the material from the week. 
