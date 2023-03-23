# reality-animate transformer


### Install packages
- run `pip install -r requirements.txt`


### Generate images from videos
- For the videos that you want to convert to frames, please put them into `data/reality_videos/` and `data/animation_videos`.
- run `python generate_data.py`

````
.
└── data
    ├── reality_images
    │   ├── image1.jpg
    │   ├── image2.jpg
    │   └── ...
    └── animation_images
    │   ├── image1.jpg
    │   ├── image2.jpg
    │   └── ...
    
    
└── reality-transformer main
````
...



### Train
- run `python train.py`
