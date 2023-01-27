# StreetAware Dataset

## Location: vidagpu.poly.edu:/vida/work/street_aware/synchronized/


### Folder structure:

#### chase_1
#### chase_2
#### chase_3
##### meta				- Metadata used during processing of raw data
│   │   ├── camera_orders.json	- Left/Right camera associations for raw data
│   │   └── video_qualities.json	- Video quality settings used for rendring
│   ├── sensor_1
│   │   ├── array.json
│   │   ├── array.png
│   │   ├── array.wav
│   │   ├── left_half.mp4
│   │   ├── left.json
│   │   ├── left.mp4
│   │   ├── left_poses.json
│   │   ├── left_quarter.mp4
│   │   ├── right_half.mp4
│   │   ├── right.json
│   │   ├── right.mp4
│   │   ├── right_poses.json
│   │   └── right_quarter.mp4
│   ├── sensor_2
│   ├── sensor_3
│   ├── sensor_4
│   ├── mosaic
│   │   ├── 0.jpg
│   │   .
│   │   ├── 20.jpg
│   │   ├── 1000.jpg
│   │   .
│   │   ├── 1020.jpg
│   │   ├── 2000.jpg
│   │   .
│   │   └── <n>.jpg
│   ├── mosaic.mp4
│   ├── audio.png
│   ├── street_1.wav
│   ├── street_2.wav
│   ├── street_3.wav
│   ├── street_4.wav
│   └── lidar.zip
├── chase_map.pdf
├── dumbo_1
├── dumbo_2
├── dumbo_3
├── dumbo_4
├── dumbo_map.pdf
├── park_1
├── park_2
├── park_3
├── park_4
├── park_map.pdf
├── reip_sensor.jpg
└── ReadMe.md
```

Code repository: https://github.com/reip-project/street-aware.git

Attention! Known issues/limitations:

1) Lidar data is not synchronized with audio and video data;
2) Park_4 recording session has lots of mising data because of copying error;
3) Dumbo_4 session experienced lots of lost frames because of sensor overheating.
