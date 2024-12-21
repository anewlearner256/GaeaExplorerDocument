.. _class_MultiPolygonGeometry:

MultiPolygonGeometry 
===================

**Inherits:** :ref:`Geometry<class_Geometry>` **<** :ref:`Object<class_Object>`

描述
----

多多边形要素类

示例
----

属性
----

+-------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`MegerPolygons<class_MultiPolygonGeometry_property_MegerPolygons>` |
+-------------------------------+-------------------------------------------------------------------------+

方法
----

+-------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`         | :ref:`GetRings<class_MultiPolygonGeometry_method_GetRings>` **(** **)**                                                                                                                                                                                        |
+-------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`         | :ref:`GetPolygons<class_MultiPolygonGeometry_method_GetPolygons>` **(** **)**                                                                                                                                                                                  |
+-------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`       | :ref:`HitTest<class_MultiPolygonGeometry_method_HitTest>` **(** :ref:`Vector3<class_Vector3>` ray, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)**                                                                        |
+-------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Geometry[]<class_Geometry[]>` | :ref:`DisassemblyMultiPolygon<class_MultiPolygonGeometry_method_DisassemblyMultiPolygon>` **(** **)**                                                                                                                                                          |
+-------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`             | :ref:`MultiGeometryInterpolate<class_MultiPolygonGeometry_method_MultiGeometryInterpolate>` **(** :ref:`CurveMode<class_CurveMode>` mode, :ref:`Vector3[]<class_Vector3[]>` Vexs, :ref:`Int32<class_Int32>` coeff, :ref:`Double<class_Double>` deviation **)** |
+-------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_MultiPolygonGeometry_property_MegerPolygons:

- :ref:`Boolean<class_Boolean>` **MegerPolygons**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_MultiPolygonGeometry_method_GetRings:

- :ref:`List`1<class_List`1>` **GetRings** **(** **)**

获取多多边形的线要素

----

.. _class_MultiPolygonGeometry_method_GetPolygons:

- :ref:`List`1<class_List`1>` **GetPolygons** **(** **)**

获取多多边形面要素

----

.. _class_MultiPolygonGeometry_method_HitTest:

- :ref:`Vector3<class_Vector3>` **HitTest** **(** :ref:`Vector3<class_Vector3>` ray, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)**



----

.. _class_MultiPolygonGeometry_method_DisassemblyMultiPolygon:

- :ref:`Geometry[]<class_Geometry[]>` **DisassemblyMultiPolygon** **(** **)**

将 multiPolygon 分解

----

.. _class_MultiPolygonGeometry_method_MultiGeometryInterpolate:

- :ref:`Void<class_Void>` **MultiGeometryInterpolate** **(** :ref:`CurveMode<class_CurveMode>` mode, :ref:`Vector3[]<class_Vector3[]>` Vexs, :ref:`Int32<class_Int32>` coeff, :ref:`Double<class_Double>` deviation **)**

关于 MultiGeometry 进行插值

----

