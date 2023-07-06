# Project_Saravanastore
Detect humans from live streaming video and send an alert to telegram when humans are detected in live streaming.

## Inference
`python fraction_detect.py --weight best.py --source 0 `

`--weights` - custom model for detecting humans from live stream videos


`--source`  - choose 0 (zero) for webcam 

## Added features

#### Write logs in Result.txt 
#### Convert Result.txt into Result.json
#### Send an alert message to telegram using a custom bot 
