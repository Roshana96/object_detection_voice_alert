# object_detection_voice_alert
## Machine Learning Object Detection and Recognition With Voice Alert Application for Visually Impaired People
This is a vision enhancer based module specifically for the Visually Impaired People. The system is designed 
in such a way in which the visually impaired or blind person can take the help of AN APPLICATION which inturn 
sends Real-Time Frames to the LAPTOP-BASED WIRELESS NETWORKED SYSTEM. It works on REAL-TIME OBJECT DETECTION 
using SSD_MOBILENET algorithm and TENSORFLOW APIs . It has a core feature of approximate distance calculation 
and Voice - Based wireless feedack generation w.r.t the DISTANCE CALCULATION. It makes the work of Blind 
easy,efficient and reliable by sending wireless Voice based feedback whether the particular object is either 
too close to him or is it at a safer distance.


## Features
* Easy to integrate
* Voice Activated
* Real Time Interface
* Can be Interacted with Android Mobile Webcam as well 

## Setup

1) Download TensorFlow and TensorFlow GPU 
## For CPU
    pip install tensorflow
## For GPU
    pip install tensorflow-gpu

2) Next, Download Protobuf version 3.4 or above (https://github.com/protocolbuffers/protobuf/releases)

3) Download TensorFlow’s Model from Github. (https://github.com/tensorflow/models) [TensorFlow_API]
Once downloaded and extracted rename the "models-masters" to just "models".

4)  "models" and "protobuf" files keep in one folder (ODRVA_application)

5)  Create enviroment variable path (ODRVA\PROTOBUF\bin)

6) Run protobuf from there using this command: 
*  protoc object_detection/protos/*.proto --python_out=.

*  To check whether this worked or not, go to the protos folder inside models>object_detection>protos and there you can see 
that for every proto file there’s one python file created.

7) Download the project source code. Unzip ODRVA_application file.
Copy webcam_blind_voice.py python file and save under ODRVA\models\research\object_detection directory.

8) Run [MainFile](ODRVA\models\research\object_detection\webcam_blind_voice.py)

Thank you !


#### [author]: Roshana Atapattu 
#### [e-mail]: (roshana96.atapattu@gmail.com)
