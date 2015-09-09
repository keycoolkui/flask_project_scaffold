# Flask 脚手架
> Flask  项目框架

## 如何运行

1. 创建虚拟环境 `virtualenv venv` 并激活 `source venv/bin/activate`
2. 安装依赖 `pip install -r requirements.txt`
3. 运行程序 `python manage.py runserver -r -d`
4. 打开浏览器输入地址：`http://127.0.0.1:5000` 页面出现 `hello world` 即成功！！

> 初始化运行数据库

执行 `python manage.py db init`

然后执行 `python manage.py db migrate`

最后执行 `python manage.py db upgrade`
