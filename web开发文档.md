## web开发文档

### 简介

开发技术：(python) + Flask + (html + css + javascript) + 其他各式各样的库

开发人员：林春茹

### 文件结构

- `trans.py`

  Flask服务器主文件 + 沟通`c++`后端和`python`服务器

- `static`

  Flask储存静态文件（javascript, css 和 字体文件等）的目录

- `template`

  Flask储存页面文件（html）的目录

### web具体内容

- `/和/mine/index`

  主页

- `/ticket和/mine/ticket`

  车票查询购买页面

- `/admin`

  管理员页面

- `/mine`

  个人主页

- `/train和/mine/train`

  列车查询页面

- `/login`

  登录页面

- `/register`

  注册页面

### 一些实现细节

- 利用 Jinja2 模板渲染，同时通过 Jinja2 中的变量来控制显示内容，例如导航栏中哪一栏改显示为被激活状态。
- 所有动态内容大多使用 JQuery 更新，如查询结果的表格等。

### 其他

- ~~我觉得这网站做的还挺好看的。~~