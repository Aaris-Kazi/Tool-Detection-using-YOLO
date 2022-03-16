<div align="center">
   ## It is our major project based on Arduino
<p>
   <img width="640" src="https://github.com/Aaris-Kazi/Tool-Detection-using-YOLO/blob/main/output.gif"></a>
</p>

<div align="center">
   <a href="https://github.com/Aaris-Kazi">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-github.png" width="2%"/>
   </a>
   <img width="2%" />
   <a href="https://www.linkedin.com/in/aaris-kazi/">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-linkedin.png" width="2%"/>
   </a>
   <img width="2%" />
   <a href="https://twitter.com/AarisKazi">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-twitter.png" width="2%"/>
   </a>
   <img width="2%" />
   <a href="https://www.instagram.com/aaris_kazi/">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-instagram.png" width="2%"/>
   </a>
</div>

## <div align="center">Documentation</div>

See the [YOLOv5 Docs](https://docs.ultralytics.com) for full documentation on training, testing and deployment.

## <div align="center">Quick Start Examples</div>

<details open>
<summary>Install</summary>

Clone repo and install [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) in a
[**Python>=3.7.0**](https://www.python.org/) environment, including
[**PyTorch>=1.7**](https://pytorch.org/get-started/locally/).

```bash
git clone https://github.com/Aaris-Kazi/Tool-Detection-using-YOLO.git  # clone
cd Tool-Detection-using-YOLO
pip install -r requirements.txt  # install
```

</details>

<details open>
<summary>Run the Code</summary>
   For Using Laptop camera 

```
python app.py --weight latest.pt --img 100 --conf 0.55 --source 0
```
   
   For Mobile Stream using Ip camera 

```
python app.py --weight latest.pt --img 100 --conf 0.55 --source http://192.168.0.102:8080/video
```
