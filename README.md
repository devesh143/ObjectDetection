This is basic project for Object detection using yolo(you only look once) which detects objects in a raw image and processes a new image with detected objects

Please consider using **yolo.weights** and add that to main folder to run the code
You can find weights on this following link: https://github.com/patrick013/Object-Detection---Yolov3/blob/master/model/yolov3.weights

To run the code use this command in local **powershell or terminal**:
python yolo_opencv.py --image dog.jpg --config yolov3.cfg --weights yolov3.weights --classes yolov3.txt
