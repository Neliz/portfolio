<link rel="stylesheet" href="../styles.css">

## InfraMonitoring (signal processing)

**Project description:** I contributed to the InfraMonitoring project, which involves high-frequency monitoring of railway infrastructure from a passengertrain. The system, developed by Ricardo Rail, allows for continuous monitoring without negatively impacting the capacity of the railway. My focus was on the measurement equipement and on signal processing to convert accelerometer data into track geometry.

### Signal processing
The system uses sensors installed on trains to measure the quality of the track and overhead line, allowing for early detection of issues before they cause disruptions. The system generates around 15 GB of data per day per train, which requires automatic data processing to extract useful information.

<img src="../images/accelerometer.JPG?raw=true"/>

During the signal processing phase of the InfraMonitoring project, I used Fast Fourier Transform (FFT) and spectrograms to analyze the accelerometer data and identify the source of measurementerrors. 

FFT is a mathematical algorithm used to transform time-domain signals into frequency-domain signals. By applying FFT to the accelerometer data, we were able to identify the frequency components of the signals and calculate it towards track geometry.

Spectrograms, on the other hand, are visual representations of the frequency content of a signal over time. By plotting the spectrograms of the accelerometer data, we were able to identify specific frequency ranges that were associated with certain measurement issues. This allowed us to pinpoint the source of errors and make recommendations for new sensors and mounting brackets.


### Results
The InfraMonitoring system was found to be highly accurate in monitoring railway geometry from a passengertrain. The system was successfully implemented for multiple projects and clients, demonstrating its versatility and effectiveness in improving the safety and efficiency of railway operations.

### Used tools
Matlab, Signal Processing Toolbox, git, FFT, spectogram, NationalInstruments, 

