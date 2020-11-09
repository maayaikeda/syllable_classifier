# Syllable Classifier


## Objective:
In songbird research, researchers manipulate the brain to see if it effects the birds' singing behavior. However, analyzing different features of thousands of songs takes a long time. Here, I used deep learning to develop a classifier that segments and classify the elements (syllables) of songs.
After running this notebook, you will have:

*  A deep learning model that can predict the syllable label of a new audio file (see image bellow).

(Using the model, you will get:)

*  A folder containing audio files of individual syllables
*  An png plot of a spectogram with predicted syllables labeled like the example below.
*  A CSV file with predicted syllable label, syllable duration, and start and end time. You can add code to extract other features such as pitch later.


## Work flow:

Preparation:
1.   Filter audio file
2.   Segment files into syllables
3.   Convert the audio files to images
4.   Label/sort the files

Train the classifier:
5.   Train the classifier
6.   Save the model

Use the classifier:

7.   Load the model
8.   Upload a new song using the upload widget
9.   Process the new file and classify detected syllables
10.   Create a table and an image with predicted syllable labels



![image](https://github.com/maayaikeda/syllable_classifier/blob/main/images/Unknown-2.png)



[Link to Google Colab notebook](https://colab.research.google.com/drive/1iOrfKuesu-pDgTeEipsfHE2Mj9W-M4Mk?usp=sharing)

## How to use the notebook:
1.  Create a copy of the notebook in your google drive.
2.  Change runtime to GPU (Runtime>Change runtime type)
3.  Change directory to your google drive (go to section "Segment files into syllables)
4.  Upload a song file in your directory
5.  Go through all the cells


