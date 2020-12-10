# WRS_ObjectDetection

Object detection for World Robot Summit(WRS)

Dataset: 12 class type, 1920 x 1200 pixels, RGB-A 4 channels, png format 250 images    
<https://github.com/RasmusHaugaard/wrs-data-collection>

Each image contains almost always 12 objects.    

EfficientDet <https://github.com/google/automl.git>    

```
conda create -n ws python=3.7
conda activate ws

git clone https://github.com/google/automl.git
pip -r requirements.txt
pip install -U 'git+https://github.com/cocodataset/cocoapi.git#subdirectory=PythonAPI'
```
