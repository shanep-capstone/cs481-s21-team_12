# CS481 - Senior Design Project

TODO:[CI Lab](https://shanep.github.io/capstone/labs/ci/)

## Project Epic

TODO:[Project Brainstorm Lab](https://shanep.github.io/capstone/labs/project/)

The pavement inspection vehicle project will detect the cracks in the road. A vehicle is fitted with a camera at a higher level 
so that it can have a larger scope of the road. The hardware on board the vehicle is capable of running a real time object detection 
program. This program will be using YOLOv4 for object detection. There is already some work done on it. Before we start working on the
vehicle's software, we will be reading over some literature reference and learning about YOLOv4. Once we feel ready to get started, 
we will be updating the current state of features. We will be adding multi-classification abilities to the program. The instructor has
provided us with images of cracks on the road. The model will be trained on images which don't have the classes labelled. We will be writing 
a program to label the images. This needs to be done so that the model can be trained on a multi class dataset. We will establish a baseline 
score from the current model's score. Then we can fine tune the hyperparameters of the model to increase the performance. We also want to implement 
a new way of labelling the cracks so that they are better segmented. Currently, they are labelled by surrounding the cracks in a box. We want to 
label the cracks by surrounding them in a box which is close to the shape of the crack. We would also like to classify the cracks in relation to the size. 
We plan on doing this by checking the size of the box around the crack and making different categories (e.g. small, medium, big) that we can sort these
boxes into. If we feel we can further refine or add to our classification process we will also look into implementiing it as well. It is quite possible 
we'll be going into Dr.Yang's lab at some point later on this semester to test out our work on the vehicle itself. He has a track setup and ready to go
if we do end up doing this. During our work on this project, we will be checking in with Dr.Yang roughly once a month and refer to Professor Panter for
more techincal questions/issues or things relating to assignments due in the class.

### Feedback from Shane

Nice! I am excited to see this project! Let me know if there is anything you need from me.

### Tech lab

TODO:[Tech Lab](https://shanep.github.io/capstone/labs/tech/)

## Planning Lab

TODO:[Planning Lab](https://shanep.github.io/capstone/labs/planning/)

- [Jane's Plan](planning/janedoe@u.boisestate.edu.md)
- John's Plan
- Bob's Plan
