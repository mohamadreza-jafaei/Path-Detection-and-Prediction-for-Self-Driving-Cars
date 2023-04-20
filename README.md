# Path Detection and Prediction Program for Self-Driving Cars using Canny and HoughLine on Video and Image
This project is a path detection and prediction program for self-driving cars that uses Canny edge detection and HoughLine transform to detect the road lines from a video or an image. The system predicts the path of the car based on the detected lines using a linear regression model.

The goal of this project is to create a program that can detect the path for a self-driving car using video and image inputs. The program detects the road lines in the video or image using Canny edge detection and HoughLine transform techniques.

The Canny edge detection algorithm is used to find the edges in the image. It works by first applying a Gaussian filter to the image to reduce noise, then computing the gradient of the image using the Sobel operator, and finally applying non-maximum suppression to thin the edges.

The HoughLine transform is then applied to the edges detected by Canny. It is used to find lines in the image by looking for the intersection of the edges. The algorithm uses the Hough space, which is a parameter space representing all possible lines in the image.

The program can be run on both images and videos. For videos, the program reads the frames of the video, processes each frame to detect the road lines, and outputs a video with the predicted path overlaid on the video. For images, the program processes the image to detect the road lines and outputs the predicted path as a separate image.

## output video: 
[![Watch the video](outputs/output_video_02.mp4)

Overall, this program can be a useful tool in developing self-driving cars as it can help in detecting and predicting the path of the car.
