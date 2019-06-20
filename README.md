# Bingle

### 运行环境

Python3+Django

### 依赖

pip3 install pexpect
pip3 install demjson

### 语言编译环境

- C:gcc
- C++:g++
- C#:Mono
- Python:Python3
- JAVA:Java8
- Pascal:Free Pascal

需要预先在服务器上安装各种语言的编译器，并将其路径加入到 PATH 中。开发测试的时候建议使用 Mac 电脑，可以一次性便捷安装所有的编译环境。

### 运行程序

```shell
python3 manage.py runserver
```

### 代码结构

- Bingle/Templetes/production 下为界面模板
  - urls.py 分发 url 请求
  - view.py 处理 urls.py 分发的请求
  - compiler.py 处理编译和运行代码的主类
  - debugger.py 在线调试代码的主类
- Background 为后台处理数据库、模型相关模块
  - models.py 定义了数据库模型

### 可视化算法

- 来源自 https://github.com/algorithm-visualizer/algorithm-visualizer
- 对其中的代码跟踪进行了修改，展示的代码和运行的代码进行了分离。

### 问题页面 Markdown 展示

- 来源自 https://github.com/commonmark/commonmark.js
- 编辑页面直接撰写 Markdown 代码保存到数据库，前台通过 commonmark.js 转化成 HTML。

### MarkDown 编辑器

- 来源于https://github.com/pandao/editor.md

### 测试题编辑展示

- 来源于https://github.com/surveyjs/survey-library

### 监视变量可编辑表格

- 来源于https://github.com/vitalets/x-editable
