**Garbage_ben-_detection**
Welcome to the YOLOv5 Garbage Bin Detection project! This project utilizes YOLOv5, a powerful object detection model, to identify garbage bins in images. The model is trained on a custom dataset, allowing you to perform garbage bin detection on your own images.
If you are using Google Colab, make sure to mount your Google Drive to access necessary files.
run the Yolov5 and go to yolov5 folder in drive and open it . then go to open data folder inside data you will find the coco128.yaml .. click the 3 icon and download it.
after download customize it according to your dataset and uplaod it inside the label data folders like my data folder is Garbage_ben  .
After that just copy the path of customize coco.yaml  and put it into the code and run ..eg !python train.py --img 640 --batch 8 --epochs 100 --data /content/drive/MyDrive/carbage_ben/mycoco.yaml --weights yolov5l.pt --cache
put the path after --data to .yaml
then go to folder inside the drive name is yolov5 .. inside yolov5 open the data folder and then open folder runs.. after open the folder runs then open train folder and inside the train folder you can see the exp folder and open it  you will find weights folder  copy the path of weights folders and out here ..i.e.. !python detect.py --weights /content/yolov5/runs/train/exp/weights/best.pt --img 640 --conf 0.2 --source /content/garbage.jpg
**Contributing**
Contributions are welcome! Feel free to report issues or submit pull requests to improve the project.
