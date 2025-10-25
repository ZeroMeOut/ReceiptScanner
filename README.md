
# Receipt Scanner

Hello, this is a receipt scanner as the name suggest. Specifically it extracts only the the bought items. The thought process is for it to first use an image classification model to check if the input image is even a receipt in the first place, then if it is extract the bought items with a ~~VLM~~ image to text model. 

## Why a Image to text model?
Image to text models can (potentially) understand the structure of a receipt better than typical OCR methods. I also just want to understand how to train them to do that. If it doesn't work this repo would be terminated :)



## Roadmap

- Find and clean a receipe dataset

- Train an image classification model (I would probably use YOLO). I would like to also learn how to connect my system to a gpu instance running on the cloud. So like code on my machine while not using my gpu to train

- Check the performance of the recognition model locally on my system

- Then move on to train a image to text model for the extraction.

- Check the performance, iterate till it's decent. I don't want to try creating the best, I must admit I don't believe I can, but I want it to be very very good

- Create a pipeline. I will be using FastAPI

- Host the piepline. I would think of something if I ever reach here

