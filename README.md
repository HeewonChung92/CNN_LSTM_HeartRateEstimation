## CNN_LSTM_HeartRateEstimation
CNN-LSTM based Heart Rate Estimation from PPG and Accleration

***Paper***  
Deep Learning for Heart Rate Estimation from Reflectance Photoplethysmography with Acceleration Power Spectrum and Acceleration Intensity. with IEEE Access.
Link: https://ieeexplore.ieee.org/document/9042276

***Abstract***  
We propose a new deep neural network based on multiclass and non-uniform multilabel classification for HR estimation. In our proposed model, we used two power spectra of PPG and acceleration signals along with the acceleration intensity for the input layer. The proposed model comprised of two convolutional layers, two LSTM layers, one concatenation layer, and three fully connected layers including a softmax. In the proposed model, we also presented a new scheme to evaluate the loss value by modifying the true HR value into Gaussian distribution. 

***Model Architecture & Summary***  
<img src="https://github.com/HeewonChung92/CNN_LSTM_HeartRateEstimation/blob/master/Model%20Architecture.jpg" width="100%" />  

<img src="https://github.com/HeewonChung92/CNN_LSTM_HeartRateEstimation/blob/master/Model%20Summary.jpg" width="60%" />  

***Physiological Data Measured During Intensive Physical Exercise with Matlab***  
Heewon Chung, Hooseok Lee, Hoon Ko, and Jinseok Lee (Professor) a member of BAMI LAB.   
https://sites.google.com/site/bamilab/biosignal-lab   

***Matlab Data***  
This database contains wrist PPGs recorded during stay, walking, and running.
Accelerometers and Gyroscopes are collected to remove the motion artifact from the PPGs.
A reference chest ECG is included to allow a gold-standard comparison of heart rate during CR exercise.
* ECG sampling rate : 125Hz   
* PPG sampling rate : 50Hz  
* Acc sampling rate : 50Hz  

***Data Description***
* bpm_ecg        : ECG heart rate
* bpm_proposed   : ECG times   
* rawPPG         : PPG signal 
* rawAcc         : Accelerometer signal 
 
