Checkpoint 1
Task 1
Pandas exercises : We learnt how to import pandas and numpy and used some library functions in order to extract the information about the dataset.
Task 2 
Matplotlib exercises : In this, we tried to get the statistical info about different columns of the dataset. And also plotted various kinds of graphs for the data such as histograms and box type.

Overall we learnt several library functions, numpy, panda, seaborn to fetch as much information of the dataset as we can.The practice notebooks have also been attached for the same.

Checkpoint 2
In the second phase - Week 1 of our project we were introduced to openCV, anaconda, machine learning. First of all we watched tutorials for openCV, pytorch basics. Understood image manipulations processing and image segmentation contours.Performed a live sketcher project. 
In Week 2, we were introduced to deep leaning, neural network for which we watched a playlist. We got an idea of how does neural networking take place. We looked at Deep learning library - pytorch.
In week 3, we covered live age and gender detection.

Task 4
Live Age and Gender Detection : We watched a 2hr long video, and understood and wrote the code to detect live age and gender. But it turned out that it wasn't trained properly since it gave wrong results sometimes.

Task 5
Age and Gender Detection on YouTube Videos : This was a modified code, where it detected age and gender for a youtube video.
All the practice notebooks are attached.

Checkpoint 3
We first saw a basic facial features recognition using cv2 video system. The notebooks are attached.

Task 7
Making Colab Based Face Detection + Recognition + Cluster Project : Understood the raw code given by our mentor. First installed the required libraries, then mounted google drive, further selected source of images (I chose online). Created the ouput directory for downloading images, and downloaded them. Then got the face encodings (trained the model). 
Now we uploaded a test image to detect and recognize each of the faces by bounding it in a box and displaying person's "name".
I added an extra feature of "facial attributes analysis" which returns the age, gender, emotion and race of each detected face. 
So the mechanism behind this was, before displaying bounding box and name, I copied the "image" as "image2". So, I used "image" for displaying box and name of each person. And, used image2 for cropping each of the faces and detecting their facial attributes using deepface analyze function (had to use "image2" instead of "image" because the bounding box was creating problem in detecting the face).
It returned correct results on testing.
Finally added code for clustering and renaming. The images of similar faces appeared as a montage.



