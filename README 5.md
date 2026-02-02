\\ DIP Task 05 – Spatial Domain Filtering on Grayscale Images

Overview
This project explores spatial domain filtering techniques used for noise reduction and image smoothing in Digital Image Processing (DIP). A grayscale image is processed using different filters to study their effect on noise removal, edge preservation, and image blurring.

Objectives
To load and display a grayscale image
To apply common spatial domain filters for noise reduction
To compare the effects of different filters visually
To analyze the strengths and limitations of each filtering technique

Tools & Libraries Used
Python
PIL (Python Imaging Library)
NumPy
SciPy
Matplotlib

Filtering Techniques Applied
1. Mean Filter
The mean filter replaces each pixel with the average value of its neighboring pixels.
Reduces random noise
Causes noticeable image blurring
Poor at preserving edges

2. Median Filter
The median filter replaces each pixel with the median of neighboring pixel values.
Very effective against Salt & Pepper noise
Preserves edges better than mean filtering

3. Mode Filter
The mode filter assigns the most frequent pixel value within a neighborhood.
Useful for impulse noise removal
Works best on images with uniform regions

4. Gaussian Filter
The Gaussian filter applies weighted averaging based on a Gaussian distribution.
Smooths images naturally
Reduces Gaussian noise
Produces less edge distortion compared to mean filtering

Results Visualization
The program displays:
Original grayscale image
Filtered images for each method
A combined comparison layout showing all filters side by side
This layout helps in visually comparing the performance of each filter.

Analysis
Each filter affects the image differently:
Mean Filter: Good noise reduction but high blurring
Median Filter: Best for impulse noise with good edge preservation
Mode Filter: Effective for dominant pixel noise
Gaussian Filter: Balanced smoothing with minimal distortion

Applications
Noise reduction in digital images
Image preprocessing for computer vision
Medical and satellite image enhancement
Digital photography improvement

Conclusion
This task demonstrates how spatial domain filtering techniques impact image quality. By analyzing the results, it becomes clear that choosing the correct filter depends on the type of noise and the desired balance between smoothing and edge preservation.