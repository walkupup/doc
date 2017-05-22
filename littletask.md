## task 1 标定你自己的相机
任务描述：用你的手机，摄像模式，对着标定板拍摄一段各种姿态的视频。或其拿你的usb摄像头或笔记本自带摄像头，写一个opencv程序采集一组图像，然后用标定程序标定摄像头参数。
素材：在opencv的目录下搜索patten，搜索到一副图像，名字可能是pattern.png，图像分辨率非常大，把它在显示器上打开，用摄像头对着它拍摄。如果拍摄的是视频，你需要把视频里的图像截取出来，10张左右就ok。
标定代码参考opencv samples目录下的calibration.cpp。

## task 2 场景识别
任务描述：实现《视觉SLAM十四讲》中讲到的DBOW3 的例子，并在实际场景中展示效果。

## task 3 orbslam 真实场景演示
实现此任务，你需要先标定你自己的相机，把标定结果填到yaml文件里，https://git.oschina.net/paopaoslam/ORB-SLAM2 里面有yaml文件的例子。
你还需要一个字典文件，在 https://github.com/raulmur/ORB_SLAM2  的 Vocabulary目录下。
然后你就可以在手机上运行orbslam的app看到效果了，apk文件在这里 https://github.com/FangGet/ORB_SLAM2_Android

## task 4 背景建模
todo

## task 5 目标检测
todo

## task 6 手写字符识别
todo

## task 7 orbslam 调试和源码阅读
todo
