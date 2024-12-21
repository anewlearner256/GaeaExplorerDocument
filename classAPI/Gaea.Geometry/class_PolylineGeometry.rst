.. _class_PolylineGeometry:

PolylineGeometry 
===================

**Inherits:** :ref:`Geometry<class_Geometry>` **<** :ref:`Object<class_Object>`

描述
----

折线要素

示例
----

属性
----

+-----------------+-------------------------------------------+

方法
----

+-------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`                     | :ref:`GetSegments<class_PolylineGeometry_method_GetSegments>` **(** **)**                                                                                                              |
+-------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`Length<class_PolylineGeometry_method_Length>` **(** **)**                                                                                                                        |
+-------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                   | :ref:`QueryPoint<class_PolylineGeometry_method_QueryPoint>` **(** :ref:`Double<class_Double>` DistanceAlongCurve, :ref:`Boolean<class_Boolean>` asRatio **)**                          |
+-------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                   | :ref:`sphericalToCartesian<class_PolylineGeometry_method_sphericalToCartesian>` **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon **)**                           |
+-------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PolylineGeometry<class_PolylineGeometry>` | :ref:`Split<class_PolylineGeometry_method_Split>` **(** :ref:`Int32<class_Int32>` count, :ref:`Int32<class_Int32>` agg **)**                                                           |
+-------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                   | :ref:`HitTest<class_PolylineGeometry_method_HitTest>` **(** :ref:`Vector3<class_Vector3>` latlon, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)** |
+-------------------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------


方法说明
-------

.. _class_PolylineGeometry_method_GetSegments:

- :ref:`List`1<class_List`1>` **GetSegments** **(** **)**

获取折线要素的各段折线

----

.. _class_PolylineGeometry_method_Length:

- :ref:`Double<class_Double>` **Length** **(** **)**

折线的长度

----

.. _class_PolylineGeometry_method_QueryPoint:

- :ref:`Vector3<class_Vector3>` **QueryPoint** **(** :ref:`Double<class_Double>` DistanceAlongCurve, :ref:`Boolean<class_Boolean>` asRatio **)**

查询给定距离处的三维向量

----

.. _class_PolylineGeometry_method_sphericalToCartesian:

- :ref:`Vector3<class_Vector3>` **sphericalToCartesian** **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon **)**

根据经纬度坐标转换成笛卡尔坐标

----

.. _class_PolylineGeometry_method_Split:

- :ref:`PolylineGeometry<class_PolylineGeometry>` **Split** **(** :ref:`Int32<class_Int32>` count, :ref:`Int32<class_Int32>` agg **)**

未知

----

.. _class_PolylineGeometry_method_HitTest:

- :ref:`Vector3<class_Vector3>` **HitTest** **(** :ref:`Vector3<class_Vector3>` latlon, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)**

判断点与折线的关系。如果检测到点在线上，则返回该点的位置，否则返回Vector3.Zero。

----

