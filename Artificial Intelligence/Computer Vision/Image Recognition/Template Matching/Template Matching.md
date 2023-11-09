Template matching is a fundamental technique in digital image processing that involves searching and finding the location of a template image in a larger image. It is crucial for applications that require pattern recognition, such as quality control in manufacturing, navigation of mobile robots, and edge detection in images.

## Definition

Template matching is defined as the process of locating a smaller image, or a template, within a larger one. The goal is to find the part of the larger image that matches the template image as closely as possible.

## Explanation

Template matching works by sliding the template image over the search image (also known as the "target" image) and computing a numerical measure of match at each possible position. There are several methods to do this, but two common ones are cross-correlation, which measures the similarity, and the sum of absolute differences (SAD), which measures the discrepancy.

## Examples

1. **Quality Control**: In a manufacturing line, template matching can be used to identify parts that do not match a quality standard template.
2. **Robot Navigation**: Mobile robots can use template matching to navigate by comparing their camera feed to a database of images of the environment.
3. **Edge Detection**: In image processing, template matching can be used to find edges by matching an edge template to areas in the image.

## Properties

- **Robustness to Occlusion**: Good template matching algorithms can handle cases where the template is partially obscured.
- **Tolerance to Non-Rigid Transformations**: They can also match templates that have undergone non-rigid transformations.
- **Sensitivity to Illumination and Scale**: The algorithms can be sensitive to changes in illumination and scale, which can be mitigated by using feature-based approaches.

## Applications

Template matching is widely used in various fields such as computer vision for facial recognition systems, medical image processing for identifying features in X-rays, and in geostatistical simulations.

## Connection to Other Topics

Template matching is related to other image processing techniques such as:

- [[Stereo matching]]: Used for creating 3D models from two images.
- [[Image registration]]: Aligns two images that may be taken at different times or from different sensors.
- [[Scale-invariant feature transform (SIFT)]]: Detects and describes local features in images.