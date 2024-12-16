# GitTest-test.py
# 文件上传Web应用

这是一个使用Flask框架创建的简单文件上传Web应用程序。用户可以通过一个HTML表单上传文件，服务器会检查文件类型并将其保存到指定的文件夹中。

## 目录结构
```
.
├── app.py
├── templates
│   └── upload.html
└── static
    └── uploads
```

## 安装依赖
在运行应用程序之前，请确保安装了Flask。可以使用以下命令安装Flask：
```bash
pip install Flask
```

## 运行应用程序
使用以下命令运行应用程序：
```bash
python app.py
```

## 使用方法
1. 打开浏览器，访问`http://127.0.0.1:5000/upload`。
2. 在表单中选择要上传的文件。
3. 点击“上传”按钮，文件将被上传并保存到`static/uploads`目录中。

## 注意事项
- 确保`static/uploads`目录存在，否则文件将无法保存。
- 服务器仅允许上传特定类型的文件（如图片），可以根据需要进行修改。