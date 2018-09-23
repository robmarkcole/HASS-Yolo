# HASS-Yolo
Object detection in Home-Assistant using Yolo. This custom component is a demonstrator, and will likely not work on a raspberry-pi.

Inspired by https://github.com/joakimeriksson/ai-smarthome/tree/master/yolov3-ha but will be a native component. 

Yolo: https://pjreddie.com/darknet/yolo/

### Tiny YOLOv3
We have a very small model as well for constrained environments, yolov3-tiny. To use this model, first download the weights:

wget https://pjreddie.com/media/files/yolov3-tiny.weights
Then run the detector with the tiny config file and weights:

./darknet detect cfg/yolov3-tiny.cfg yolov3-tiny.weights data/dog.jpg

### Articles
* https://medium.com/ml-everything/how-to-actually-easily-detect-objects-with-deep-learning-on-raspberry-pi-4fd40af84fee
* https://medium.com/@manivannan_data/how-to-train-yolov3-to-detect-custom-objects-ccbcafeb13d2
* https://github.com/burningion/poor-mans-deep-learning-camera
