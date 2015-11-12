The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals).
These are our variable

[1] "Activity Id"           
[2]"Subject Id"                
[3]"tBodyAcc-mean()-X"         
[4]"tBodyAcc-mean()-Y"         
[5] "tBodyAcc-mean()-Z"            
[6] "tBodyAcc-std()-X"            
[7] "tBodyAcc-std()-Y"            
[8] "tBodyAcc-std()-Z"          
[9] "tGravityAcc-mean()-X"     
[10]"tGravityAcc-mean()-Y"     
[11] "tGravityAcc-mean()-Z"       
[12]"tGravityAcc-std()-X"       
[13] "tGravityAcc-std()-Y"       
[14]"tGravityAcc-std()-Z"      
[15]"tBodyAccJerk-mean()-X"    
[16]"tBodyAccJerk-mean()-Y"     
[17] "tBodyAccJerk-mean()-Z"   
[18]"tBodyAccJerk-std()-X"   
[19]"tBodyAccJerk-std()-Y"     
[20]"tBodyAccJerk-std()-Z"      
[21] "tBodyGyro-mean()-X"    
[22]"tBodyGyro-mean()-Y"     
[23]"tBodyGyro-mean()-Z"       
[24]"tBodyGyro-std()-X"   
[25] "tBodyGyro-std()-Y"     
[26]"tBodyGyro-std()-Z"       
[27]"tBodyGyroJerk-mean()-X"    
[28]"tBodyGyroJerk-mean()-Y"    
[29] "tBodyGyroJerk-mean()-Z"  
[30]"tBodyGyroJerk-std()-X"      
[31]"tBodyGyroJerk-std()-Y"      
[32]"tBodyGyroJerk-std()-Z" 
[33] "tBodyAccMag-mean()"   
[34]"tBodyAccMag-std()"      
[35]"tGravityAccMag-mean()"   
[36]"tGravityAccMag-std()"      
[37] "tBodyAccJerkMag-mean()"  
[38]"tBodyAccJerkMag-std()"     
[39]"tBodyGyroMag-mean()"        
[40]"tBodyGyroMag-std()"        
[41] "tBodyGyroJerkMag-mean()"   
[42]"tBodyGyroJerkMag-std()"   
[43]"fBodyAcc-mean()-X"         
[44]"fBodyAcc-mean()-Y"         
[45] "fBodyAcc-mean()-Z"      
[46]"fBodyAcc-std()-X"      
[47]"fBodyAcc-std()-Y"         
[48]"fBodyAcc-std()-Z"          
[49] "fBodyAccJerk-mean()-X"    
[50]"fBodyAccJerk-mean()-Y"    
[51]"fBodyAccJerk-mean()-Z"     
[52]"fBodyAccJerk-std()-X"      
[53] "fBodyAccJerk-std()-Y"  
[54]"fBodyAccJerk-std()-Z"     
[55]"fBodyGyro-mean()-X"      
[56]"fBodyGyro-mean()-Y"        
[57] "fBodyGyro-mean()-Z"       
[58]"fBodyGyro-std()-X"       
[59]"fBodyGyro-std()-Y"       
[60]"fBodyGyro-std()-Z"         
[61] "fBodyAccMag-mean()"    
[62]"fBodyAccMag-std()"       
[63]"fBodyBodyAccJerkMag-mean()" 
[64]"fBodyBodyAccJerkMag-std()" 
[65] "fBodyBodyGyroMag-mean()"     
[66]"fBodyBodyGyroMag-std()" 
[67]"fBodyBodyGyroJerkMag-mean()"
[68]"fBodyBodyGyroJerkMag-std()" 

We have 68 variables. In the table bellow we have described the variable.

We are using:

u (unit): frecuency or time (f or t)
measure: mean() or std().
direction: X, Y or Z.
For example u-BodyAcc-measure-direction are 6 variable

tBodyAcc-mean()-X tBodyAcc-mean()-Y tBodyAcc-mean()-Z tBodyAcc-std()-X tBodyAcc-std()-Y tBodyAcc-std()-Z fBodyAcc-mean()-X fBodyAcc-mean()-Y fBodyAcc-mean()-Z fBodyAcc-std()-X fBodyAcc-std()-Y fBodyAcc-std()-Z

For example u-BodyAccMag-measure are 4 variable (2 for unit and 2 for measure 2*2=4)



Variable name                    |  Description
-------------------------------- | -----------------------------
Activity Id                      |  Name of the Activity
Subject Id                       |  Identifier of the subject 
u-BodyAcc-measure-direction      |  Body Acceleration    
u-GravityAcc-measure-direction   |  Gravity Acceleration
u-BodyAccJerk-measure-direction  |  Jerk signal for the Body Acceleration
u-BodyGyro-measure-direction     |  Gyroscope
u-BodyGyroJerk-measure-direction |  Jerk signal for the Gyroscope
u-BodyAccMag-measure             |  Ecludien norm for the Body Acclearation
u-GravityAccMag-measure          |  Ecludien norm for the Gravity Acceleration
u-BodyAccJerkMag-measure         |  Ecludien norm of Jerk signal for the Body Acceleration
u-BodyGyroMag-measure            |  Ecludien norm for the Body Gyroscope        
u-BodyGyroJerkMag-measure        |  Ecludien norm of the Jerk signal for the Gyroscpe  
