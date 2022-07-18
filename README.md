# Conan Character Classification

In this project, I try to use yolov5 to classify 5 characters from Detective Conan The Movie 21 “The Crimson Love Letter”.
The characters that I used are Edogawa Conan, Hattori Heiji, Mouri Ran, Mouri Kogoro, Toyama Kazuha.

For the dataset, I captured face's images from the video file and used them as base images.
Then I used roboflow to label their faces and create dataset.
The images were augmented 4 times to increase the dataset, so we get 4 times more for the dataset.
After this, I used yolov5 to classify those characters on google colab.

You can see the results on: https://wandb.ai/beater27/YOLOv5/runs/br0l6pau?workspace=user-beater27
