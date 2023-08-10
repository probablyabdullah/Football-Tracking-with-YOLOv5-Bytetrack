# **Football Players Tracking on a pitch using YOLOv5 + ByteTrack**

 ![Static Badge](https://img.shields.io/badge/YOLOv5-yellow)![Static Badge](https://img.shields.io/badge/Roboflow-purple)![Static Badge](https://img.shields.io/badge/Pytorch-green)![Static Badge](https://img.shields.io/badge/Bytetrack-red)




## A YOLOv5-based object detection model that identifies and tracks the players, the ball, the sideline referees and the goalkeeper separately when provided with a TV broadcast camera feed. Bytetrack is further used to enhance the model's capabilities! ⚽

## About
In my project, I utilized Roboflow Universe, an open-source computer vision dataset repository with over 100,000 datasets. We make use of two pretrained models one after another and apply custom annotations on the latter to get our output.

## Useful links:

* [YOLOv5 repository](https://github.com/ultralytics/yolov5) 🔗
* [ByteTrack repository](https://github.com/ifzhang/ByteTrack) 🔗
* [Roboflow Notebooks](https://github.com/roboflow/notebooks) 🔗

## Steps Involved:

* Setup🛠️<br>
* Download data🛠️<br>
* Install YOLOv5🛠️<br>
* Install ByteTrack and other libs🛠️<br>
* Custom annotator🛠️<br>
* Detect ball possession🛠️<br>
* Full video tracking🛠️<br>
* Put everything together🛠️<br>

## Output!⚽

### Sample Video Frame:
![Media Player 10-08-2023 22_07_57](https://github.com/probablyabdullah/Football-Tracking-with-YOLOv5-Bytetrack/assets/79295754/62224168-1d19-4773-a73e-5436b0853255)



### Output Video after first petrained model:

![Media Player 10-08-2023 22_07_13](https://github.com/probablyabdullah/Football-Tracking-with-YOLOv5-Bytetrack/assets/79295754/a0cd95d1-6eb1-4441-a25d-8694a9fd2764)


### Output video after v2 pretrained model:
![Media Player 10-08-2023 22_06_55](https://github.com/probablyabdullah/Football-Tracking-with-YOLOv5-Bytetrack/assets/79295754/b1b36309-d558-43aa-a529-53410e39bee2)



### Frame after applying Bytetrack:
![output2](https://github.com/probablyabdullah/Football-Tracking-with-YOLOv5-Bytetrack/assets/79295754/acc502a5-7a0d-4dec-a19b-4395dafd8a4b)

