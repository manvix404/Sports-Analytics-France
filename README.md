## CenterTrack
Download the weights from [Model zoo](https://drive.google.com/drive/folders/1y_CWlbboW_dfOx6zT9MU4ugLaLc6FEE8) and put them in `CenterTrack/models/` (models folder needs to be created). The coco_tracking.pth model can be used for general purpose.
<br>Reference Github can be found here: [CenterTrack](https://github.com/xingyizhou/CenterTrack).

## TrackNetv1_tennis
This model has been trained specifically for tennis ball tracking and is suitable for tracking and detecting a high speed ball.
Download the weights from [tracknetv1 weights](https://nol.cs.nctu.edu.tw:234/open-source/TrackNet/tree/master/Code_Python3/TrackNet_Three_Frames_Input/weights) and all 3 files to `TrackNetv1_tennis/Code_Python3/TrackNet_Three_Frames_Input/weights`.
The model has already been tested on a sample video taken from youtube and the results can be found in [result video](TrackNet/TrackNetv1_tennis/Code_Python3/result_videos).

## TrackNetv1_player_yolov3
The model uses tracknetv1 to detect and track the ball and uses yolov3 with ResNet50 for tracking the players. The court lines are also detected using OpenCV.
The tracknet weights can be downlaoded from [weights](https://github.com/ArtLabss/tennis-tracking/tree/main/WeightsTracknet) and put in `TrackNetv1_player_yolov3/WeightsTracknet`.
<br>Reference Github can be found here: [TrackNetv1-yolov3](https://github.com/ArtLabss/tennis-tracking/tree/main)

## TrackNetV3
This is the only attention based model while the others are all CNN based. The model has been trained and tested for badminton specifically. 
Download the weights from [weights](https://drive.google.com/file/d/1CfzE87a0f6LhBp0kniSl1-89zaLCZ8cA/view) and put them in `TrackNetV3/ckpts/`
<br>Reference Github can be found here: [TrackNetv3](https://github.com/qaz812345/TrackNetV3)
