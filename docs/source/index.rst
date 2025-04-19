.. ElcGW Manual documentation master file, created by
   sphinx-quickstart on Sat Dec 28 10:03:23 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to ElcGW Manual's documentation!
========================================

功能
------

平台管理
++++++++++

平台
^^^^^^
      * 设备状态
      * 增删查
      * 设备控制
      * 设备告警
      * 设备数据（电量、电流、电压、功率、功率因数、温度）

本地
^^^^^^
      * 管理
         #. CRUD
         #. 更换(暂无)
         #. 升级

      * 网络
         #. 有线网络
            * DHCP
         #. 无线网络
            * DHCP

      * 控制
         #. 分和闸

      * 异常
         #. 过流、过压、欠压、漏电


APP (暂不可用)
^^^^^^^^^^^^^^^^^^


.. toctree::
   :maxdepth: 1
   :caption: 电力设备功能说明:

   functions/gateway/index
   functions/subdevices/index   

.. toctree::
   :maxdepth: 1
   :caption: 电力设备开发说明:

   development/subdevices/index

测试
-------

.. toctree::

   testcases/index


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
