# FFmpeg-script
编译ffmpeg+aac+x264

* 编译 [x264-ios][3] 版本：x264-snapshot-20160814-2245-stable，环境：Xcode 9.2
* 编译 [fdk-aac-build-script-for-iOS][2] 版本：0.1.5
* 编译 [FFmpeg-iOS-build-script][1] 版本：3.4
* 依赖：[gas-preprocessor][4]

在FFmpeg库里编译x264和aac的话，预先编译好x264和aac。然后把编译好的FFmpeg库连同编译好的x264和aac库一同加入项目了，引入头文件就可以用了

[1]: https://github.com/kewlbear/FFmpeg-iOS-build-script
[2]: https://github.com/kewlbear/fdk-aac-build-script-for-iOS
[3]: https://github.com/kewlbear/x264-ios
[4]: https://github.com/yuvi/gas-preprocessor
