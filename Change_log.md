### 2019.9.18
#### 版本号: 0.0.3

内容:
1. 更改视频重新加载逻辑，现在当播放错误时会重新请求接口以防止服务器返回403错误
2. 添加竖屏视频支持，现在当播放竖屏视频时会以裁剪形式播放。
底部详情栏可以向上滑动，同时播放器会缩小直到最小高度。
只有当点击全屏时才会完整的显示视频。
3. 添加播放器请求头，UA和Referer。
UA为固定的chrome UA，Referer则为Appconfig中选择的HOST
4. 修复了一些bug，具体是啥我忘了=、=
5. 添加自动版本号

------
### 2019.9.12
#### 版本号: 0.0.2

内容:
1. 添加更新检查
2. Theme更改为Material.Light

------
### 2019.9.9
#### 版本号: 0.0.1

内容:
第一次Commit，完成播放器和视频列表