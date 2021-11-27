# Social-distance-detection
**Abstract:**
The paper presents a methodology for social distancing detection using deep learning to evaluate the distance between people to mitigate the impact of this coronavirus pandemic. The detection tool was developed to alert people to maintain a safe distance with each other by evaluating a video feed. The video frame from the camera was used as input, and the open-source object detection pre-trained model based on the YOLOv3 algorithm was employed for pedestrian detection. Later, the video frame was transformed into top-down view for distance measurement from the 2D plane. The distance between people can be estimated and any noncompliant pair of people in the display will be indicated with a red frame and red line. The proposed method was validated on a pre-recorded video of pedestrians walking on the street. The result shows that the proposed method is able to determine the social distancing measures between multiple people in the video. The developed technique can be further developed as a detection tool in realtime application.
## To run this code in your terminal:
* ***Open your terminal**
* ***Change directory to where you have downloaded this code***
* ***Install python3 if you have not, if installed already then it's ok!***
* **Run**  `  python3 -m venv venv  ` ***to create a virtual environment named venv.***
* **Run**   `  source venv/bin/activate  ` 
***to activate your environment!***
* **Write**   `  pip install -r requirements.txt  ` 
***to install the python dependencies related to this project like opencv,numpy,scipy etc.***
* **Run the command** `time python social_distance_detector.py --input pedestrians.mp4 --output output.avi --display 1
` ***to run your social distance detection project***
***For yolov3.weigths file***
https://pjreddie.com/darknet/yolo/

-> run commands on terminal
->then copy yolov3.weights files
->copy in **yolo-coco** files name
->then run on above commands

#### After you run the last line of command,a window eill pop up and after execution of the file a `output.avi` file will be showing up in your directory like this:
![Output avi gif](https://github.com/abd-shoumik/Social-distance-detection/blob/master/social%20distance%20detection.gif)


## Contacts:
* **Created by:[Prabhat Kumar Tiwari](https://github.com/Prabhatap20)**
* **Email:[prabhatap20@gmail.com](https://prabhatap@gmail.com)**
* **Youtube:[Techblogg](https://www.youtube.com/channel/UCFtcOBIMoHlg_Opo2t_jTsA)**
* **LinkedIn:[Prabhatap20](https://www.linkedin.com/in/prabhatap20)**
