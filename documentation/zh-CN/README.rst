================================
 pySerial  |build-status| |docs|
================================

Language :us: English_ :cn: 简体中文_
=========================================================================

概述
====
pySerial模块封装了对串口的访问，通过该模块可以简单的实现串口通讯功能。它提供了运行在Windows，OSX，Linux，BSD（可能是任何POSIX兼容系统）和IronPython上的Python的后端。“serial”模块自动选择适当的后端。

- 工程主页: https://github.com/pyserial/pyserial
- 下载地址: https://pypi.python.org/pypi/pyserial
- 法律许可: BSD license, (C) 2001-2017 Chris Liechti <cliechti@gmx.net>


文档
====
API（应用程序接口）文档、用法和例程可查阅 documentation_ 目录下的文档。

- .rst后缀文件可以在任何文本编辑器中查看或者使用 Sphinx_ 转换成HTML或PDF格式
- 在线HTML版本请浏览：https://pythonhosted.org/pyserial/

例程
====
例程和测试单元存放在工程文件的 examples_ 目录下。


安装
====
大多数用户可以通过一下命令安装pySerial模块，更多安装信息请查阅 `documentation/pyserial.rst`_ 该文档。

``pip install pyserial`` 

Windows，OSX，Linux，BSD，Jython，IronPython可通过 Python_ 库下载源文件后使用setup.py进行安装（请参阅上面的下载地址）。

或者是通过conda命令来安装（conda版本可用于Linux，Mac和Windows）：

``conda install -c conda-forge pyserial``  


中文支持
========
问文档的翻译工作由 zoumingzhe@qq.com 作者主页_ 独立完成。

为了更好的帮助更多的中国开发者了解和使用pySerial模块，请关注中文工程主页: https://github.com/zoumingzhe/pyserial


.. _作者主页: https://zoumingzhe.github.io
.. _English: ../../README.rst
.. _简体中文: ../../documentation/zh-CN/README.rst
.. _`documentation/pyserial.rst`: https://github.com/pyserial/pyserial/blob/master/documentation/pyserial.rst#installation
.. _documentation: https://github.com/pyserial/pyserial/blob/master/documentation
.. _examples: https://github.com/pyserial/pyserial/blob/master/examples
.. _Python: http://python.org/
.. _Sphinx: http://sphinx-doc.org/
.. |build-status| image:: https://travis-ci.org/pyserial/pyserial.svg?branch=master
   :target: https://travis-ci.org/pyserial/pyserial
   :alt: Build status
.. |docs| image:: https://readthedocs.org/projects/pyserial/badge/?version=latest
   :target: http://pyserial.readthedocs.io/
   :alt: Documentation