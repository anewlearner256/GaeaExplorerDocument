.. _class_LineGeometry:

LineGeometry 
===================

**Inherits:** :ref:`Geometry<class_Geometry>` **<** :ref:`Object<class_Object>`

描述
----

线要素

示例
----

属性
----

+-----------------+---------------------------------------+

方法
----

+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`GetStart<class_LineGeometry_method_GetStart>` **(** **)**                                                                                                                    |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`GetEnd<class_LineGeometry_method_GetEnd>` **(** **)**                                                                                                                        |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`   | :ref:`Length<class_LineGeometry_method_Length>` **(** **)**                                                                                                                        |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`QueryPoint<class_LineGeometry_method_QueryPoint>` **(** :ref:`Double<class_Double>` DistanceAlongCurve, :ref:`Boolean<class_Boolean>` asRatio **)**                          |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`HitTest<class_LineGeometry_method_HitTest>` **(** :ref:`Vector3<class_Vector3>` latlon, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)** |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`sphericalToCartesian<class_LineGeometry_method_sphericalToCartesian>` **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon **)**                           |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------


方法说明
-------

.. _class_LineGeometry_method_GetStart:

- :ref:`Vector3<class_Vector3>` **GetStart** **(** **)**

获取线的第一个点坐标

----

.. _class_LineGeometry_method_GetEnd:

- :ref:`Vector3<class_Vector3>` **GetEnd** **(** **)**

获取线的最后一个坐标

----

.. _class_LineGeometry_method_Length:

- :ref:`Double<class_Double>` **Length** **(** **)**

计算线的长度

----

.. _class_LineGeometry_method_QueryPoint:

- :ref:`Vector3<class_Vector3>` **QueryPoint** **(** :ref:`Double<class_Double>` DistanceAlongCurve, :ref:`Boolean<class_Boolean>` asRatio **)**

函数的作用是计算给定距离内的点，并返回一个Vector3类型的点

----

.. _class_LineGeometry_method_HitTest:

- :ref:`Vector3<class_Vector3>` **HitTest** **(** :ref:`Vector3<class_Vector3>` latlon, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)**

碰撞检测，如果距离小于8，则返回线段上距离latlon最近的点，否则返回0向量

----

.. _class_LineGeometry_method_sphericalToCartesian:

- :ref:`Vector3<class_Vector3>` **sphericalToCartesian** **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon **)**

纬经度转笛卡尔坐标，包含地形高度，抬高20米

----

