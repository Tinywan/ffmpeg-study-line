# FFmpeg音视频的解决方案
##  代码转换过程 

```bash
 _______              ______________
|       |            |              |
| input |  demuxer   | encoded data |   decoder
| file  | ---------> | packets      | -----+
|_______|            |______________|      |
                                          v
                                      _________
                                     |         |
                                     | decoded |
                                     | frames  |
                                     |_________|
 ________             ______________       |
|        |           |              |      |
| output | <-------- | encoded data | <----+
| file   |   muxer   | packets      |   encoder
|________|           |______________|

```
##  教程
+   [FFmpeg Encoding and Editing Course(FFmpeg编码和编辑课程)](http://slhck.info/ffmpeg-encoding-course/#/)
+   [FFmpeg VBR Settings](http://slhck.info/video/2017/02/24/vbr-settings.html)
+   [了解速率控制模式（x264，x265，vpx）](http://slhck.info/video/2017/03/01/rate-control.html)
+   [CRF指南（x264和x265中的恒定速率因子）](http://slhck.info/video/2017/02/24/crf-guide.html)
