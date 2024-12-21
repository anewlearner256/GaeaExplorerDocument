.. _class_PointGeometry:

PointGeometry 
===================

**Inherits:** :ref:`Geometry<class_Geometry>` **<** :ref:`Object<class_Object>`

描述
----

点要素

示例
----

属性
----

+-----------------+----------------------------------------+

方法
----

+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`GetPoint<class_PointGeometry_method_GetPoint>` **(** **)**                                                                                                                    |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`HitTest<class_PointGeometry_method_HitTest>` **(** :ref:`Vector3<class_Vector3>` latlon, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)** |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------


方法说明
-------

.. _class_PointGeometry_method_GetPoint:

- :ref:`Vector3<class_Vector3>` **GetPoint** **(** **)**

获取点的坐标

----

.. _class_PointGeometry_method_HitTest:

- :ref:`Vector3<class_Vector3>` **HitTest** **(** :ref:`Vector3<class_Vector3>` latlon, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)**

选中检测，当latlon离点的像素距离小于15，则表示选中

----

