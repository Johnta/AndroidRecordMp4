通过AndroidAPI中提供的MediaCodec和MediaMuxer实现对硬件采集的YUV格式视频数据和PCM格式音频数据进行压缩编码，并将编码好的数据封装成MP4格式文件。
本Demo特点：
(1) 支持添加时间水印；
(2) 支持后置摄像头画面旋转0、90、180、270度；
(3) 支持前置摄像头画面旋转90度；
(4) 支持分辨率切换，前后置摄像头切换；
(5) 支持自动对焦；
(6) 解决音视频不同步，前几帧图像马赛克，muxer failed 等问题
(7) 所有对YUV的处理均在NDK层实现，编码效率高
(8) 支持YV12转NV21，NV21转YUV420sp，NV21转YUV420p
/// 博客地址:http://blog.csdn.net/andrexpert/article/details/72523408
