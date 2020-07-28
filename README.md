# 批量获取网站title标题，状态码，body大小等信息，

本项目基于使用python3开发，支持自定义线程，自定义url文件，获取title后会自动保存记录到文件。
## 使用教程：
```
D:\SRC\webtitle>python3 webtitle.py
轻量级Title批量获取器V1.1
-t      线程数         默认5个线程
-f      url文本文件    默认打开当前目录的url.txt

案例如下：
python3 webtitle.py -f url.txt -t 10  #从url中读取url进行批量访问，以10个线程。
```
