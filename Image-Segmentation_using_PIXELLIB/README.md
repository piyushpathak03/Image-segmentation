# Segmenting the images with the help of pixellib

![mylogo](Images/PixelLibLogo.png) <br> <br>

Pixellib is a library for performing segmentation of objects in images and videos. It supports the two major types of image segmentation:

1.Semantic segmentation

2.Instance segmentation

**Step:1**

Download the model file with [predefined coco.h5](https://github.com/matterport/Mask_RCNN/releases/tag/v2.0)

**Step:2**
Install the requirements.txt in local

**Step:3**

### Input image
![Input image of crowd](https://github.com/piyushpathak03/Image-segmentation/blob/main/Image-Segmentation_using_PIXELLIB/crowd.jpg)

**Step:3**

```
import pixellib
from pixellib.instance import instance_segmentation
segment_image = instance_segmentation()
segment_image.load_model("mask_rcnn_coco.h5") 
segment_image.segmentImage("input.jpg", show_bboxes = True, output_image_name = "output.jpg")
```


### Output image
![Output image of crowd after segmentation](https://github.com/piyushpathak03/Image-segmentation/blob/main/Image-Segmentation_using_PIXELLIB/output_crowd.jpg)

## About me

**Piyush Pathak**

[**PORTFOLIO**](https://anirudhrapathak3.wixsite.com/piyush)

[**GITHUB**](https://github.com/piyushpathak03)

[**BLOG**](https://medium.com/@piyushpathak03)


# 📫 Follw me: 

[![Linkedin Badge](https://img.shields.io/badge/-PiyushPathak-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/piyushpathak03/)](https://www.linkedin.com/in/piyushpathak03/)

<p  align="right"><img height="100" src = "https://media.giphy.com/media/l3URDstnIjBNY7rwLB/giphy.gif"></p>

