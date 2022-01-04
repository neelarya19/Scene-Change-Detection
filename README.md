# Scene-Change-Detection

<table>
<tr>
<td>

The detection of scenes change is a simple problem that human beings face, but it gets much
harder to handle autonomously a device that generally includes complex calculations and
algorithms.

A video scene detection model is created to detect a variety of different scenes within a
video. There is a very simple definition for a scene: It is a series of logically and chronologically
related shots taken in a specific order to depict an over-arching concept or story. The
identification of video scenes, in many video analysis applications, is a crucial pre-processing
step.
A dataset for video scene detection known as the Open Video Scene Detection (OVSD)
dataset has been provided in order to evaluate algorithms for video scene detection. Videos in
the dataset have an open-source nature, which makes them an ideal product to be used by
academics, as well as industry researchers alike.
</td>
</tr>
</table>

## DATASET
- Dataset 2012 - In the dataset, there are six video categories, and in each category, there are four to  six video sequences
- IBM video Scene Change Detection
- A dataset for video scene detection known as the Open Video Scene Detection (OVSD)
dataset has been provided in order to evaluate algorithms for video scene detection.

## MODEL
VGG16 was used for this project.VGG16 is a convolutional neural network model proposed by K. Simonyan and A. Zisserman from the University of Oxford in the paper “Very Deep Convolutional Networks for Large-
Scale Image Recognition”. The model achieves 92.7% top-5 test accuracy in ImageNet, which is a dataset of over 14 million images belonging to 1000 classes.

### LIBRARIES USED
- Numpy for array manipulation
- OpenCV (cv2) for Image Augmentation
- Keras for building the Neural Network
- Matplotlib for plotting visuals

### COMPILATION USED
- Loss function selected is sparse categorical cross-entropy
- Optimizer selected is Adam
- Validation metric chosen is accuracy

### Training
- No of epochs = 5
- Batch size = 1

## REPORT
https://drive.google.com/file/d/1cwoP5cRJ5D76PvHV_WjCDRoSJIf0h9du/view?usp=sharing

## COLLABORATORS
Neel kumar arya and Ashish Vidyarthi

## [License](https://github.com/neelarya19/Scene-Change-Detection/blob/main/LICENSE)
MIT © [Neel arya](https://github.com/neelarya19/)

