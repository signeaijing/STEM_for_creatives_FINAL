# STEM_for_creatives_FINAL_ASSESMENTS 

<h3> INTRODUCTION  </h3>
  
This repository contains the solutions to the weekly assignments for the STEM for Creative class at the Creative Computing Institute at the University of the Arts London 2022/2023. 
The three weekly assignments has all been solved using Python and a variety of chosen Python libraries in VS Code, as Jupyter Notebook kept causing unresolved trouble. 

<h3> ASSIGNMENT 1 </h3>
Started working on this assignment in Jupyter Notebook, but it kept crashing so I went on the use VS Code, which is what I usually use and which I like better. 
Mostly questions on data and data processing with starting point in a data collection from a musuem. 
To make answering the questions easier and more manageable as I go along I put all the columns I need in variables in the setup. 

<h3> ASSIGNMENT 2 </h3>
This assignment was about designing a onset detector that were able to detect onsets (peaks in amplitude) from an audiofile. For an onset to count as an onset it needs to live up to three different conditions: if a certain time has passed before the last onset, if it's larger than the average of the surrounding samples, and if it's larger than the maximum peak  of the surroinding samples. 
The detector is made by creating an empty list for the timestamps and the amplitude, which can be plotted against each other with numpy library. 
The detector iterates through the samples and checks the conditions for each sample +- half the window_size. If all the conditions are met it will append the samplevalue and the timestamp to the lists. 

<h3> ASSIGNMENT 3 </h3>
The third assignment was a test in experiment design. I am testing to see if people who watch inspiring stuff on a platform like TikTok will see an increase in how well they perform in front of a crowd. The experiment is planned as a T-Test and the hypothesis is: Poetic writers who have been watching inspiring videos on TikTok right before performing in front of a crowd gets less nervous on stage. 
