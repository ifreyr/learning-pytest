.. learning-pytest documentation master file, created by
   sphinx-quickstart on Mon Jun 11 10:03:52 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Pytest 使用手册
===========================================


快速入门
==========

.. toctree::
   :caption: 快速入门
   :hidden:

   doc/intro/getting-started

:doc:`doc/intro/getting-started`
   使用 pytest 运行最简单的测试用例。

测试函数
===========

.. toctree::
   :caption: 测试函数
   :hidden:

   doc/test-function/assert
   doc/test-function/exception
   doc/test-function/mark
   doc/test-function/skip
   doc/test-function/xfail
   doc/test-function/parametrize

:doc:`doc/test-function/assert`
   使用 assert 编写测试。

:doc:`doc/test-function/exception`
   使用 pytest 进行异常捕获测试。

:doc:`doc/test-function/mark`
   使用标记执行特定的测试用例。

:doc:`doc/test-function/skip`
   使用标记跳过测试。

:doc:`doc/test-function/xfail`
   明知失败还是要执行的解决方法。

:doc:`doc/test-function/parametrize`
   参数化测试。



.. toctree::
   :maxdepth: 2

   doc/fixture
   doc/plugin
   doc/configuration



