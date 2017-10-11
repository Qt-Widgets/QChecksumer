# QChecksumer
A file checksum(up to 64bit) computation program of Qt5.8.0.  
Components that used：QtCore QtGui QtWidgets QtConcurrent

## Feature details
1. Use QtConcurrent Map-Reduce API to compute the file checksum with multi threads.  
QtConcurrent automatically adjust the number of threads used according to the number of local processor cores available.  
2. Use a ProgressBar to display the computation progress percentage.

## Screenshot
![Screenshot](https://raw.githubusercontent.com/Zalafina/QChecksumer/master/screenshot/QChecksumer_screenshot.png)
