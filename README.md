# data
This dataset focuses on the detection of defects in transmission line components, specifically insulators and vibration dampers.
It covers four defect categories commonly found in real-world inspections:

Insulator

Insulator Breakage

Insulator Disc Detachment

Vibration Damper Corrosion

The dataset is designed to support research in defect detection under complex backgrounds and challenging conditions.
dataset/
├── images/
│   ├── train/    # 1505 images
│   └── val/      # 428 images
├── labels/
│   ├── train/
│   └── val/
images/: Original images for training and validation.

labels/: Corresponding annotations in VOC format (.xml files).
