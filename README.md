# Self-driving-car_Lane-Detection

Welcome to my Self-driving-car_Lane-Detection project. This project is focused on developing a computer vision-based solution for lane detection in self-driving cars. It uses advanced image processing and machine learning techniques to accurately detect and track lanes on the road in real-time.

The project starts by capturing video footage from a camera mounted on a self-driving car and pre-processing the frames to remove noise and improve the image quality. Then it applies various image processing techniques such as color thresholding, edge detection, and Hough line transforms to detect the lanes in the image.

Once the lanes are detected, the project uses machine learning algorithms to track the lanes over time and predict the car's trajectory. This is done by fitting a polynomial to the detected lane lines, and using the polynomial to estimate the car's position relative to the center of the lane.

The project also includes a module for handling false positives, for example, when there is no lane present in the image. It uses a combination of temporal and spatial filtering techniques to reject false lane detections and improve the overall robustness of the system.

This project is implemented using Python and the OpenCV library, it is designed to work in real-time and can be integrated into a self-driving car platform. It is a great example of how computer vision techniques can be used to solve real-world problems such as lane detection in self-driving cars.

I hope you enjoy exploring this project, and if you have any questions or feedback, feel free to reach out to me.
