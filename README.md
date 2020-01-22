# Repulsion-loss-yolo-pytorch

This program is only available on the single class dataset. We apply it on the vehicle detection in the crowd situation and get a feasible result. For multiple classes, only modify ultis.py to compute the repulsion loss separately.

The codes are based on the YOLO in Pytorch(https://github.com/ultralytics/yolov3)


## Datasets
* Make own datasets by voc_label.py
* Modify cfg files, voc.name and voc.data according to https://github.com/ultralytics/yolov3/wiki/Example:-Train-Single-Class

## Yolo
main modifications are in the train.py and ultis.py
