
human_emmotion - v1 2024-03-26 9:01pm
==============================

This dataset was exported via roboflow.com on March 26, 2024 at 3:34 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 9018 images.
Faces are annotated in clip format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random rotation of between -13 and +13 degrees
* Random shear of between -10° to +10° horizontally and -14° to +14° vertically
* Random Gaussian blur of between 0 and 1.1 pixels
* Salt and pepper noise was applied to 0.38 percent of pixels


