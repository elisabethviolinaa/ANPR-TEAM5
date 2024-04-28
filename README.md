# ANPR-TEAM5
### This is our code for ANPR Projects

There are 3 major code segments that we will implement in our research.
- Data Prerocessing:
Based on the diverse input data, we need to ensure that the input used is in the form of images with dimensions of around 800x800 pixels. In this case, we need to convert data that is still in the form of CCTV videos to meet these criteria. (Done)
- License Plate Localization:
Based on our previous proposal, we will use Mask R-CNN for this task. This is because the algorithm is capable of capturing vehicle license plates well even in less-than-ideal conditions. The algorithm will output images of the license plates that have been separated from the vehicles. (Ongoing)
- Character Recognition:
Finally, we will use an OCR Engine called Tesseract. So, all output from Mask R-CNN will be converted into character form and the data will be saved back into a CSV file. (Ongoing)
