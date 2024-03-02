# SFU CMPT 340 Project -- AmIHavingAStroke.ca
A common symptom of strokes is facial drooping and asymmetry. We present a Python program that aims to help patients assess
their own health by analysing their face and determining the likelihood
of a positive diagnosis. We pre-process and detect facial landmarks of the
dataset, consisting of stroke patients and healthy individuals, with the
dlib library. We then extract features from the landmarks, and finally we
train an SVM model and use it to predict if the user is experiencing a
stroke. The experimental results of our system average to 93%, indicating a high accuracy in facial droop recognition, which will help identify
patients having a stroke.

