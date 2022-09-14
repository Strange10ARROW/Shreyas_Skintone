# Shreyas_Skintone

PROJECT OBJECTIVE - A web portal to detect the skin tone (i.e, Fair,Mild or Dark) from a human face image.

PROJECT DESCRIPTION - The project aims to create a webpage which will take image as an input; Use image processing techniques to process the image as per requirement; To detect whether the skin tone in the image is Fair, Mild or Dark.

Skin detection is the process of finding skin-colored pixels and regions in an image or a video. This process is typically used as a preprocessing step to find regions that potentially have human faces and limbs in images . Skin image recognition is used in a wide range of image processing applications like face recognition, skin disease detection, gesture tracking and human-computer interaction . The primary key for skin recognition from an image is the skin color. But color cannot be the only deciding factor due to the variation in skin tone according to different races. Other factors such as the light conditions also affect the results. Therefore, the skin tone is often combined with other cues like texture and edge features. This is achieved by breaking down the image into individual pixels and classifying them into skin colored and non-skin colored . One simple method is to check if each skin pixel falls into a defined color range or values in some coordinates of a color space. There are many skin color spaces like RGB, HSV, YCbCr, YIQ, YUV, etc. that are used for skin color segmentation.

To run this project:
Step 1: Clone the repository.
git clone https://github.com/ad158h/exploratory-data-analysis.git

Step 2: Navigate to directory
pip install -r requirements.txt

Step 3: Run the file.
py skintone.py

Step 4: Enter File Location.
Hint: The program is configured to work in python3. However opencv works in both python2 and python3. The Program gives the skintone of image as "Fair" , "Mild" or "Dark".
