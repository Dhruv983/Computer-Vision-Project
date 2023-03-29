# Data Sourced From Kaggle
## (Link)[https://www.kaggle.com/datasets/andrewmvd/face-mask-detection]

# Model Parameters

* Epochs : 100
* Batch Size : 16
* train Img : 640
* test Img :224

# How to train Model

* After Creating YAMl config and datasets
* Run Command python train.py --img 640 --batch 16 --epochs 100 --data ../mask_yaml.yaml --weights yolov5s.pt --workers 0

# How run model using Yolov5

* open Yolov5 directory
* open terminal
* type python detect.py --weights best.pt --source 0