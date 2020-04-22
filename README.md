# Social-Distancing-Analyser-CONVID-
this repository is containing project for analysing social distancing between peoples with respect to CCTV(upper-level-photage) &amp; also by WEB-IP cameras enabled on cameras or installed on smartphones 

An AI tool to prevent spreading of coronavirus (COVID-19) by using computer vision on video surveillance. A social distancing analyzer AI tool to regulate social distancing protocol using video surveillance of CCTV cameras and drones. Social Distancing Analyser to prevent COVID19

# For education purpose only, [its just  contribution to the  society]
Social Distancing Analyser automatically detects the extent to which social distancing protocols are followed in the area. Deploying it on current surveillance systems and drones used by police to monitor large areas can help to prevent coronavirus by allowing automated and better tracking of activities happening in the area. It shows analytics of the area in real time. It can also be used to alert police in case of considerable violation of social distancing protocols in a particular area.

## Please fork the repository and give credits if you use it for your clearence or practice🙂

# I will be happy and really appreciate you  if you give it a star. ⭐

here i used vwrsion 2.0
## So please Note: angle factor is needed to be set between 0 to 1 for v2.0 according to the angle of camera (move towards one as angle becomes verticle)

## Features:
* Get the areal time nalytics such as:
   - Number of people in a particular area
   - Number of people in high risk
   - The extent of risk to a particular person.
* Doesn't collect any data of a particular person
* Stores a video output for review

## Things needed to be work-on :
* Auto-calibration [For the given sample video, I've calibrated the model by simulating a 3D depth factor based on the camera position and orientation.] (Check out v2.0) but if you really wants to use from my input videos file then i will suggest you to take video-2 & 5 (they are more preferable than others)
* Faster processing

## Installation:
* Fork the repository and download the code.
* Download the following files and place it in the same directory
  - https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg
  - https://pjreddie.com/media/files/yolov3.weights
* For slower CPUs, use yolov3-tiny(preferable)
* Install all the dependenices
* Run social_distancing_analyser.ipynb if you already had a video saved on system 
* Else: Run Web_ip_SocialDistancing .ipynb if you wants to take input as in the form of LIVE-video-stream from web-ip enabled camera or installed on smartphones

### Credits:
#### A big thanks to Ardian Rosebrock (www.pyimagesearch.com) for CV tutorial on detection.
