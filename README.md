## RVOS: Real-world Video Object Segmentation Dataset
  
RVOS is the first real-world video object segmentation dataset. It was released on Oct. 18, 2017.
  
There will be two mainly contributions of this dataset: 
  
First, there is a lack of real-world data of video object segmentation. DAVIS is captured using expensive video camera. We use mobile phone to capture objects. The photographers are volunteer and not well trained. RVOS will fill the gap for real-world video object segmentation. 
  
Second, in E-commerce area, there needs to show products using mobile phone. The sellers capture the video of products which will be segmented in E-commerce mobile applications. Then the background can be changed or composited to a better one. We hope our dataset is useful for this purpose. 
  
It consists of two hundreds short videos, which focus on common object in family and office.
  
The dataset is challenging because the objects in these videos vary wildly in their categories. There are occlusions and sudden motion and other complexity. The videos are captured in portrait using mobile phones. About 35 frames are annotated which are selected uniformly in each video. Every frame is rotated and resized to 854*480, which is 480p resolution, same as the DAVIS dataset.
  
Raw videos can be downloaded via: <a href="https://drive.google.com/open?id=0B7mv0bFAqJGEbGNTdjVBNW40QjQ">Google Drive</a>  or  <a href="https://pan.baidu.com/s/1c2NGOLE">Baidu Drive</a>    
  
Selected frames and annotations can be downloaded via: <a href="https://drive.google.com/open?id=0B7mv0bFAqJGERFM1Sy14SHY5SEE">Google Drive</a>  or  <a href="https://pan.baidu.com/s/1dEGD10t">Baidu Drive</a>

### Some Samples:
<a href="http://www.youtube.com/watch?feature=player_embedded&v=Kq280YXHlBU
" target="_blank"><img src="https://img.youtube.com/vi/Kq280YXHlBU/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=K8IKsPgdNJA
" target="_blank"><img src="https://img.youtube.com/vi/K8IKsPgdNJA/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=tlOjUl_VASs
" target="_blank"><img src="https://img.youtube.com/vi/tlOjUl_VASs/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=LBOShbTMHtY
" target="_blank"><img src="https://img.youtube.com/vi/LBOShbTMHtY/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=sujNRE1xdsw
" target="_blank"><img src="https://img.youtube.com/vi/sujNRE1xdsw/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=Ecnm6xvbTE4
" target="_blank"><img src="https://img.youtube.com/vi/Ecnm6xvbTE4/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=FdGfQhKliqs
" target="_blank"><img src="https://img.youtube.com/vi/FdGfQhKliqs/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" border="10" /></a>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=84qyzuq-LAA
" target="_blank"><img src="https://img.youtube.com/vi/84qyzuq-LAA/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="320" height="240" border="10" /></a>

All sequences are owned by the authors of `RVOS` and are licensed under Creative Commons Attributions 4.0 License.

### Folder structure:
.
├── README.md # readme of the dataset
|
├── JPEGImages # folders containing frames
|   └── 480p
├── Annotations # folders containing human annotations
|   └── 480p
└── ImageSets
    ├── train.txt # list of all the sequences for training
    ├── trainval.txt # all the sequences for training and validation    
    └── val.txt # list of all the sequences for validation

### Contributors:
to be added after the paper review of CVPR 2018. 
