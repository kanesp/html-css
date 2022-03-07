# 多媒体元素

video元素
audio元素

## video元素

controls: 控制控件的属性
```html
<video controls="controls" src="" style="width:500px">
</video>
```

某些属性，只有两种状态： 1. 不写 2. 取值为属性名，称为bool属性

bool属性在html5中，可以不写属性值

autoplay: bool属性，自动播放
muted: bool属性，静音播放
loop： 循环播放

## 音频
和视频完全一直


## 兼容性
1. 旧版本浏览器不支持这两个元素
2. 不同浏览器支持的音视频格式不同

mp4、webm
为了兼容性。不在元素内部使用src属性
在video和audio内部使用<source>










