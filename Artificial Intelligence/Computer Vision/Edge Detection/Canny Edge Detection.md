Canny Edge Detection is a multi-stage algorithm that is used to detect a wide range of edges in images. Developed by John F. Canny in 1986, it is considered one of the most effective edge detection methods due to its ability to minimize error and its robustness against noise. It is commonly used in the field of computer vision, particularly in the areas of image processing and machine vision.

![[Valve_monochrome_canny_(6).png]]
## Definition

Canny Edge Detection is an image processing technique that involves a multi-stage algorithm to detect edges. The edges are identified by searching for the local maxima of the gradient of the image. The gradient is calculated using the derivative of a Gaussian filter.

## Explanation

The process of Canny Edge Detection can be broken down into the following steps:

1. Noise reduction: A Gaussian filter is applied to clean the image of noise.
2. Gradient calculation: The gradient of the image is calculated to find the intensity and direction of the edges.
3. Non-maximum suppression: Only the edges that are the main local maxima are marked as such, to ensure that the result is a thin line.
4. Double threshold: Potential edges are determined by thresholding.
5. Edge Tracking by Hysteresis: Finalizes the detection of edges by suppressing all the other edges that are weak and not connected to strong edges.

## Examples:

- Applying the Canny Edge Detector to a grayscale image to detect the edges of objects within it.
- Using the algorithm to preprocess images for computer vision tasks, such as object recognition, where the edges of objects are important features.

## Properties:

- The Canny Edge Detector uses a Gaussian filter to smooth the image and reduce noise.
- It applies non-maximum suppression to find the most significant edges.
- The algorithm uses double thresholding to differentiate between strong, weak, and non-edges.
- It includes a hysteresis step to ensure that weak edges are only considered if they are connected to strong edges.

## Applications

Canny Edge Detection is widely used in various computer vision systems, such as:

- Autonomous vehicles for lane detection.
- Medical imaging to help in the detection of tumors or other medical conditions.
- Machine vision in manufacturing for detecting the edges of products for quality control.
- Robotics for object detection and navigation.

## Connection to Other Topics:

- [[Gaussian Filter]]: explanation of how Gaussian filters are used to smooth images.
- [[Gradient Calculation]]: explanation of how gradients are used to detect changes in intensity in an image.
- [[Non-maximum Suppression]]: explanation of the process to thin out the edges.
- [[Double Thresholding]]: explanation of how thresholds are set to identify strong and weak edges.
- [[Hysteresis]]: explanation of the process of connecting weak and strong edges.
- [[Artificial Intelligence]]
- [[Edge Detection]]
- [[Computer Vision]]