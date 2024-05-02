# Human-Violence-Detection


## Model Links:
Openpose model: [Click here to download](https://drive.google.com/file/d/1YuJB9I7F1plPab3vjmiwqkRH_c7-aVKQ/view?usp=sharing)<br>
YOLO model: [Click here to download](https://drive.google.com/file/d/14ufVFdTUgYO__KrDdsLKBPUmMhuLaXUx/view?usp=sharing)


## Setup
Move pretrained models to `\models`
```
cd Violence-Detection
mv yolo.h5 \models
mv openpose.h5 \models
```

```
pip install -r requirements.txt
```

Set video path in `Violence-Detection\main.py`
## Inference
```
python3 main.py
```
