# ZZ 学子说语音留言墙

[![GitHub](https://img.shields.io/badge/GitHub-ZZVoice-lightgrey?logo=github)](https://github.com/lsy223622/ZZVoice) [![Releases](https://img.shields.io/badge/-Releases-lightgrey?logo=github)](https://github.com/lsy223622/ZZVoice/releases) [![JSDelivr](https://data.jsdelivr.com/v1/package/gh/lsy223622/ZZVoice/badge?style=rounded)](https://www.jsdelivr.com/package/gh/lsy223622/ZZVoice)

## 2021/10/06状态更新：服务已恢复上线

## 4.0更新预告：全新界面！

---

# 常见问题

## 如何在ZZ学子说语音留言墙上传音频？

&emsp;&emsp;在语音留言查看页面的网址后面加上  `upload.html`

&emsp;&emsp;或是扫描明信片附带纸条上传网址二维码

&emsp;&emsp;请使用电脑或手机浏览器上传 **10 MB** 以内的 **MP3** 格式文件，不要使用微信 QQ 等自带浏览器

## 怎样的输出结果说明上传成功？

&emsp;&emsp;点击 **选择文件** 再点击 **上传** 后，如果上传成功，网页将会显示如下信息：

&emsp;&emsp;注意最后的 **文件上传成功**

&emsp;&emsp;`（以体积为 5,168,738 字节的 demo.mp3 为例）`

>```php
>array(1) {
>["file1"]=>
>array(5) {
>["name"]=>
>string(26) "demo.mp3"
>["type"]=>
>string(10) "audio/mpeg"
>["tmp_name"]=>
>string(14) "/tmp/demo123"
>["error"]=>
>int(0)
>["size"]=>
>int(5168738)
>}
>}
>array(1) {
>[0]=>
>string(21) "文件上传成功！"
>}
>```

## 微信扫码访问提示非标准端口怎么办？

&emsp;&emsp;不要在意，继续访问就好了

## 如何获得其他附加服务？

### 可以联系 QQ **2413282135** 获得以下服务：

- 更换背景图片、播放器logo
- 禁用上传功能（防止当前已上传的音频被替换）
- 人工上传音频（你真的不会用上面的方法上传吗？）
- 其他服务可询问但不一定提供

---

# 更新日志

## Release v3.2 （ modern + legacy ）

2021.1.25

3.2 legacy 相关改进
- legacy 版本改进为单文件 `index.html`
- 使用公用 `resources` 文件夹放置共享静态文件，便于更新修补和节约空间
- 与此同时 `legacyswitch.php` 修改为简单的 php `copy` 函数，增加文字返回消息

明天是第二次年初义卖，希望 3.2 版本能伴随语音留言明信片再次卖出一点钱qwq


## Release v3.1 （ modern + legacy ）

2021.1.23

modern + legacy
- **modern** 版本同 3.0
- 新增 **legacy** 版本将静态文件还原为本地实现
- 新增 **legacyswitch** 功能，可一次性切换 modern 版本为 legacy 版本
- 新增 `legacyswitch.php` 使用递归复制算法将 modern 文件替换为 legacy 文件


## Release v3.0

2021.1.18

3.0 全新改进！
- 静态文件（除`index.html`以及`voice.mp3`以外）全面部署 CDN
- 优化页面加载速度，提高并发访问能力，提供全球范围接近一致的打开用时
- 界面延续 1.3 版本不变

**2021 年，用户体验再进化！**


## Release v2.0

2020.1

2.0 已被弃用
- ZZ 学子说语音留言明信片于 2020 年初义卖首发
- 然后卖的很惨 *（历史事件）*


## Release v1.3

2020.1

1.3 接近完成
- 其实我也忘了有什么改动
- 这才是最终选用的正式版本
- 2020 春节被小米公司抄袭（他们做的语音留言明信片和我的完全一样）
- 大概是当时做 Beta 的时候和几个那边的开发说起过
- md 确实没有什么办法


## Beta v1.2

2019.12

1.2 基本成型
- 解除与光阑的合作关系！
- 光阑有关内容已被移除
- 界面大幅度修改


## Beta v1.1

2019.11

1.1 第一次修改
- 界面小改


## Beta v1.0

2019.10

1.0 最初版本

- lsy223622 于 2019.10 首次提出语音留言明信片设想并成功实现

---

# 关于

ZZ 学子说语音留言墙

由 *lsy223622* 创作于2019.10

QQ:*2413282135*

---

## 最后更新时间

`2021-1-25`
