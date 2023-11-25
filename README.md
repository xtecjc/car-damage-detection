# car-damage-detection
This is a reposity for the AI701 project by Group 28. Group members are Vahan Martirosyan, Daniel Gebre, Siem Hadish

The finetune_sam.ipynb notebook was used to finetune the facebook/sam-vit-huge pretrained model using the CarDD dataset.
The finetune_yolov8.ipynb notebook was used to finetune the Yolov8x architecture by Ultralytics using using the CarDD dataset.
The test-and-inference-pipeline.ipynb notebook was used to test our method on individual images as well as the entire testing dataset.

The notebooks were run in a Google Colab. The NVIDIA Tesla A100 GPU with 40GB RAM was used for the finetune_sam.ipynb notebook, whereas the
NVIDIA Tesla V100 GPU with 16GB RAM sufficed for finetune-yolov8.ipynb and test-and-inference-pipeline.ipynb.

All dependencies are installed within the notebooks with command line commands.

The following Google Drive directory contains all training and testing data, as well as the weights for the finetuned yolov8x architecture:
https://drive.google.com/drive/folders/1R5B086gLhqNxbjKVO71cgtmIJkS-oIZq?usp=sharing

Our finetuned SAM architecture can be found in the following link: 
https://huggingface.co/yjmsvma/car_sam

