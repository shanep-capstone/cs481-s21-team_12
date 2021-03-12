# Journal 7 

We finally picked one github repo from the list of alternatives that Dr. Lu provided.
The repo does a good job of labelling the objects not in boxes, but it aligns close to the 
boundary of the object. That with YoloV5 should be sufficient for this task. One of the main
 things we need to do is data labelling. For a model to predict new classes, it needs to see 
 those classes. So we will need to write an algorithm to look at an image and point out the crack 
 and then measure how big the crack is and classify it. I think we will use YoloV5 here to detect 
 the crack, and modify the output to measure and label the crack. 
 
 # Things to do :
 
 * Set up data pipelines to pre-process the images.
 * Set up the github repo
 * Start really cracking this problem down
