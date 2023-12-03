# Development-of-a-Telegraph-Robot-for-Target-Detection-Based-on-aiogram-and-FastAPI-Framework



The goal of this project is to provide hands-on experience image processing and object detection and integrate it into a real-world application, a robot that can acquire images via Telegram and return object detection results. Using the publicly available ultralyticsplus/yolov8s model from Hugging Face [1] for development, a Telegram-based robot for object detection in images based on the aiogram framework and FastAPI. 

[1] https://huggingface.co/ultralyticsplus/yolov8s 

Supported Labels:

['person', 'bicycle', 'car', 'motorcycle', 'airplane', 'bus', 'train', 'truck', 'boat', 'traffic light', 'fire hydrant', 'stop sign', 'parking meter', 'bench', 'bird', 'cat', 'dog', 'horse', 'sheep', 'cow', 'elephant', 'bear', 'zebra', 'giraffe', 'backpack', 'umbrella', 'handbag', 'tie', 'suitcase', 'frisbee', 'skis', 'snowboard', 'sports ball', 'kite', 'baseball bat', 'baseball glove', 'skateboard', 'surfboard', 'tennis racket', 'bottle', 'wine glass', 'cup', 'fork', 'knife', 'spoon', 'bowl', 'banana', 'apple', 'sandwich', 'orange', 'broccoli', 'carrot', 'hot dog', 'pizza', 'donut', 'cake', 'chair', 'couch', 'potted plant', 'bed', 'dining table', 'toilet', 'tv', 'laptop', 'mouse', 'remote', 'keyboard', 'cell phone', 'microwave', 'oven', 'toaster', 'sink', 'refrigerator', 'book', 'clock', 'vase', 'scissors', 'teddy bear', 'hair drier', 'toothbrush']

# How to use

1. Requirements: Google Colab

Install ultralyticsplus:

pip install -U ultralyticsplus==0.0.14

pip install aiogram

pip install fastapi

pip install uvicorn

!pip install python-telegram-bot==13.13

2. telegram

Preparation: Make sure you have a Telegram account, then Create a new bot in Telegram using BotFather to get a bot token.

![image](https://github.com/2461011611/Development-of-a-Telegraph-Robot-for-Target-Detection-Based-on-aiogram-and-FastAPI-Framework/assets/118686100/41d0ad93-330f-448b-ac14-01e81be135b0)

Upon successful creation you will receive a token to access the HTTP API.

![image](https://github.com/2461011611/Development-of-a-Telegraph-Robot-for-Target-Detection-Based-on-aiogram-and-FastAPI-Framework/assets/118686100/bfb5d2f2-7efc-4954-b174-1b87f44d7e77)


3. Results

![image](https://github.com/2461011611/Development-of-a-Telegraph-Robot-for-Target-Detection-Based-on-aiogram-and-FastAPI-Framework/assets/118686100/424614fb-3a7a-4413-bb54-062a1d1f1295)



