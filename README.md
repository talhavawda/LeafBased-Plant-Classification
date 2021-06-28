# LeafBased-Plant-Classification
 Leaf-Based Plant Classification

Project Repository Link: https://github.com/talhavawda/LeafBased-Plant-Classification

Download Leafsnap dataset: http://leafsnap.com/static/dataset/leafsnap-dataset.tar

Note that the dataset has been added to .gitignore and is thus not present in this hosted repository.

Dependencies: 

1. Python 3.8

2. The following Python libraries need to be installed:
    1. pandas
    2. numpy
    3. OpenCV (cv2)
    4. mahotas
    5. scikit-learn (sklearn)

<br>

Execution instructions:
1. Download the Leafsnap dataset at the above link
2. Extract the leafsnap-dataset.tar file using a tool such as 7-Zip
3. Place the 'leafsnap-dataset' folder that was extracted in the 'data' folder in the repository
    4. Verify that the 'leafsnap-dataset' folder has two files ('leafsnap-dataset-readme.txt' and 'leafsnap-dataset-images.txt') and one folder ('dataset')
5. There is a file called 'leafsnap-dataset-images.csv' in the root folder of the repository. Take this file and move it into the data/leafsnap-dataset folder
6. To run the program, you can either open the project in an IDE (preferably PyCharm) and run it in the IDE or run the program from the Command Prompt
    7. To run the program from the Command Prompt (in Windows):
        8. Navigate to this project folder location on your pc using the 'cd' command
        9. Type in the following command into the Command Prompt: 'python Main.py' (without the inverted commas)
       