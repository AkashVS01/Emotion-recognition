# Facial Emotion Recognition from videos

Recognizing facial emotion has become an popular topic in the field of deep learning. Emotion recognition models has been created using ResNet-50 and SqueezeNet CNN architectures.These models take the video as input, extract the frames from the video every 'n' seconds and predict the emotion exhibited by the person in each frame and store the frames with the timestamp indicating when the frame was extracted and the emotion exhibited as a image file name.

## Dataset

The dataset used for recognizing emotions was FER-2013.Download dataset from https://www.kaggle.com/deadskull7/fer2013

## CNN Models

ResNet-50 and SqueezeNet are the CNN architectures that has been used to develop the emotion recognition models. Face is detected from the frames of a video using OpenCV library and haar-caascade face detection. Frames that were extracted will be sent into the trained model to predict the emotion exhibited by the person in each frame. Both the ResNet-50 and SquuezeNet architectures are developed from scratch.

## Results

ResNet-50 model gives a training accuracy of 80% and testing accuracy of 68%.
SqueezeNet gives a training accuracy of 73% and testing accuracy of 64% 

