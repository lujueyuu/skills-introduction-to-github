# Daily Learning
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">

## Morning Planning
- [ ] 查看 [Github Blog] 获取选题灵感
- [ ] 学习 [Github [Pages] 的使用方法
- [ ] 将我的第一篇博客转换为网页形式
## Review
使用 [ffmpeg] 将图片或视频从深色模式转换为浅色模式

```bash
ffmpeg -i imput.mp4 -vf "nagete,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
