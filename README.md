# QRCode-BarCode-Detection
Simple QR code and barcode reader, made using OpenCV, NumPy and Pyzbar libraries and Python.   

# Project structure 
Project constist of qrcode_and_barcode_detection.py file and Resources folder 

Resources folder contains two testing images, one of a QRcode identification card and one of a Barcode. 

# How to use 
Run the qrcode_and_barcode_detection.py file 

The program is set to read the QRcodes and barcodes using your webcam, code: cap = cv2.VideoCapture(0) 

You can change the code and use other cameras. To do so, change "0" into another digit. To learn more about it, please read the OpenCV documentation. 

Print the test images in Resources folder, or find other ways to display them infront of the camera. Personaly, I uploaded test images to my smartphone and turned the viewscreen towards the webcam. 

Program will detect the QRcodes and barcodes currently displayed infront of the camera, mark them with a rectangle and read the contents of the QRcode or bar code. Decoded qr code or bar code will be written and displayed above the purple rectangle. 

The program is able to detect and read multiple QRcodes and/or bar codes at once. 
