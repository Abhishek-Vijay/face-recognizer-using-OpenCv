# face-recognizer-using-OpenCv
This program has 3 main phases as : 
1. Creation of dataset/testdata for the recognizer
2. Creation of trainer set which generates .yml file for trainer data
3. Main recognizer which uses LBPH- local binary point histogram function. 


# Libraries used:
1. OpenCV
2. numpy mkl
3. pillow

# Running procedure:
1. create 2 empty folders namely - dataset and trainer - in the same directory in which you have the code files 
2. run face_dataset.py file
3. check if the dataset folder have some data or not.
4. run face_training.py file 
5. check trainer folder should have .yml file 
6. now run the face_recognition.py
7. for more accurate results create more test data as well as trainer data.
