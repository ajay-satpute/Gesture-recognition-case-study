# Gesture-recognition-case-study

Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature 
in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. 

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

1) Thumbs up:  Increase the volume,
2) Thumbs down: Decrease the volume,
3) Left swipe: 'Jump' backwards 10 seconds,
4) Right swipe: 'Jump' forward 10 seconds,
5) Stop: Pause the movie
 
Each video is a sequence of 30 frames (or images).

Understanding the Dataset
The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 
30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 
