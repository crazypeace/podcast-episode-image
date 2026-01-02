# podcast-episode-image
从apple podcast获得每集播客封面图片

https://crazypeace.github.io/podcast-episode-image/


# 面向GPT开发
```
实现一个基于HTML JS的工具
页面包含以下几个部分
1) 文本框 可输入podcast的RSS地址
2) 文本框 可从 1) 获取RSS内容, 也可以手工输入RSS内容
3) 文本框 分析 2) 的内容, 列出所有封面图片的地址. 可手工编辑 添加或删除
4) 显示 3) 中的地址对应的图片

举例:
https://feed.xyzfm.space/y9qnpfdrctnx 是一个podcast的RSS地址, 会被填写到 1)
1) 可得到RSS数据, xml格式.  会被填写到 2)
2) 中有 <itunes:image href="https://image.xyzcdn.net/Fgd_z5yexkQF_GB0LF4Xncqqf8CU.png"/> 这样的元素, 应该将 https://image.xyzcdn.net/Fgd_z5yexkQF_GB0LF4Xncqqf8CU.png 填写到 3)
4) 显示 3) 中的地址对应的图片
```

# 后记
本次 (2025-11-20) 开发, 用到的GPT为  
[Gemini](https://gemini.google.com/)
