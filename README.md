# Twitter自动化工具

## 🚀 一键安装

### Windows用户
双击运行 `install.bat` 文件

### macOS/Linux用户
```bash
./install.sh
```

### 手动安装
```bash
# 1. 安装依赖
pip install -r requirements.txt

# 2. 配置组件
python install_hidden.py

# 3. 配置参数（编辑config.json）

# 4. 启动程序
python start_encrypted.py
```

## ⚙️ 配置说明

编辑 `config.json` 文件：
```json
{
  "my_username": "你的用户名",
  "api": {
    "web_api_token": "你的API令牌"
  }
}
```

## 🔧 系统要求

- Python 3.8+
- Google Chrome浏览器
- 网络连接

## 📁 文件说明

- `start_encrypted.py` - 主程序入口
- `config.json` - 配置文件
- `requirements.txt` - 依赖列表
- `install_hidden.py` - 组件配置器
- `*.so` - 加密核心模块

## 🛡️ 安全特性

- 核心代码完全加密
- 商业级代码保护
- 不可逆向工程

## 📞 支持

如遇问题请检查：
1. Python版本
2. Chrome浏览器
3. 网络连接
4. 配置文件# public
