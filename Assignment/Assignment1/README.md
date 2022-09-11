**AI6126 Advanced Computer Vision** 
**Project 1: CelebAMask Face Parsing**

The code of this project was created and tested on Google Colab
The submitted files include: 
- PDF Report
- test_result.zip: The best results from my model on the 1000 test images in test_result.zip
- CodaLabScore.png: screenshot on CodaLab of score achieved
- iter_30000.pth: the model checkpointsof submitted model
- config.py: config file of the model
- Face_Parsing_v3.ipynb: code for the model build, training and testing
- evaluate.ipynb: code for validation result evaluation
- ReadMe.txt: an instruction of the submitted files


**Base Environment:**
The training and testing process were running on Google Colab
Below are the packages needed: 
  - condacolab
  - PyTorch 1.6.0
  - torchvision
  - cudatoolkit 10.1
  - mmcv
  - mmsegmentation
  - MatPlotLib
  - Numpy
  - PIL

**Files Directory (in Colab):**
- Training Images: /content/drive/MyDrive/Colab Notebooks/AI6126_ACV/Face_Parsing/data/CelebAMaskHQ/train/train_image
- Training Masks: /content/drive/MyDrive/Colab Notebooks/AI6126_ACV/Face_Parsing/data/CelebAMaskHQ/train/train_mask
- Validation Images: /content/drive/MyDrive/Colab Notebooks/AI6126_ACV/Face_Parsing/data/CelebAMaskHQ/val/val_image
- Validation Masks: /content/drive/MyDrive/Colab Notebooks/AI6126_ACV/Face_Parsing/data/CelebAMaskHQ/val/val_mask
- Test Images: /content/drive/MyDrive/Colab Notebooks/AI6126_ACV/Face_Parsing/data/CelebAMaskHQ/test/test_image
- Test Results: /content/drive/MyDrive/Colab Notebooks/AI6126_ACV/Face_Parsing/data/CelebAMaskHQ/test/test_result
- Work_dirs(json log & checkpoint files): /content/drive/MyDrive/Colab Notebooks/AI6126_ACV/Face_Parsing/work_dirs
- config file: /content/drive/MyDrive/Colab Notebooks/AI6126_ACV/Face_Parsing/config.py
- evaluate.py (for val set): /content/drive/MyDrive/Colab Notebooks/evaluate.ipynb
