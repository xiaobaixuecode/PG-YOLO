PG-YOLO re-implementation using PyTorch

### Installation

```
pip install -r requirements.txt
```

### Train

* Configure your dataset path in `train.py` for training
* Run `yolo train model=yolov11s.pt/PG-YOLO.pt data=$.yaml epochs=300 imgsz=640 batch=32` for training

### Val

* Configure your dataset path in `val.py` for testing
* Run `yolo val model = yolov11s.pt/PG-YOLO.pt data = $.yaml` for valing

`$` represents the name of the yaml file

The model can autonomously choose between yolov11s.pt or PG-YOLO.pt.

### Reference

* https://github.com/ultralytics/ultralytics
