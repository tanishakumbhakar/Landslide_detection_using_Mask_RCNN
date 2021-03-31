# Landslide_detection_using_Mask_RCNN
Freely available landslide photographs are collected from distinct sources to create the training dataset. Transfer learning is used for achieving good results with finite training samples. Object detection task is performed on landslide photographs for achieving landslide detection with minimal dataset using a Mask R-CNN model pre-trained on COCO weights. ResNet 101 backbone is used.

# WORK PLAN
❏ Set runtime type to GPU in Google Colaboratory for training and testing the
model<br>
❏ Installation of compatible versions of keras, python, Tensorflow, required
libraries and packages<br>
❏ Dataset Preparation<br>
5-fold cross validation approach is used. So 1 set is the validation set while the rest 4 sets together comprise the training dataset. This process is repeated for 5 times by randomly shuffling the images in the dataset.<br>
❏ Data Annotation – Labelling of images<br>
Labelling of images is done by VCG Image annotator and the json file is present in the datasets folder.<br>
❏ Image Augmentation<br>
imgaug library is used for image augmentation.<br>
❏ Configure model for training<br>
❏ Configure model for testing<br>
❏ Test the accuracy of the model<br>
❏ Repeat if not satisfying after tuning hyperparameters<br>

# Results
Precision: 1 <br>
Recall: 0.73 <br>
F1 Score: 0.85

