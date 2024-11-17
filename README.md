# Project Name
Detecting Text From Handwritten Documents
### Project Description:
#### Summary - 
This MATLAB project processes an image to detect, align, and extract text from it using several image processing and computer vision techniques. It involves detecting edges, finding the orientation of dominant text lines, aligning the text, and performing Optical Character Recognition (OCR). The final output includes the aligned image and the extracted text.
#### Course concepts used - 
1. -Image PreProcessing( Grayscale conversion, Noise Removal, Contrast enhancement)
2. -Edge and line detection
3. -Geometric and Affine Transformations
4. -Matlab Visualization
   
#### Additional concepts used -
1. -Hough Transform
2. -OCR
   
#### Dataset - 
Custom dataset of handwritten images used

#### Novelty - 
1. -Hough Transform is used to detect straight lines in the preprocessed binary edge-detected image.
2. -Canny edge detection algorithm implemented
3. -Created a custom rotation function to rotate an image by a specified angle while preserving its size and filling any uncovered areas with a white background
   
### Contributors:
1. Zacharias S Edakkara (PES1UG22EC357)
2. Vignesh Kamath (PES1UG22EC336)

### Steps:
1. Clone Repository
```https://github. com/Digital-Image-Processing-PES-ECE/Detecting_Text_From_Handwritten_Documents.git```

2. Install Dependencies
-Image processing toolbox
-Computer Vision Toolbox

3. Run the Code
```Detecting_text_from_handwritten_documents.m```

### Outputs:
-Attached under outputs

### References:
1. -```https://ijcrt.org/papers/IJCRT2107479.pdf```
2. -```https://in.mathworks.com/help/vision/ug/recognize-text-using-optical-character-recognition-ocr.html```
   
### Limitations and Future Work:
1. Accuracy is low for cursive handwriting.
2. Highly dependent on quality of input images
3. Can be implemented with more direct ocr and neural network approaches for better accuracy
4. Can be implemented for different languages
