# iTOP4412-qt-uvc-opencv-arm

This repo contains the qt projects about "uvc-opencv-arm", which I managed to transplant to arm-board iTOP-4412.
All projects in this repo has been tested on Ubuntu12.0.4 + qtcreator-2.6.1 + opencv-2.4.9:
--PC : qt4.8.1 + GCC-x86-x64
--ARM: qt4.7.1 + arm-none-linux-gnueabi-gcc-4.3.2

The descriptions of each project code are below:
1) uvc-ui
   The project has managed to use V4L2 APIs to drive a UVC-Camera and get yuyv frames with differnt resolution and FPS.
   
2) uvc-yuyv-opencv
   The project has managed to gets yuyv frames and turn it to gray frame via opencv.
   
3) uvc-mjpg-opencv
   The project has managed to gets mjpg frames and turn it to cv::Mat.
