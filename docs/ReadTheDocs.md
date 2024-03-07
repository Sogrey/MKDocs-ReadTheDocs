# The theme ReadTheDocs

For full documentation visit [Full featured documentation deployment platform - Read the Docs --- 全功能文档部署平台-阅读文档](https://about.readthedocs.com/?ref=readthedocs.org).

# Upgrade your documentation with Read the Docs 通过阅读文档升级文档

1. Create an account   注册一个帐户
   
    Sign up with GitHub or your email.
    使用GitHub或您的电子邮件注册。

2. Import your project   导入您的项目
   
    Select your existing Git repositories with a 1-click interface.
    通过单击界面选择您现有的Git存储库。

3. Add YAML config   添加YAML配置
   
    Copy this example, it probably does what you want 😉
    复制这个例子，它可能会做你想做的事情。

``` yml
version: 2
build:
os: ubuntu-22.04
tools:
    python: "3.10"
    # You can also specify other tool versions:
    # nodejs: "16"

# Build documentation in the docs/ directory with Sphinx
sphinx:
configuration: docs/conf.py

# Dependencies required to build your docs
python:
install:
- requirements: docs/requirements.txt
```

# Project layout

``` yml
    # Configuration
    theme:
    name: readthedocs
```
