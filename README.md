# Waffles & Ice Cream Detector
We all enjoy waffles or ice cream unless you are lactose-intolerant. This basic web app is able to detect and identify waffles or ice cream in a photo.

[YoloV5](https://github.com/ultralytics/yolov5) was used to train the default model and labelling the images was done using [MakeSense](https://www.makesense.ai/). The  [Waffles or Ice-Cream](https://www.kaggle.com/datasets/sapal6/waffles-or-icecream?select=waffles) dataset was used for training and validation.

<center><a data-flickr-embed="true" href="https://www.flickr.com/photos/194810959@N06/52136789845/in/dateposted-public/" title="Screenshot"><img src="https://live.staticflickr.com/65535/52136789845_967eaa980f_z.jpg" width="529" height="640" alt="Screenshot"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script></center>

## Setup Guide
Few steps to follow before getting started.

1. Download the **YoloV5** github repository
2. Create a directory called `runs` with the following subdirectories `train\weights`
3. Move `best.py`  to the newly created directly (this contains the weights of the trained model)

## Notes
- The model only used 74 images for training and validation. It can be significantly improved for better results
- Training was done using Google Colab using a GPU