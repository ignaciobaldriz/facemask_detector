# facemask_detector

https://user-images.githubusercontent.com/65371348/115462987-ab726500-a201-11eb-9f39-e6a214a11462.mp4




The current repository contains a deep learning project for face detection and face mask usage recognition, created in the context of the Coivd-19 pandemic.


The project is written in Python language, the model was trained with Keras-Tensorflow inside Google Colab, the video display was executed with OpenCV locally on a Ubuntu machine.




The documents contained are:

- "dataset": A folder with the images for training the model, "with_mask" and "without_mask". Please unzip the images and save it in Google Colab before running the model generator file.

- "requirements.txt": A text file with the libraries and versions requirements. Run this file inside your virtual environment before importing any librarie.

- "facemask_detector.ipynb": A GoogleColab Notebook written in Python to import the dataset, train the model and save it as a HDF5 file. Please run this file inside the same Google Colab folder of the dataset.

- "mask_recognizer.h5": A HDF5 file with the model binarized. Please store this file locally in the PC that you are going to display the camera.

- "face_detector": A folder with two files necessaries to run the final Python file with the camera recognition. Please store this file locally in the PC that you are going to display the camera.

- "detect_mask_video.py": A Python file where you open the mask_recognizer.h5 model, the face_detector folder and you run locally the camera for the final face detection and facemask recognition. Please store this file locally in the PC that you are going to display the camera.

- "face_mask_video.mp4": An illustrative video of myself with the final result.





DOCUMENTATION AND REFERENCES:

- https://www.mygreatlearning.com/blog/real-time-face-detection/
- https://colab.research.google.com/drive/1KuI6BjaBsuz8fClweso_c2aNgqmSPezl?usp=sharing
- https://github.com/balajisrinivas/Face-Mask-Detection
- https://www.youtube.com/watch?v=Ax6P93r32KU


