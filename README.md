![alt text](/static/ss.jpeg?raw=true "example output")
This app is based on YOLOV7 object detection library engine from WongKinYiu repository on https://github.com/WongKinYiu/yolov7 and based on DeepSort object tracking implementation

Run this command to run the app
```bash 
python detect_count_and_track.py --weights yolov7.pt --conf 0.60 --source ../videos/traffic.mp4 --view-img --nosave --no-trace
```

Download yolov7 weight from YOLOV7 assets repository https://github.com/WongKinYiu/yolov7/releases
