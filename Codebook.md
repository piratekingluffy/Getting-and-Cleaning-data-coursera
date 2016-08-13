Code Book
The data set was built from experiments carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (walking, walking upstairs, walking downstairs, sitting, standing, laying) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, 3-axial linear acceleration and 3-axial angular velocity were captured at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually
The obtained data set has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.
The set of variables that were estimated are:
1.	mean(): Mean value
2.	std(): Standard deviation
3.	mad(): Median absolute deviation
4.	max(): Largest value in array
5.	min(): Smallest value in array
6.	sma(): Signal magnitude area
7.	energy(): Energy measure. Sum of the squares divided by the number of values.
8.	iqr(): Interquartile range
9.	entropy(): Signal entropy
10.	arCoeff(): Autoregression coefficients with Burg order equal to 4
11.	correlation(): Correlation coefficient between two signals
12.	maxInds(): Index of the frequency component with largest magnitude
13.	meanFreq(): Weighted average of the frequency components to obtain a mean frequency
14.	skewness(): Skewness of the frequency domain signal
15.	kurtosis(): Kurtosis of the frequency domain signal
16.	bandsEnergy(): Energy of a frequency interval within the 64 bins of the FFT of each window.
17.	angle(): Angle between some vectors.
No unit of measures is reported as all features were normalized and bounded within [-1, 1].
The final data set contains 10299 observations with 81 variables divided in:
1.	an activity label (Activity): WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING
2.	an identifier of the subject who carried out the experiment (Subject): 1, 3, 5, 6, 7, 8, 11, 14, 15, 16, 17, 19, 21, 22, 23, 25, 26, 27, 28, 29, 30
3.	a 79-feature vector with time and frequency domain signal variables (numeric)
The following table relates the 17 signals to the names used as prefix for the variables names present in the data set. ".XYZ" denotes three variables, one for each axis.
Name	Time domain	Frequency domain
Body Acceleration	TimeDomain.BodyAcceleration.XYZ	FrequencyDomain.BodyAcceleration.XYZ
Gravity Acceleration	TimeDomain.GravityAcceleration.XYZ	
Body Acceleration Jerk	TimeDomain.BodyAccelerationJerk.XYZ	FrequencyDomain.BodyAccelerationJerk.XYZ
Body Angular Speed	TimeDomain.BodyAngularSpeed.XYZ	FrequencyDomain.BodyAngularSpeed.XYZ
Body Angular Acceleration	TimeDomain.BodyAngularAcceleration.XYZ	
Body Acceleration Magnitude	TimeDomain.BodyAccelerationMagnitude	FrequencyDomain.BodyAccelerationMagnitude
Gravity Acceleration Magnitude	TimeDomain.GravityAccelerationMagnitude	
Body Acceleration Jerk Magnitude	TimeDomain.BodyAccelerationJerkMagnitude	FrequencyDomain.BodyAccelerationJerkMagnitude
Body Angular Speed Magnitude	TimeDomain.BodyAngularSpeedMagnitude	FrequencyDomain.BodyAngularSpeedMagnitude
Body Angular Acceleration Magnitude	TimeDomain.BodyAngularAccelerationMagnitude	FrequencyDomain.BodyAngularAccelerationMagnitude
For variables derived from mean and standard deviation estimation, the previous labels are augmented with the terms "Mean" or "StandardDeviation".
The data set is written to the file average.txt.
References
1.	http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
2.	Course Lectures
