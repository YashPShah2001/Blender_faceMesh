# WELCOME
Assignment to integrate blender animation with AI based model using python which makes the animation's face to mimic the movements of your face. 

# Prerequisities
1. Blender Version 2.8
2. Animation Character file: https://studio.blender.org/characters/5718a967c379cf04929a4247/v1/
3. AI Model

# Steps implemented
1. Downloaded Blender Version 2.8
2. Then downloaded both the Animation file and the AI model and extracted it.
3. Open the downloaded Animation file and this should open the Vincent Character Animation in Blender.
4. open command prompt as administrator and enter the following 3 commands
  - cd C:\Program Files\Blender Foundation\Blender 2.82\2.82\python\bin
  - python -m pip install --upgrade pip
  - python -m pip install opencv-contrib-python numpy
5. Then opened Animation file on Blender and click on the Scipting tab which will open you a code editor.
6. Here go to Text->New to create a new empty file 
7. Copy the contents of OpenCVAnim.py to the blender code editor and rename the file name in code editor to the original filename(OpenCVAnim.py). Save this and click on Run Script
8. Again create a new file in code editor and this time copy the contents of OpenCVAnimOperator.py file and change the filename as OpenCVAnimOperator.py in code editor.
9. Before Saving this and running, don't forget to change the AI model file path which can be changed in the landmark_model_path variable as given in line 40
10. The AI model is a file named lbfmodel.yaml. You need to paste the path of this file in landmark_model_path variable.
11. Then save, tick the Register option and Run Script. After this, click on layout tap which will zoom in the Animation.
12. Here you can see an option in left hand side called OpenCV Animation. Click on it you will see capture option on the right
13. Click on capture which will turn on your video camera.
14. Congragulations!, Now move your face once the face mesh comes which will make the Vincent Animation automatically mimic your face.

AR VR assignment-1
