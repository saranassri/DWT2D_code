# DWT2D_code
DWT2D_code
Read me before install and application:

Algorithm application platform

The codes works perfectly under MATLAB R2016b, while it will also works with higher version of MATLAB as well. The codes uses MATLAB tools for reading input data and illustration of results. 
Input data could be result of any inversion software, no difference in format and size. 

The DWT algorithm: 

Steps to execute code: 

1.	Load data (image_new_1 and image_new_2) that contain an inverse magnetic and gravity models. The sections could be draw in any desired direction. In the presented example, it is drawn in the east-west direction of the model. Random noise could be added to the data in any desired level. These models in the presented example are contaminated with 2% of Gaussian Noise. In order to normalize the models at the stage of applying the strategy, the range of susceptibility changes is between 0-1 with size of the model is 70 × 70 × 30 km in directions East, North and Vertical, respectively.
2. The 2D wavelet decompose the input data in 3-level and extract the approximate and details coefficients (DWT).
3. Applying fusion rule on data (by function fusion_detail_2D_final).
4.	Multilevel 2-D wavelet reconstruction the using inversion of the discrete wavelet transform (IDWT).
Result of fusing gravity and magnetic inverse models could be saved and illustrated using graphical tools of the MATLAB, based on the 2D-DWT algorithm. Result could be illustrated in any image or vector format. Here, image presentation was selected. Interpretation could be performed on these images, e. g. in the presented example, the gravity anomalies diminished during the fusion process compared to the magnetic field.

Sara Nasri and Amin Roshandel kahoo
Email address: roshandel@shahroodut.ac.ir


