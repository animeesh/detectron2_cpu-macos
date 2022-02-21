# detectron2_cpu-macos
- create an env with python < 3.9
- clone the reppo using the following command.
  git clone https://github.com/facebookresearch/detectron2.git
  for understanding the detectron 
  
  
Create a conda environment with conda create -n detectron2 python=3.7
conda activate detectron2
Install PyTorch and Torchvision --  conda install pytorch torchvision torchaudio -c pytorch
Install OpenCV with conda install -c pip install opencv-python
Install Detectron2 via this comand-- python -m pip install 'git+https://github.com/facebookresearch/detectron2.git' ( this worked well on my M1-based Mac Mini.)
  
  
  

 ##This configuration worked out for me ##
  python==3.7
  torch==1.10.0
  torchvision==0.11.3
  pycocotools==2.0.2

  
  - To validate you are in proper location and everythin is set, Run following command
   Run --  python -m detectron2.utils.collect_env

  for the first run it will download the pkl file of ~ 178mb
  
  ## Demo
  Detectron2_cpu_result:

![british.jpeg](https://github.com/wangermeng2021/ScaledYOLOv4-tensorflow2/blob/main/images/pothole_p5_detection_3.png)
![british_result.jpeg](https://github.com/wangermeng2021/ScaledYOLOv4-tensorflow2/blob/main/images/chess_p5_detection.png)


