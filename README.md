# T-FasterRCNN (Transfer Learning)
# Realtime traffic sign detection in low visibility
## Using Resnet-50 architecutre

### Introduction

Traffic sign detection is a hotspot of research and development by the onset of semi-automatic and fully automatic cars in the market. However, the low visibility scenarios due to bad weather, reflections, and night time can cause a system failure in these cars. Improving traffic sign detection system vision in real-time can reduce accidents and also regulates drivers to follow traffic rules.

Below are the implementation of various experiments and results comparions to give answers to following research questions:

 - Can transfer learning when applied to real-time traffic sign classification accelerate the prediction of FasterRCNN and RCNN?
 - Can transfer learned FasterRCNN achieve improved performance in terms of accuracy and F1 score for real-time traffic sign classifications?
 - Can image/traffic sign blurriness affect the performance of transfer learned FasterRCNN for real-time traffic sign classification?



### Files

- traffic_signs.ipynb: Jupyter notebook having code to detect the signs
- coco_eval.py: pretrained model evaluator
- coco_utils.py: pretrained model filtering and mappings
- engine.py: train epoch for pretrained model
- utilss.py: metric logger for pretrained model
- plots: directory containing all the exported plots in svg format
- datasets: directory containing all the images and files for GTSRB and GTDSB datasets.

### Datasets
- [GTSRB](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/download)
- [GTSDB](https://www.kaggle.com/safabouguezzi/german-traffic-sign-detection-benchmark-gtsdb/download)
