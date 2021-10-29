# YOLO v3 Object Detection Algorithm

## Note=> You need to have darknet, OpenCV, CUDA, CUDNN installed along with path variables set.

## This repo contains the following files:

#### custom-backup : contains the trained model (@9500 epochs)

#### custom-cfg :

**custom-cfg/obj.data =>** contains train.txt, test.txt which further contains the path to dataset images, backup and number of classes

**custom-cfg/obj.names =>** class names (e.g. Pothole)

**custom-cfg/yolo-pothole-train.cfg =>** config file

#### data:

**data/labels =>** default labels from darknet

**data/Pothole=>** dataset images with annotation(.txt)

#### test.jpg: Image to test

#### predictions.jpg: Predictions to test image

#### Dataset Link: [Pothole Dataset](https://www.kaggle.com/sachinpatel21/starter-code-to-view-dataset-images/data)

#### Tool to label: [LabelImg](https://github.com/tzutalin/labelImg)
