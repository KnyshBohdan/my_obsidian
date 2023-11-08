Histogram equalization is a technique in image processing that adjusts the contrast of an image using its histogram. This method is significant because it can enhance the visibility of features in images that are too bright or too dark. It is commonly used in various fields, including medical imaging, photography, and satellite imagery.

![[Pasted image 20231108183537.png]]

## Definition

Histogram equalization involves transforming the intensity distribution of an image so that the histogram of the output image is approximately uniform. This is achieved by spreading out the most frequent intensity values or stretching out the intensity range of the image.

## Explanation

The process of histogram equalization redistributes the intensity values of an image. It maps the original histogram to a new histogram with a uniform distribution of intensities, which tends to increase the global contrast of the image. This is particularly useful when the image has regions that are significantly lighter or darker than the rest of the image.

## Examples

1. In medical imaging, such as X-rays, histogram equalization can help in enhancing the visibility of bone structures.
2. In photography, an underexposed or overexposed photo can be corrected to reveal details that were not visible before.

## Properties

- Histogram equalization is an invertible operation; if the equalization function is known, the original histogram can be recovered.
- It is a global processing technique; it does not take into account the local context of pixels.
- The method can increase the contrast of background noise while decreasing the signal in areas with low contrast.

## Applications

Histogram equalization is applied in:

- Medical imaging to improve the clarity of features in X-rays and scans.
- Photography to correct exposure and enhance details.
- Satellite imagery processing to improve the visibility of features.

## Connection to Other Topics

Histogram equalization is related to other image processing techniques such as:

- [[Adaptive histogram equalization]]: A variant that computes several histograms corresponding to distinct sections of the image.
- [[Normalization (image processing)]]: A process that changes the range of pixel intensity values.
- [[Image Processing]]
* [[Artificial Intelligence]]
- [[Computer Vision]]