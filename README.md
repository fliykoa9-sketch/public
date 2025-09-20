# 使用说明

1 用户可以根据需要自行决定下载google 插件模式或者BOT程序

2 软件下载地址： https://github.com/fliykoa9-sketch/public/releases

3 使用说明查看README


# google插件使用说明

一 注册网站： https://awsinsight.net

二 注册步骤：
1. 点击上方链接访问注册网站
2. 使用 Google 邮箱登录注册
3. 获取 Token 后复制到下方 API Token 输入框

  <img width="396" height="518" alt="image" src="https://github.com/user-attachments/assets/88074fea-0e84-4af5-9c57-e9a0a59a69af" />



三 使用方法：

1 在google商店搜索 [https://chromewebstore.google.com/detail/igjaplchliebiahibhjcbjecdeckgkli](https://chromewebstore.google.com/detail/twitter-ai-reply-assistan/igjaplchliebiahibhjcbjecdeckgkli?authuser=1&hl=zh-CN)


2 或者:https://github.com/fliykoa9-sketch/public/releases
直接github下载后解压缩后打开google浏览器插件，打开开发模式，加载未打包的插件，选择解压缩文件所在的目录，加载插件
<img width="1484" height="848" alt="9999" src="https://github.com/user-attachments/assets/bc03d474-c18d-4cda-841b-1aaa8bbc33ef" />


3 点击插件输入url和token


4 生成文章内容，填入推特帐号(不是自己的)，选择文章长度，风格，其他要求。等待1-2分钟即可。
<img width="910" height="639" alt="image" src="https://github.com/user-attachments/assets/7854406b-249f-4d3e-8b1e-dddc600ab3c0" />


5 回复别人的帖子或者回复自己帖子下的评论。

<img width="653" height="540" alt="image" src="https://github.com/user-attachments/assets/28ee0bcf-b874-4fbe-80ee-afc9240ebb83" />



















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

<img width="702" height="341" alt="image" src="https://github.com/user-attachments/assets/ca00c9bf-1b70-4e40-adee-2ac478d1ca1d" />


 7. 🔧 系统要求

- Python 3.12
- Google Chrome浏览器
- 网络连接


 8. 📞 支持

如遇问题请检查：
1. Chrome浏览器
2. 网络连接
3. 配置文件
4. 线上TG客服咨询

