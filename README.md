# ship_detection_sar

# Introduction
This repository is the detection of ships in SAR (Synthetic Aperture Radar) data using the state-of-the-art object detection model YOLOv8.

# Dataset
The dataset contains 5604 SAR images.

![P0001_1200_2000_8400_9200_jpg rf 78df63eb91d2825747cba055b6de60f6](https://github.com/nithinreddy003/ship_detection_sar/assets/104730933/ca00a26b-ca3b-475b-9205-b0b41050fbc1)


![P0002_0_800_8400_9200_jpg rf 2e9d43c0d0019d26b351d7cce8af986e](https://github.com/nithinreddy003/ship_detection_sar/assets/104730933/6bf501f2-b852-4586-ba0e-392964b0342f)


# Model
I have used one stage object detection model YOLOv8 architecture to detect the ships in SAR data.

# Results
| Metric  | Score |
| ------------- | ------------- |
| mAP 50  | 92.7  |
| mAP 50-95  | 69.0  |
| Precision  | 91.2  |
| Recall  | 84.8  |

![results](https://github.com/nithinreddy003/ship_detection_sar/assets/104730933/0e9afefc-dfa1-463d-bb52-349aaec472d4)
![confusion_matrix](https://github.com/nithinreddy003/ship_detection_sar/assets/104730933/3ab2c9a6-6a60-4c9e-861f-5fb7885f0291)


# Test Case Images
![val_batch2_pred](https://github.com/nithinreddy003/ship_detection_sar/assets/104730933/462030e5-0928-46b0-afed-33e4cd9a4b82)
![val_batch2_labels](https://github.com/nithinreddy003/ship_detection_sar/assets/104730933/0364b688-9eaf-4907-b925-7564650621ec)



Link:  https://colab.research.google.com/drive/1zrRBSLZ8TIjZ2CuVyXMzg2iOTky_PApW?usp=sharing
