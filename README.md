# faceSwapGAN



1. Run MTCNN_video_face_detection_alignment.ipynb  extracts faces from videos.
  Manually move/rename the aligned face images into ./faceA/ or ./faceB/ folders.

2. Run prep_binary_masks.ipynb generates binary masks of training images.

3. Run FaceSwap_GAN_train_test.ipynb  trains models.
4. Run FaceSwap_GAN_v2.2_video_conversion.ipynb creates videos using the trained models in step 3.
