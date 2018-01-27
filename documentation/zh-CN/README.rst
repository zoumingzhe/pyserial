================================
 pySerial  |build-status| |docs|
================================

Language :us: English_ :cn: 简体中文_
=========================================================================

概述
====
该模块封装了串口的访问。它提供了运行在Windows，OSX，Linux，BSD（可能是任何POSIX兼容系统）和IronPython上的Python的后端。“serial”模块自动选择适当的后端。

- 工程主页: https://github.com/pyserial/pyserial
- 下载地址: https://pypi.python.org/pypi/pyserial
- 法律许可: BSD license, (C) 2001-2017 Chris Liechti <cliechti@gmx.net>


Documentation
=============
For API documentation, usage and examples see files in the "documentation"
directory.  The ".rst" files can be read in any text editor or being converted to
HTML or PDF using Sphinx_. An HTML version is online at
https://pythonhosted.org/pyserial/

例程
====
例程和测试单元存放在工程文件的 examples_ 目录下。


Installation
============
``pip install pyserial`` should work for most users.

Detailed information can be found in `documentation/pyserial.rst`_.

The usual setup.py for Python_ libraries is used for the source distribution.
Windows installers are also available (see download link above).

or

To install this package with conda run:   

``conda install -c conda-forge pyserial``   

conda builds are available for linux, mac and windows.


.. _English: ../../README.rst
.. _简体中文: ../../documentation/zh-CN/README.rst
.. _`documentation/pyserial.rst`: https://github.com/pyserial/pyserial/blob/master/documentation/pyserial.rst#installation
.. _examples: https://github.com/pyserial/pyserial/blob/master/examples
.. _Python: http://python.org/
.. _Sphinx: http://sphinx-doc.org/
.. |build-status| image:: https://travis-ci.org/pyserial/pyserial.svg?branch=master
   :target: https://travis-ci.org/pyserial/pyserial
   :alt: Build status
.. |docs| image:: https://readthedocs.org/projects/pyserial/badge/?version=latest
   :target: http://pyserial.readthedocs.io/
   :alt: Documentation