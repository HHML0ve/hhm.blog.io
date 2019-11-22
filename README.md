# hhm.blog.io
我的个人博客

目的：本博客是记录学到的知识，生活感悟与表述自己
创建：
    博客依托于Sphinx创建，创建方法如下
    1、安装环境+搭建项目
        在git上创建一个公开项目，pull下来，粘贴Python的.gitignore文件，创建虚拟环境（本博客Python3）
        安装Sphinx v2.2.0
        安装仓库 http://mirrors.aliyun.com/pypi/simple/
        输入如下命令创建Sphinx项目
            mkdir yourdir
            cd yourdir
            sphinx-quickstart
        autodoc: automatically insert docstrings from modules (y/n) [y]
        空项目创建成功，输入如下命令发布项目
            sphinx-build -b html source build
            make html【这个命令本博客没有用到，可能有版本问题】
    2、充实博客
        source目录下有俩个文件【conf.py 配置文件 index.rst 主文件】
        index.rst需要懂得rst的语法，我也在学习中，会有一个新的页面专门写rst学习内容
    3、提交git+发布项目
        借用readthedocs发布项目即可
注意：每次修改都要重新发布项目