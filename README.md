# FenceNotes
记录个人学习过程中的一些信息

# 1.综合类
## 1.1. Paddle(百度飞桨)
### 1.1.1 PaddleGAN
- 地址：<https://github.com/PaddlePaddle/PaddleGAN/tree/develop>
#### 1.1.1.1 LapStyle (图片转不通风格)
- 地址：<https://github.com/PaddlePaddle/PaddleGAN/blob/develop/docs/en_US/tutorials/lap_style.md>
- 描述：PaddleGAN下的样例代码，可以生成不通风格照片
- 评价：使用简单，官方提供四个风格的预训练模型，效果好
![image](https://github.com/fense8000/FenceNotes/assets/7136821/85de9d66-4832-41b5-aa30-1fd9cca17e3b)

### 1.1.2 PaddleDetect
- 地址：<https://github.com/PaddlePaddle/PaddleDetection>
- 描述：PaddleDetection是一个基于PaddlePaddle的目标检测端到端开发套件，在提供丰富的模型组件和测试基准的同时，注重端到端的产业落地应用，通过打造产业级特色模型|工具、建设产业应用范例等手段，帮助开发者实现数据准备、模型选型、模型训练、模型部署的全流程打通，快速进行落地应用。
![image](https://github.com/fense8000/FenceNotes/assets/7136821/6b07eef0-e39f-4a7f-9f56-bf3faa1afcb6)

### 1.1.3 [PaddleYOLO](https://github.com/PaddlePaddle/PaddleYOLO)
- 地址：<https://github.com/PaddlePaddle/PaddleYOLO>
- 描述：PaddleYOLO是基于PaddleDetection的YOLO系列模型库，只包含YOLO系列模型的相关代码，支持YOLOv3、PP-YOLO、PP-YOLOv2、PP-YOLOE、PP-YOLOE+、RT-DETR、YOLOX、YOLOv5、YOLOv6、YOLOv7、YOLOv8、YOLOv5u、YOLOv7u、YOLOv6Lite、RTMDet等模型，COCO数据集模型库请参照 ModelZoo 和 configs。


## 1.2. OpenMMLab (商汤科技)
- 地址：<https://github.com/open-mmlab>
- [MMEngine](https://github.com/open-mmlab/mmengine): OpenMMLab foundational library for training deep learning models.
- [MMCV](https://github.com/open-mmlab/mmcv): OpenMMLab foundational library for computer vision.
- [MIM](https://github.com/open-mmlab/mim): MIM installs OpenMMLab packages.
- [MMClassification](https://github.com/open-mmlab/mmclassification): OpenMMLab image classification toolbox and benchmark.
- [MMDetection](https://github.com/open-mmlab/mmdetection): OpenMMLab detection toolbox and benchmark.
- [MMDetection3D](https://github.com/open-mmlab/mmdetection3d): OpenMMLab's next-generation platform for general 3D object detection.
- [MMRotate](https://github.com/open-mmlab/mmrotate): OpenMMLab rotated object detection toolbox and benchmark.
- [MMYOLO](https://github.com/open-mmlab/mmyolo): OpenMMLab YOLO series toolbox and benchmark.
- [MMSegmentation](https://github.com/open-mmlab/mmsegmentation): OpenMMLab semantic segmentation toolbox and benchmark.
- [MMOCR](https://github.com/open-mmlab/mmocr): OpenMMLab text detection, recognition, and understanding toolbox.
- [MMPose](https://github.com/open-mmlab/mmpose): OpenMMLab pose estimation toolbox and benchmark.
- [MMHuman3D](https://github.com/open-mmlab/mmhuman3d): OpenMMLab 3D human parametric model toolbox and benchmark.
- [MMSelfSup](https://github.com/open-mmlab/mmselfsup): OpenMMLab self-supervised learning toolbox and benchmark.
- [MMRazor](https://github.com/open-mmlab/mmrazor): OpenMMLab model compression toolbox and benchmark.
- [MMFewShot](https://github.com/open-mmlab/mmfewshot): OpenMMLab fewshot learning toolbox and benchmark.
- [MMAction2](https://github.com/open-mmlab/mmaction2): OpenMMLab's next-generation action understanding toolbox and benchmark.
- [MMTracking](https://github.com/open-mmlab/mmtracking): OpenMMLab video perception toolbox and benchmark.
- [MMFlow](https://github.com/open-mmlab/mmflow): OpenMMLab optical flow toolbox and benchmark.
- [MMEditing](https://github.com/open-mmlab/mmediting): OpenMMLab image and video editing toolbox.
- [MMGeneration](https://github.com/open-mmlab/mmgeneration): OpenMMLab image and video generative models toolbox.
- [MMDeploy](https://github.com/open-mmlab/mmdeploy): OpenMMLab model deployment framework.


# 2. 图像转手绘
## 2.1. Image-Freehand
- 地址：<https://github.com/tmliang/Image-Freehand>\
- 描述：对于不同的图片可以通过修改深度值depth，光照的俯视角el和方位角az以获得最好的效果\
- 评价：仅20多行代码，纯图像处理算法，使用PIL, numpy库，简洁方便，效果不错\
![image](https://github.com/fense8000/AIDemo/assets/7136821/a1a8798a-57f2-40fc-b08d-07681519b914)



# 3. 人脸检测相关
## 3.1. 换脸



# 4.对象检测
## 4.1. Darknet
- 地址：<https://github.com/AlexeyAB/darknet>
- 描述：支持YOLOv3,对象检测
- 评价：使用简单，可在检测后，发送UDP消息

## 4.2. YOLOv8
- 地址：<https://docs.ultralytics.com/>  <https://github.com/ultralytics/ultralytics>
- 描述：支持对象检测、姿态检测、目标分割、分类、跟踪等功能
- 评价：性能与检测准确度都有所提高，使用ultralytics的代码编译改写即可
  
# 5. 标记工具
- Yolo_mark in C++: <https://github.com/AlexeyAB/Yolo_mark>  
- labelImg in Python: <https://github.com/tzutalin/labelImg>  
- OpenLabeling in Python: <https://github.com/Cartucho/OpenLabeling>  
- darkmark in C++: <https://www.ccoderun.ca/darkmark/>  
- cvat in JavaScript: <https://github.com/opencv/cvat>  
- deeplabel in C++: <https://github.com/jveitchmichaelis/deeplabel>  
- BMW-Labeltool-Lite in C#: <https://github.com/BMW-InnovationLab/BMW-Labeltool-Lite>  
- DL-Annotator for Windows ($30): url <https://www.microsoft.com/en-us/p/dlannotator/9nsx79m7t8fn?activetab=pivot:overviewtab>
- v7labs - the greatest cloud labeling tool ($1.5 per hour): <https://www.v7labs.com/>  
- labelbee <https://github.com/open-mmlab/labelbee>
- BILS(视频标注工具) <https://github.com/PaddlePaddle/PaddleVideo/blob/develop/docs/zh-CN/annotation_tools.md>
- 
# 6. 姿态检测
## 6.1 OpenPose
- 地址：<https://github.com/CMU-Perceptual-Computing-Lab/openpose>
- 描述：卡内基梅隆大学的openpose 可以检测人体姿态、body,foot,face and hands
- 评价：不错的开源项目，近两年为更新较少
![image](https://github.com/fense8000/FenceNotes/assets/7136821/be7e15c5-cf63-4046-9801-2394cc8f2000)







