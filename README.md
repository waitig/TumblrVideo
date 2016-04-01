# TumblrVideo
## 自动下载Tumblr用户所有视频的脚本
### 功能说明
* 此脚本可以根据作者主页自动搜集作者所有的视频文件，并将视频地址保存到本地。
* 可选是否自动下载视频文件到本地
* 支持单个用户链接模式，也可以将多个用户的主页地址放到文件中，然后使用本脚本打开的方式。
* 下载支持wget、request、urllib2三种下载方式，默认通过urllib方式，通过脚本相关注释来控制使用哪种方式。
* 无论是否保存，都会在./xxx/video/下生成一个url文件，里面包含了爬取到的所有视频的下载地址，你可以将这些地址粘贴到迅雷当中下载，速度更快~
### 使用方法：
* python .\TumblrModel.py -u'http://xxx.tumblr.com' 0      --搜集http://xxx.tumblr.com的所有视频，但不将文件保存到本地
* python .\TumblrModel.py -u'http://xxx.tumblr.com' 1      --下载http://xxx.tumblr.com的所有视频，并且将文件保存到本地
* python .\TumblrModel.py -f'filename' 0                   --搜集filename中所有的链接中的所有视频，但不将文件保存到本地
* python .\TumblrModel.py -f'filename' 1                   --下载filename中所有的链接中的所有视频，并且将文件保存到本地
### 反馈
* 反馈请到我的主页waitig.com或者本页添加评论
