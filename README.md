# 带 H5 前端的 YouTube 搜索列表采集器

本项目可以让你通过 H5 前端界面，使用 YouTube Data API v3 搜索视频采集列表，并获得视频的详细信息。

### 1. 创建项目与获取 API Token
在使用本工具前，请前往 [Google Cloud 控制台](https://console.cloud.google.com/apis/dashboard?hl=zh-cn) 创建项目，并启用 **YouTube Data API v3**，然后获取 API Token填入**YouTube.py**，。

### 2. 安装依赖
在终端中运行以下命令来安装所需的依赖包：

```bash
pip install flask google-api-python-client pandas openpyxl
```
### 3. 运行YouTube.py

```bash
python3 YouTube.py
```

网页会在 http://0.0.0.0:5000 上运行
