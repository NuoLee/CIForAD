# CIForAD
### Cross-modal Integration Framework for Anomaly Detection in Surveillance Videos
This is an implementation of the paper Cross-modal Integration Framework for Anomaly Detection in Surveillance Videos. For convenience, we upload the compressed files.

### Implementation
- Linux OS or Windows OS 
- Python 3.8
- Numpy 1.19.5
- Tensorflow 2.4.0
- Torch 1.7.1
- Opencv 4.5.5
- Scikit_learn 1.0.2
- Matplotlib 3.5.2

### Datasets
- UCSD Ped2
- CUHK Avenue
- ShanghaiTech

### How to run?  
- Set the parameters in the ```args.py``` file.
- For training,  python ```train.py```
- It requires the pre-trained yolo model in the folder models/yolov3/yolov3.ckpt (https://github.com/wizyoung/YOLOv3_TensorFlow)
- For testing, python ```test.py```


