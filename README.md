# yolov8Detection
 A simple object detection using the Yolov8 image processing algorithm

# 1 )First, with the help of the command prompt, we go to the folder containing the content of the zip file. (you can forward your address with the cd command)
# 2 )Afterwards, we set up our own Python environment using the following command => ( conda create -n *environment_name* python=* the python version you are using*
# 3 )After this process, the Python environment we will use is established.
# 4 )conda activate *environment_name*  =>  We can enter the Python environment we have established using the code.
# 5 )Then, I use the following command to install the ultralytics library required to use the YOLOV8 algorithm. => ( pip install ultralytics)
# 6 )Then, using the following command, we load the libraries in the txt file inside the zip file into our environment. => (pip install -r 0_demo/requirements.txt)
# 7 )Finally, we run our detection.py script using the following command => (python detection.py --source data/images/road.png)
# 8 )There may be different options in the source section here. For example, the command (--source 0) opens our webcam and performs object recognition.
