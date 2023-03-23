# reality-transformer


### Install packages
- run `pip install -r requirements.txt`


### Generate images from videos
- For the videos that you want to convert to frames, please put them into `data/reality_videos/` and `data/animation_videos`.
- run `python generate_data.py`

mkdir -p data/reality_images
touch data/reality_images/image1.jpg
touch data/reality_images/image2.jpg
...

mkdir -p data/animation_images
touch data/animation_images/image1.jpg
touch data/animation_images/image2.jpg
...



### Train
- run `python train.py`
