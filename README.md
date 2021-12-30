# AICUP-2021
## Install 
<pre><code> $ git https://github.com/fan1071221/Traditional-Chinese-Scene-Character-Recognition-Contest-Advanced-Competition.git</code></pre>
## Links

* YOLOv5x6 Weight1
(https://drive.google.com/file/d/1C6_MYhZqZenIScHNpHlxorxepigzmlW6/view?usp=sharing).

* YOLOv5x6 Weight2
(https://drive.google.com/file/d/1--rYhldKNFpVb8n4lfXgTFw3DHqOokFt/view?usp=sharing)

* Colab

## Training
 
<pre><code>!python train.py --img 1365 --batch 4 --epochs 300 --data data/TWStreet.yaml --weights yolov5x6.pt
</code></pre>
## Detect
<pre><code>!python detect.py --source /content/drive/MyDrive/test --weights /content/drive/MyDrive/best.pt /content/drive/MyDrive/best1.pt --class 0 2 3 4 --conf 0.75 --save-txt --img-size 1365 --augment
</code></pre>

## Images

![This is a alt text.](img_3010.jpg "This is a sample image.")
