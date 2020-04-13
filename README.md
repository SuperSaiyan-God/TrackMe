# TrackMe
<hr>
## How to use:
<br><br>
 To read the video and save the file:
 <br>
 `python count_people.py --modelprototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt
	--model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --input pathtoinputvideofile/filename.mp4
	--output pathtooutputvideofile/filename.avi`
<br><br>
 To read from webcam and save the file:
 <br>
 `python count_people.py --modelprototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt 
 	--model mobilenet_ssd/MobileNetSSD_deploy.caffemodel
	--output pathtooutputvideofile/filename.avi`
