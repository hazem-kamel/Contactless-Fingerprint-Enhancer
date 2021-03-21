# Contactless-Fingerprint-Enhancer
### Introduction
The aim of this project is to enhance images for contactless fingerprints systems , A set of 1300 contactless fingerprints images were used , NFIQ algorithm were used to test the Enhancement effect on the images which is an open source and publicly available fingerprint quality assessment tool.
NFIQ  provides a high resolution quality score in the range of (1-5).

### Objective
Objective is to enhance or highlight detail that has been blurred, either as an error or a natural effect to get better NFIQ score


### Methods
Only Spatial Domain Enhancement Methods were used seperately and with combining methods to get results:
- Canny Edge Detection
 Edge detection includes a variety of mathematical methods that aim at identifying points in a digital image at which the image brightness changes sharply or, more formally, has discontinuities. 
  Canny edge detector  was used to extract the edges for the fingerprints images which is an edge detection operator that uses a multi-stage algorithm to detect a wide range of edges in images.
- Sharpening - Prewitts Op.
  Strength of the response of a derivative operator is proportional to the degree of discontinuity of the image at that point So differentiation enhances
Edges Other discontinuities (like Noise) and Deemphasizes Areas with slowly varying gray-level-values
- Log Transformation
Logarithm value of a number is a number that raises power to a base number which gives the same number as in input. Simply, the Log transformation means replacing each pixel value with its logarithm value.

### Results
- Canny Edge Detection
- Sharpening
- Log Transformation
- Combined
