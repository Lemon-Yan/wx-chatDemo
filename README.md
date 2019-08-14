# wx-chatDemo
简易聊天室

### 文章说明
说明：此文章根据项目需要做的Demo，总结了一下，以备后期使用。
实现的功能：
> 1、发送文字；
2、发送文字+表情；
3、发送图片（拍照+相册）；
4、实现多图上传；
5、表情与文字搭配的解析；
6、下滑到底部；
7、分享功能（带参数）；
8、预览图片；

## 示例截图
![](https://upload-images.jianshu.io/upload_images/4041074-0092b22d9d01e8b3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 注意事项
由于小程序没有Vue的v-html方法，我使用的是rich-text方法做替代，
rich-text方法需要注意的地方，请自行到[官网](https://developers.weixin.qq.com/miniprogram/dev/component/rich-text.html)查看，这地方有坑。
>- **img 标签仅支持网络图片。**


参考链接：
[微信小程序-实现分享](https://blog.csdn.net/sinat_41917956/article/details/80606459)
[上传图片](https://www.cnblogs.com/Sarah-Dora/p/9257789.html)

