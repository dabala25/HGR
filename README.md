Hand Gesture Recognition

Detect 8 gestures :
Fist, Victory, Three, Five, Nice, Side, Thumbs Up and Thumbs Down

1.Install Reqiurements:

1-1 clone yolov5 : git clone https://github.com/ultralytics/yolov5

1-2 clone train model : git clone https://github.com/dabala25/HGR

1-3 install packages : pip install -r requirements.txt

2-Model:
There are 2 model to detect
model s in exp folder and model m in exp2 folder

move train folder to yolov5/runs

3-Detect:
python detect.py --source 0 --weights runs/train/exp2/weights/best.pt --conf 0.6

special thanks to https://github.com/shahriarEbram
