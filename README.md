# LSNet



This repository is a full implementation of LSNet:A Lightweight Segmentation Framework for Real-Time Wildfire Detection, building a new real-time wildfire segmentation framework for wildfire detection.
This repository demonstrates the architecture of the LSNet model and the effectiveness and robustness of the scheme. Our implementation supports both single and multi-GPU training.

EPNet
├── data
│   ├── KITTI
│   │   ├── ImageSets
│   │   ├── object
│   │   │   ├──training
│   │   │      ├──calib & velodyne & label_2 & image_2 & (optional: planes)
│   │   │   ├──testing
│   │   │      ├──calib & velodyne & image_2
├── lib
├── pointnet2_lib
├── tools
