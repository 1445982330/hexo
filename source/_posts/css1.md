---
title: css1
date: 2023-01-07
---
MP3
本地/网上音乐

<audio src="https://cong-picgo.oss-cn-shenzhen.aliyuncs.com/mp3/bj.mp3" controls="controls" preload="nome"></audio>

网易云音乐
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=1964850254&auto=1&height=66"></iframe>

MP4
Bilibili视频
src参数 
&high_quality=1 (1=最高画质 0=最低画质)
&danmaku=0 (1=打开弹幕 0=关闭弹幕)
&page=1 (第几个视频, 起始下标为 1 (默认值也是为1)就是B站视频, 选集里的, 第几个视频)
&aid=80433022 (视频ID就是B站的 avxxxx 后面的数字)
&bvid=BV1GJ411x7h7 (视频的BV)
&cid=137649199 (这个字段不填也没关系)
height # 高
width #宽
allowfullscreen="true" # 移动端全屏
sandbox="allow-top-navigation allow-same-origin allow-forms allow-scripts" # 禁止弹出网页

<iframe src="//player.bilibili.com/player.html?aid=80433022&bvid=BV1GJ411x7h7&cid=137649199&page=1&high_quality=1&danmaku=0" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" danmaku="0" width=100% height=500> </iframe>

<iframe height= 498 width= 510  src="http://player.youku.com/embed/XNjcyMDU4Njg0"> </iframe>