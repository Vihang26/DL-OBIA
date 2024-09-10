# OBIA
<img width="1123" alt="image" src="https://github.com/user-attachments/assets/3401958b-8ece-47bd-8e95-fba8568b47d1">


Traditionally, object-based image analysis (OBIA) has concentrated on pixel-level loss computation,
which can be problematic close to object edges or in dimly illuminated areas, potentially resulting
in inaccuracies. The purpose of this study is to determine whether object-level loss calculation in
OBIA can improve image analysis's accuracy and efficiency. The study uses the Land Cover
Challenge dataset as a baseline and uses deep learning methods for pixel-based segmentation,
including DeepLabV3+ and U-Net++. To achieve object-level semantic segmentation, a unique
method combines pretrained DetCon weights and a ResNet50 encoder with DeepLabV3+. The
findings show that the new strategy performs better than baseline techniques, especially when it
comes to mean Intersection-over-Union (IoU). The improved mIoU point to the possibility of
further improvements through improved model parameters and improved DetCon pretraining on
remote sensing tasks. This study opens the door for improvements in remote sensing and natural
resource management by highlighting the potential of using deep learning techniques into OBIA for
more reliable land cover classification.

- [PDF Report](RS_Final%20Report.pdf)
- [PowerPoint Presentation](DL-OBIA%20_%20Merging%20Deep%20Learning%20with%20Object-based%20Image%20Analysis.pptx)
