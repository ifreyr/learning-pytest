.. learning-pytest documentation master file, created by
   sphinx-quickstart on Mon Jun 11 10:03:52 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Pytest 使用手册
===========================================


快速入门
======================

.. toctree::
   :caption: 第一部分 快速入门
   :hidden:

   doc/intro/getting-started

:doc:`doc/intro/getting-started`
   使用 pytest 运行最简单的测试用例。

测试函数
===========

.. toctree::
   :caption: 第二部分 测试函数
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


固件
===========

.. toctree::
   :caption: 第三部分 固件
   :hidden:

   doc/fixture/intro
   doc/fixture/setup-and-teardown
   doc/fixture/scope
   doc/fixture/autouse
   doc/fixture/rename
   doc/fixture/parametrize


:doc:`doc/fixture/intro`
   固件就是函数，pytest 可以集中进行管理以便复用。

:doc:`doc/fixture/setup-and-teardown`
   使用固件实现预处理和后处理。

:doc:`doc/fixture/scope`
   声明作用域声明固件的作用范围。

:doc:`doc/fixture/autouse`
   让固件自动执行，完成诸如计时，日志任务。

:doc:`doc/fixture/rename`
   重命名固件。

:doc:`doc/fixture/parametrize`
   固件参数化，提升复用性和可维护性。


