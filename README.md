Car Number Plate Detection Project
This project is a MATLAB-based implementation of a car number plate detection system. It uses image processing techniques to identify and isolate the number plate region from an image. This system can be applied in various scenarios such as traffic management, law enforcement, and automated parking systems.

Features
Converts RGB images to grayscale for simplified processing.
Removes noise using morphological operations (dilation and erosion).
Detects edges horizontally and vertically to locate potential number plate regions.
Smoothens edge data using a low-pass filter for accuracy.
Filters irrelevant regions dynamically and isolates the number plate.

Steps Involved
1)Image Acquisition:
 Load an image using the imread function.
 Display the image using imshow for visualization.

2)Preprocessing:
  Convert the color image to grayscale using rgb2gray.
  Apply dilation to enhance edges and reduce noise.

3)Edge Detection:
  Process horizontal and vertical edges to identify regions of interest.
  Generate histograms for edge intensity analysis.

4)Histogram Processing:
  Smooth edge histograms using a low-pass filter.
  Apply dynamic thresholding to focus on relevant features.

5)Region of Interest (ROI) Detection:
  Identify the probable region containing the number plate.
  Create a bounding box around the detected area.

6) Visualization:
    Display intermediate results and the final detected number plate region.

Requirements
MATLAB (with Image Processing Toolbox)
Sample car images with visible number plates

Files Included
carno.m: MATLAB script for number plate detection.
car.jpg: Sample car image for testing.
DIP_SYNOPSIS.pdf: Documentation explaining the project.

Usage
Clone the repository:
     git clone https://github.com/Kruthikabn/CarNumberPlateDetection.git
Open MATLAB and navigate to the project folder.
Run the script:
      carno
View the outputs in the MATLAB figure windows.

Applications
Automatic Number Plate Recognition (ANPR) systems.
Traffic monitoring and law enforcement.
Automated toll collection and parking systems.

License

This project is licensed under the MIT License.
Feel free to contribute to this project by submitting issues or pull requests!

