# TSData
交通信号灯数据集集[WPI Traffic Light Dataset](http://computing.wpi.edu/dataset.html)
### Training Data
* The training data are collected in Worcester, MA, USA during summer.
* ROI Samples: Extracted from frames in Frames_GT_wHolder. Can be used for training classifier. [Download: 77.8 MB](http://computing.wpi.edu/WTLD/Samples.zip)

### Training Data [Optional]
* Training Data [Optional]
* These data are optional and may be helpful. E.g., if one wants to investigate not only the traffic lights, but also the surrounding areas.
* Many, if not all, the frames in Frames_GT_wHolder and Frames_GT_Lights are the same.
Frames_GT_wHolder: Whole frames with label. Each folder is a type of traffic lights with their holders, and only that type is labelled (Ground truth contain the traffic light holders). A frame contains multiple types of traffic lights may appear in different folders. [Download: 10.5 GB]([Download: 10.5 GB])
* Frames_GT_Lights: Whole frames with label. These sequences are labelled for individual traffic lights of all types. Sequences 8,9,10 do not have traffic lights. [Download: 1.52 GB](http://computing.wpi.edu/WTLD/Frames_GT_Lights.zip)
### Test Data
The test data are collected in Worcester, MA, USA during winter.
Test: Whole frames with label. These sequences are labelled for individual traffic lights of all types. Sequences 18,19,20,21,22,23 do not have traffic lights. [Download: 3.06 GB](http://computing.wpi.edu/WTLD/Test.zip)
# data provider's Demo (compared with HOG features without tracking)[video](https://youtu.be/7iqXcMvR3Xg)
