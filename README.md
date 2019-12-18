# Bài cuối kỳ - Hệ thống nhận dạng hành động
Một dự án nhận dạng hành động trực tuyến thời gian thực dựa trên bộ xương, phân loại và nhận dạng dựa trên các khớp nối, có thể được sử dụng để theo dõi an toàn .. 

Thành viên thực hiện: ĐỖ QUANG PHÁP - 17CE - Khoa CNTT và Truyền Thông
                      NGUYỄN CẢNH THÔNG 17CE - Khoa CNTT và Truyền Thông


------
## Giới thiệu
*The **pipline** of this work is:*   
 - Realtime pose estimation by [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose);   
 - Online human tracking for multi-people scenario by [DeepSort algorithm](https://github.com/nwojke/deep_sortv);   
 - Action recognition with DNN for each person based on single framewise joints detected from Openpose.


------
## Thư viện sử dụng
 - python >= 3.5
 - Opencv >= 3.4.1   
 - sklearn
 - tensorflow & keras
 - numpy & scipy 
 - pathlib
 
 
------
## Kết quả 
 - ***actions detection***
<p align="center">
    <img src="https://github.com/ncthong/Action_recognition/blob/master/test_out/sp.png", width="540">
 
 - ***work surveilence***
<p align="center">
    <img src="https://github.com/LZQthePlane/Online-Realtime-Action-Recognition-based-on-OpenPose/blob/master/test_out/webcam_under_scene-1.gif", width="540">


-------

