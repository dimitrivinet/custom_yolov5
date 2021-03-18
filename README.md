# custom_yolov5


```
git clone https://github.com/ultralytics/yolov5  # clone repo
cd yolov5
python3 -m venv yolov5_venv
source yolov5_venv/bin/activate
pip install -U -r yolov5/requirements.txt  # install dependencies
```
Download best.pt from trained model then:

```
python3 detect.py --weights <path/to/best.pt> --source <source; 0 for webcam, 6 for RealSense for me>
```
