# Perceptron_Project_189
___
This folder holds the 16ML course material pertaining to Perceptrons. Resources for both intructors and students are contained.  These include course notes, a slide deck, quiz questions with answers, and a coding assignment with answers.  This material is meant to be taught in the second week of class to enforce an understanding of Linear Models and how they can be used.  Therefore, students are only one week into their co-requisites, so you can essentially expect them to know only material from EE16A and CS61A.  Namely, the students have a good understanding of Python and the basics of Linaer Algebra. For this unit, the pertinant Linear Algebra material you can build off of is Inner Products, Matrix Multiplication, Least Squares, and OMP.
___
## Usage
Instructors are encouraged to release the included notes to the students the day they give their lecture on Perceptrons.  This lecture should follow what is written in the slide deck.  When teaching the students, we want to first make a connection to biology.  This will help ground the student's knowledge in something they are already familiar with, and it will help them understand how perceptrons are related to Neural Networks at large.  After establishing this, you can get into the mechanics of how to mathematically represent a perceptron.  Make sure to make connections to 16A material whenever possible.  When talking about the update algorithm and convergence, do not go in depth about hyperperameters and learning rate as they don't understand this yet.  Instead talk about trying to minimize loss and the need for linearly seperable data.
<br>
After listening to the lecture and reading the notes, students are encouraged to take the provided quiz.  These questions are not meant to be overly complicated, they are just testing whether or not students absorbed what they were supposed to from the lesson.  Tell students to re-read the notes if they cannot pass the quiz.
<br>
Release the coding assignment 24 hours after you give lecture.  This will give students a change to internalize the material and take the quiz before jumping into the more difficult work.  The first Perceptron notebook is intended enforce students understanding of the structure of a Perceptron.  They will be building one from scratch and not using any pre-built tools.  This is to teach students what is going on behind the hood and can illuminate how and when they should be using the pre-built libraries.  The Perceptron notebook is more difficult, it should teach students how to use Scikit Learn in the contex of Audio Processing.  It is critical that students understand how to use these libraries for Linear Classification.  This part of the notebook also touches on topics from later in the course such as Discrete Forier Transforms and Featurization; give students a taste of what is to come but don't dwell on specifics.  Everything they have to implement personally will not require a deep understanding of those topics.  Students should be given a week to complete this, although it is expected to only take 8-9 hours.
<br>
<br>
By the end of this week, students should have an understanding of what a Perceptron is, how to contruct one, and how it relates to Neural Networks as a whole.  They should have a feeling for when to use linear classification, even getting a taste of how to turn non-linear problems into linear ones.  Most importantly, we want them to have gained comfortablility with using Scikit Learn and the functions it provides for doing linear classification.   
___
## Navigation
**Notebook** <br>
The coding assignments can be found in the Notebook folder.  In it you will find 4 files and a folder named _material_
* **Start_Perceptron_Intructor** - The first Perceptron Notebook with answers filled in and all cells run.  This is the notebook students should start with as it lays the foundation for what a Perceptron is and how to build one.  Intructors will use this as a reference when assisting students, note that this is not the only way to implement the solutions.
* **Start_Perceptron_Student** - The first Perceptron Notebook with none of the answers filled in.  Students should complete this notebook before moving onto **Perceptron_Student**.
* **Perceptron_Intructor** - The second Perceptron Notebook with answers filled in and all cells run.  The students should be completeing this notebook after doing the first one.  Intructors will use this as a reference when assisting students, note that this is not the only way to implement the solutions.
* **Perceptron_Student** - The second Perceptron Notebook with none of the answers filled in.  Students should tackle this notebook after they complete **Start_Perceptron_Student**. 
* **_material_** - This folder holds all of the supplimentary material for the coding assignment.  This includes all zip files of imported data sets and images.
<br>
**Lecture_Material** 
<br>
The lecture material for this week can be found in the Lecture_Material folder.  Within this folder you will find two subfolders named Notes and Slides. 
* **Notes** - This folder holds all of the material related to the notes for the week
  * **Perceptron_Notes** - Notes about perceptrons
* **Slides** - This folder holds the slide deck for the week along with its supplementary material
  * **Perceptron_Slides** - Slide deck for lecture on perceptrons
