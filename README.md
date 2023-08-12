# Object detection using TensorFlow Lite on Android
### Overview
This is an android app for object detection using [TensorFlow Lite](https://www.tensorflow.org/lite) on a mobile device.  It is  trained on the ImageNet dataset which can detect about 90 classes including banana, scissors, laptop, remote, vase etc. The main issue faced earlier of object detection on mobile is that the models are often too big to run. Tensorflow Lite solves this problem by providing a lightweight solution to run machine learning models on mobile.  yourself how nicely the app works and detects multiple objects quickly.

### TensorFlow Lite Model
TensorFlow Lite is not designed to train a model, the model can be trained on a higher power device. Then, the pretrained model can be converted to a TensorFlow Lite format (.tflite), which has a smaller footprint than can be easily run on a mobile or other embedded devices for classification, regresion or other such tasks. The model (.tflite) file and the class labels (.txt) file need to be placed in the [assets]folder of the android app.

### The Android App for Object Detection
I have followed the [TensorFlow Lite example for Object Detection](https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection).
