项目结构
.
|-- DjangoTest
|   |-- __init__.py
|   |-- settings.py
|   |-- urls.py
|   |-- view.py
|   `-- wsgi.py
`--db.splite3
`-- manage.py

目录说明：

manage.py: 一个实用的命令行工具，可让你以各种方式与该 Django 项目进行交互。
DjangoTest/__init__.py: 一个空文件，告诉 Python 该目录是一个 Python 包。
DjangoTest/admin.py：后台，可以用很少量的代码就拥有一个强大的后台。
DjangoTest/forms.py：表单，用户在浏览器上输入数据提交，对数据的验证工作以及输入框的生成等工作，当然你也可以不使用。
DjangoTest/models.py：与数据库操作相关，存入或读取数据时用到这个，用不到数据库的时候，可以不使用。
DjangoTest/settings.py: Django 的设置，配置文件，比如 DEBUG 的开关，静态文件的位置等。
DjangoTest/urls.py: 网址入口，关联到对应的views.py中的一个函数（或者generic类），访问网址就对应一个函数。
DjangoTest/view.py：处理用户发出的请求，从urls.py中对应过来, 通过渲染templates中的网页可以将显示内容，比如登陆后的用户名，用户请求的数据，输出到网页。
DjangoTest/wsgi.py: 一个 WSGI 兼容的 Web 服务器的入口，以便运行你的项目。