# TrackMe
## How to use:
To read the video and save the file:

```
 python count_people.py --modelprototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt
	--model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --input pathtoinputvideofile/filename.mp4
	--output pathtooutputvideofile/filename.avi
```

 To read from webcam and save the file:
 
 ```
 python count_people.py --modelprototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt 
 	--model mobilenet_ssd/MobileNetSSD_deploy.caffemodel
	--output pathtooutputvideofile/filename.avi
```
