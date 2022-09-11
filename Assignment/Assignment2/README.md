**AI6126 Advanced Computer Vision** 
**Project 2: Blind Face Super-Resolution**

**The submitted files include:** 
-PDF Report
-result
   -test_result_ESRGAN.zip: The best results on the test image with the ESRGAN model
   -test_result_SRGAN.zip: The best results on the test image with the SRGAN model
   -real_world_test_result.zip: the best result for real-word_test_image
-CodaLabScore.png: screenshot on CodaLab of score achieved
-checkpoint
   -srgan: srgan best model
   -esrgan: esrgan best model
   -esrgan_discriminator: the esrgan with discriminator model for real-world image processing 
			  (Google Drive: https://drive.google.com/file/d/1W8AhFoAIqehWfbWY3ZQFYacZtzg4j0LE/view?usp=sharing)
-config
   -srresnet_ffhq_300k.py: SRGAN config
   -esrgan_config.py: ESRGAN config
   -esrgan2_config.py: ESRGAN with discriminator config
-Project2_v2.ipynb: code for the model build, training and testing
-ReadMe.txt: an instruction of the submitted files

**Base Environment:**
- The training and testing process were running on Google Colab
  Below are the packages needed: 
  - condacolab
  - PyTorch 1.6.0
  - torchvision
  - cudatoolkit 10.1
  - mmcv
  - mmediting
  - openmim
