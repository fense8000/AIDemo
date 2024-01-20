FenceNotes
记录个人学习过程中的一些信息

# 1.综合类
## 1.1. Paddle(百度飞桨)
### 1.1.1 PaddleGAN
- 地址：<https://github.com/PaddlePaddle/PaddleGAN/tree/develop>
- 帮助：<https://github.com/PaddlePaddle/PaddleGAN/blob/develop/README_cn.md>
- 描述：飞桨生成对抗网络开发套件--PaddleGAN，为开发者提供经典及前沿的生成对抗网络高性能实现，并支撑开发者快速构建、训练及部署生成对抗网络，以供学术、娱乐及产业应用。
  ![image](https://github.com/fense8000/FenceNotes/assets/7136821/e595654f-82b3-4e6a-9a91-7652fe9716d9)
![image](https://github.com/fense8000/FenceNotes/assets/7136821/dc2a1b4d-9055-4599-82d9-526ad9e13eb1)
![image](https://github.com/fense8000/FenceNotes/assets/7136821/c6aaabdd-db6c-4953-9d1c-b28abad2274d)

#### 1.1.1.1 LapStyle (图片转不通风格)
- 地址：<https://github.com/PaddlePaddle/PaddleGAN/blob/develop/docs/en_US/tutorials/lap_style.md>
- 描述：PaddleGAN下的样例代码，可以生成不通风格照片
- 评价：使用简单，官方提供四个风格的预训练模型，效果好
![image](https://github.com/fense8000/FenceNotes/assets/7136821/85de9d66-4832-41b5-aa30-1fd9cca17e3b)

#### 1.1.1.2 StyleGAN V2 Editing 模块
![image](https://github.com/fense8000/FenceNotes/assets/7136821/6a44f7c0-594e-4513-8422-eec2334e208f)

#### 1.1.1.3 视频超分SOTA算法PP-MSVSR：一行命令从"马赛克"到"高清影像"
![image](https://github.com/fense8000/FenceNotes/assets/7136821/7410dd06-588c-4444-8436-a28112206534)

#### 1.1.1.4 人脸编辑神器：StyleGAN V2人脸属性编辑之性别转换
![image](https://github.com/fense8000/FenceNotes/assets/7136821/7c8cd64d-3f3b-45ba-8657-217a9d417808)

#### 1.1.1.5 增人脸融合能力，结合新版Frirst Order Motion
![image](https://github.com/fense8000/FenceNotes/assets/7136821/e8357e02-d9f4-4c69-b679-c2b2b4c0dc28)


### 1.1.2 PaddleDetect
- 地址：<https://github.com/PaddlePaddle/PaddleDetection>
- 描述：PaddleDetection是一个基于PaddlePaddle的目标检测端到端开发套件，在提供丰富的模型组件和测试基准的同时，注重端到端的产业落地应用，通过打造产业级特色模型|工具、建设产业应用范例等手段，帮助开发者实现数据准备、模型选型、模型训练、模型部署的全流程打通，快速进行落地应用。
![image](https://github.com/fense8000/FenceNotes/assets/7136821/6b07eef0-e39f-4a7f-9f56-bf3faa1afcb6)

### 1.1.3 [PaddleYOLO](https://github.com/PaddlePaddle/PaddleYOLO)
- 地址：<https://github.com/PaddlePaddle/PaddleYOLO>
- 描述：PaddleYOLO是基于PaddleDetection的YOLO系列模型库，只包含YOLO系列模型的相关代码，支持YOLOv3、PP-YOLO、PP-YOLOv2、PP-YOLOE、PP-YOLOE+、RT-DETR、YOLOX、YOLOv5、YOLOv6、YOLOv7、YOLOv8、YOLOv5u、YOLOv7u、YOLOv6Lite、RTMDet等模型，COCO数据集模型库请参照 ModelZoo 和 configs。

### 1.1.4 模型库
- [官方模型(official)](https://github.com/PaddlePaddle/models/blob/release/2.4/docs/official/README.md)
• 面向产业实践，数量超过600个  
• 飞桨PP系列模型，效果与精度最佳平衡  
• 支持使用动态图开发视觉、自然语言、语音和推荐等领域模型  
• 飞桨官方实现并提供持续技术支持及答疑  
• 与飞桨核心框架版本对齐，已经经过充分的测试保证  
= [学术模型(research)](https://github.com/PaddlePaddle/models/blob/release/2.4/docs/research/README.md)
• 面向学术前沿，侧重对于问题的持续更新  
• 主要由飞桨相关的学术生态合作伙伴贡献  
= [社区模型(community)](https://github.com/PaddlePaddle/models/blob/release/2.4/docs/community/README.md)	
• 面向更多丰富场景，侧重对于学术论文的覆盖  
• 主要由飞桨生态开发者贡献，持续更新中

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

## 1.3. mediapipe(Google)
- 地址：https://github.com/google/mediapipe
- 描述：MediaPipe Solutions provides a suite of libraries and tools for you to quickly apply artificial intelligence (AI) and machine learning (ML) techniques in your applications. You can plug these solutions into your applications immediately, customize them to your needs, and use them across multiple development platforms.
- 评价：支持对象检测、图像分类、图像分割、手势检测、姿态检测、手部关节点检测、脸部关节点检测等，对于关节点检测通过测试效果很好。
![image](https://github.com/fense8000/FenceNotes/assets/7136821/5adeaceb-17f4-43b7-9584-2d5c9fa531ed)
![image](https://github.com/fense8000/FenceNotes/assets/7136821/1bfffa0d-9ddf-41ab-85c7-5dbafa787fdc)!
[image](https://github.com/fense8000/FenceNotes/assets/7136821/60f998cd-3fb4-4f8b-b9c0-46b26354b41d)# 


# 2. 图像转手绘
## 2.1. Image-Freehand
- 地址：<https://github.com/tmliang/Image-Freehand>\
- 描述：对于不同的图片可以通过修改深度值depth，光照的俯视角el和方位角az以获得最好的效果\
- 评价：仅20多行代码，纯图像处理算法，使用PIL, numpy库，简洁方便，效果不错\
![image](https://github.com/fense8000/AIDemo/assets/7136821/a1a8798a-57f2-40fc-b08d-07681519b914)



# 3. 人脸检测与识别
## 3.1. 人脸检测
### 3.1.1 InsightFace: 2D and 3D Face Analysis Project
- 地址：<https://github.com/deepinsight/insightface>
![image](https://github.com/fense8000/FenceNotes/assets/7136821/43513d7e-030f-4bda-9cbb-8409f74c0006)

## 3.2. 换脸

### 3.2.1 DeepFaceLive
- 地址：<https://github.com/iperov/deepfacelive>
- 描述：You can swap your face from a webcam or the face in the video using trained face models.Here is a list of available ready-to-use public face models.These persons do not exists. Similarities with real people are accidental. Except Keanu Reeves. He exists, and he's breathtaking!
![image](https://github.com/fense8000/FenceNotes/assets/7136821/f75ac2e8-2f27-4219-8bc7-edd0ce892861)

### 3.2.2 DeepFaceLab
- 地址：<https://github.com/iperov/DeepFaceLab>
- 描述：
  ![image](https://github.com/fense8000/FenceNotes/assets/7136821/ab397d34-80df-47b1-96e6-c22fe719cab2)

### 3.2.3 SimSwap
- 地址：<https://github.com/neuralchen/SimSwap>
- 描述：SimSwap: An Efficient Framework For High Fidelity Face Swapping

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







