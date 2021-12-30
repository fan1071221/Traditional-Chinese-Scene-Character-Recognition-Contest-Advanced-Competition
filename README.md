# AICUP-2021
## Install 
<pre><code> $ git https://github.com/fan1071221/Traditional-Chinese-Scene-Character-Recognition-Contest-Advanced-Competition.git</code></pre>
## Links

* YOLOv5x6 Weight1
(https://drive.google.com/file/d/1C6_MYhZqZenIScHNpHlxorxepigzmlW6/view?usp=sharing).

* YOLOv5x6 Weight2
(https://drive.google.com/file/d/1--rYhldKNFpVb8n4lfXgTFw3DHqOokFt/view?usp=sharing)

* Colab
## Environment Setting
* yolov5/data資料夾中新增TWStreet.yaml

* Goole Driver下載yolov5\runs\train\exp8\weights\best.pt把它放在yolov5資料夾中指定位置

## Training

**第一次訓練**  
<pre><code>!python train.py --img 640 --batch 8 --epochs 300 --data data/TWStreet.yaml --weights yolov5x.pt
</code></pre>
**Colab中斷 想持續訓練**
<pre><code>!python train.py --img 640 --batch 8 --epochs 300 --data data/TWStreet.yaml --weights /content/drive/MyDrive/yolov5/runs/train/exp8/weights/last.pt
</code></pre>

## Images

![This is a alt text.](img_3010.jpg "This is a sample image.")
