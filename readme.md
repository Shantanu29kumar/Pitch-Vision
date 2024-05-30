# Pitch Vision

## Introduction

The aim of this project is to develop a system capable of detecting and tracking players, referees, and the football in a video using YOLO, a top-tier AI object detection model. Beyond detection, we enhance the model's performance through further training. We categorize players into teams based on the colors of their t-shirts using KMeans for pixel segmentation and clustering. This categorization allows us to determine each team's ball possession percentage throughout the match.

To accurately track player movements, we employ optical flow to measure camera movement between frames. By implementing perspective transformation, we can convert the scene's depth and perspective, enabling the measurement of player movements in meters instead of pixels. Ultimately, we calculate each player's speed and the total distance they cover during the game.

* Note:
    1. As we cannot upload large videos to GitHub repositories, a link to the input video is provided. Additionally, screenshot images are included to illustrate how the video will look after project completion.
    2. For the dataset, kindly use your API key in the given code, or you can directly download the `best.pt` and  `last.pt` file from the provided link.

## Modules Used

The following modules are used in this project:

- **YOLO**: AI object detection model
- **KMeans**: Pixel segmentation and clustering to detect t-shirt color
- **Optical Flow**: Measure camera movement
- **Perspective Transformation**: Represent scene depth and perspective
- **Speed and Distance Calculation**: Per player


# Trained Models

* [Trained YOLO Model](https://drive.google.com/drive/folders/1RC5Fnw5PsF8vY4rLxeoE5t2lPer-1Jk5?usp=sharing)


# Sample Video

* [Input Video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view)


