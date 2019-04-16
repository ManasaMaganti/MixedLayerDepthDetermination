# MixedLayerDepthDetermination
A ground based elastic backscatter LIDAR signals contain the growth of the mixed layer (ML),
a daylight phenomenon of the atmospheric boundary layer. To delineate the ML information from LIDAR, 
one needs to process the LIDAR signals for noise and path loss correction. 
The post-processed LIDAR signals represent the range-resolved total backscatter of the atmosphere. 
It is proposed to estimate the ML depth using an adaptive Kalman filter. 
In order to understand the signature of the mixed layer depth (MLD), mathematical, statistical and signal processing methods 
have been applied to the LIDAR signals and the MLD values have been computed. 
The mathematical methods employed consist of three different approaches such as simple gradient, double gradient and logarithmic gradient. 
The statistical method used employs variance analysis. 
The signal processing method utilizes wavelet method that uses covariance transform to estimate the MLD. 
The proposed Kalman filter method contains a solution to estimate the mixed layer height that is sensed by the LIDAR backscatter profiles. 
The extended Kalman filter enables us to trace various parameters to find out the boundary layer height based on the simplified statistics. 
The filter minimizes the error rate in the data and predicts the estimated values based on the previous best value.
It analyzes the data and produces the nearest range values of the signal based on the given backscatter profile values and the estimated error.
