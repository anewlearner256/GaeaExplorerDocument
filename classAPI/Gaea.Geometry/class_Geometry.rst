.. _class_Geometry:

Geometry 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----

几何类

示例
----

属性
----

+---------------------------------+-------------------------------------------------------+
| :ref:`Int32<class_Int32>`       | :ref:`ID<class_Geometry_property_ID>`                 |
+---------------------------------+-------------------------------------------------------+
| :ref:`Envelope<class_Envelope>` | :ref:`Extent<class_Geometry_property_Extent>`         |
+---------------------------------+-------------------------------------------------------+
| :ref:`Int32<class_Int32>`       | :ref:`PointCount<class_Geometry_property_PointCount>` |
+---------------------------------+-------------------------------------------------------+
| :ref:`Int32<class_Int32>`       | :ref:`PartCount<class_Geometry_property_PartCount>`   |
+---------------------------------+-------------------------------------------------------+

方法
----

+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Geometry<class_Geometry>`     | :ref:`Create<class_Geometry_method_Create>` **(** :ref:`GeometryType<class_GeometryType>` geoType, :ref:`List`1<class_List`1>` datas **)**                                                                                                                                         |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Geometry<class_Geometry>`     | :ref:`Create<class_Geometry_method_Create>` **(** :ref:`GeometryType<class_GeometryType>` geoType, :ref:`Vector3[]<class_Vector3[]>` datas **)**                                                                                                                                   |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Geometry<class_Geometry>`     | :ref:`Add<class_Geometry_method_Add>` **(** :ref:`Geometry<class_Geometry>` geo, :ref:`List`1<class_List`1>` datas **)**                                                                                                                                                           |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Geometry<class_Geometry>`     | :ref:`Add<class_Geometry_method_Add>` **(** :ref:`Geometry<class_Geometry>` geo, :ref:`PolygonGeometry<class_PolygonGeometry>` polygon **)**                                                                                                                                       |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Geometry[]<class_Geometry[]>` | :ref:`Cut<class_Geometry_method_Cut>` **(** :ref:`Geometry<class_Geometry>` geo, :ref:`Vector3<class_Vector3>` segmentA, :ref:`Vector3<class_Vector3>` segmentB **)**                                                                                                              |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Geometry<class_Geometry>`     | :ref:`LinesMergeIntoPolygon<class_Geometry_method_LinesMergeIntoPolygon>` **(** :ref:`Geometry[]<class_Geometry[]>` geometrys **)**                                                                                                                                                |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Geometry<class_Geometry>`     | :ref:`GeometryInterpolate<class_Geometry_method_GeometryInterpolate>` **(** :ref:`Geometry<class_Geometry>` geometry, :ref:`CurveMode<class_CurveMode>` mode, :ref:`Vector3[]<class_Vector3[]>` Vexs, :ref:`Int32<class_Int32>` coeff, :ref:`Double<class_Double>` deviation **)** |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`         | :ref:`Clip<class_Geometry_method_Clip>` **(** :ref:`Vector3<class_Vector3>` line **)**                                                                                                                                                                                             |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`       | :ref:`HitTest<class_Geometry_method_HitTest>` **(** :ref:`Vector3<class_Vector3>` ray, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)**                                                                                                        |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`       | :ref:`Contains<class_Geometry_method_Contains>` **(** :ref:`Geometry<class_Geometry>` geo **)**                                                                                                                                                                                    |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`       | :ref:`Crosses<class_Geometry_method_Crosses>` **(** :ref:`Geometry<class_Geometry>` geo **)**                                                                                                                                                                                      |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`         | :ref:`DistanceTo<class_Geometry_method_DistanceTo>` **(** :ref:`Geometry<class_Geometry>` geo **)**                                                                                                                                                                                |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`         | :ref:`Area<class_Geometry_method_Area>` **(** **)**                                                                                                                                                                                                                                |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`         | :ref:`Length<class_Geometry_method_Length>` **(** **)**                                                                                                                                                                                                                            |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`         | :ref:`Scale<class_Geometry_method_Scale>` **(** :ref:`Geometry<class_Geometry>` geo, :ref:`Double<class_Double>` ScaleValue **)**                                                                                                                                                  |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`       | :ref:`IsClockwise<class_Geometry_method_IsClockwise>` **(** **)**                                                                                                                                                                                                                  |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`       | :ref:`QueryPoint<class_Geometry_method_QueryPoint>` **(** :ref:`Double<class_Double>` DistanceAlongCurve, :ref:`Boolean<class_Boolean>` asRatio **)**                                                                                                                              |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`         | :ref:`GetOriginData<class_Geometry_method_GetOriginData>` **(** **)**                                                                                                                                                                                                              |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`         | :ref:`GetLocalData<class_Geometry_method_GetLocalData>` **(** :ref:`Transform<class_Transform>` trans, :ref:`Single<class_Single>` heightOffset, :ref:`Int32<class_Int32>` level **)**                                                                                             |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`         | :ref:`GetGlobeData<class_Geometry_method_GetGlobeData>` **(** **)**                                                                                                                                                                                                                |
+-------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Geometry_property_ID:

- :ref:`Int32<class_Int32>` **ID**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

几何形状的ID

----

.. _class_Geometry_property_Extent:

- :ref:`Envelope<class_Envelope>` **Extent**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

几何的外包络线

----

.. _class_Geometry_property_PointCount:

- :ref:`Int32<class_Int32>` **PointCount**

+----------+---+
| *Getter* |   |
+----------+---+

单个几何的点数

----

.. _class_Geometry_property_PartCount:

- :ref:`Int32<class_Int32>` **PartCount**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_Geometry_method_Create:

- :ref:`Geometry<class_Geometry>` **Create** **(** :ref:`GeometryType<class_GeometryType>` geoType, :ref:`List`1<class_List`1>` datas **)**

根据数据类型创建不同的要素

----

.. _class_Geometry_method_Create:

- :ref:`Geometry<class_Geometry>` **Create** **(** :ref:`GeometryType<class_GeometryType>` geoType, :ref:`Vector3[]<class_Vector3[]>` datas **)**

根据数据类型创建不同的要素

----

.. _class_Geometry_method_Add:

- :ref:`Geometry<class_Geometry>` **Add** **(** :ref:`Geometry<class_Geometry>` geo, :ref:`List`1<class_List`1>` datas **)**

合并数据

----

.. _class_Geometry_method_Add:

- :ref:`Geometry<class_Geometry>` **Add** **(** :ref:`Geometry<class_Geometry>` geo, :ref:`PolygonGeometry<class_PolygonGeometry>` polygon **)**



----

.. _class_Geometry_method_Cut:

- :ref:`Geometry[]<class_Geometry[]>` **Cut** **(** :ref:`Geometry<class_Geometry>` geo, :ref:`Vector3<class_Vector3>` segmentA, :ref:`Vector3<class_Vector3>` segmentB **)**

使用线段，对线和面Geometry进行分割
tips: 0. 数据类型为经纬度加高度
      1. 线段和多边形的某边存在时重合时，分割失败
      2. 线段和多边形有且仅有两个交点，否则分割失败
      3. 分割失败返回一个空数组

----

.. _class_Geometry_method_LinesMergeIntoPolygon:

- :ref:`Geometry<class_Geometry>` **LinesMergeIntoPolygon** **(** :ref:`Geometry[]<class_Geometry[]>` geometrys **)**

将线段合并成多边形（前提是线段可以组合成多边形）

----

.. _class_Geometry_method_GeometryInterpolate:

- :ref:`Geometry<class_Geometry>` **GeometryInterpolate** **(** :ref:`Geometry<class_Geometry>` geometry, :ref:`CurveMode<class_CurveMode>` mode, :ref:`Vector3[]<class_Vector3[]>` Vexs, :ref:`Int32<class_Int32>` coeff, :ref:`Double<class_Double>` deviation **)**

对 Geometry 进行插值，顶点必须是有序的，且不存在分支、不连贯等情况

----

.. _class_Geometry_method_Clip:

- :ref:`List`1<class_List`1>` **Clip** **(** :ref:`Vector3<class_Vector3>` line **)**

裁切

----

.. _class_Geometry_method_HitTest:

- :ref:`Vector3<class_Vector3>` **HitTest** **(** :ref:`Vector3<class_Vector3>` ray, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)**

选中检测

----

.. _class_Geometry_method_Contains:

- :ref:`Boolean<class_Boolean>` **Contains** **(** :ref:`Geometry<class_Geometry>` geo **)**

包含关系。当前几何要素是否包含geo

----

.. _class_Geometry_method_Crosses:

- :ref:`Boolean<class_Boolean>` **Crosses** **(** :ref:`Geometry<class_Geometry>` geo **)**

碰撞关系。当前几何要素是否与geo碰撞

----

.. _class_Geometry_method_DistanceTo:

- :ref:`Double<class_Double>` **DistanceTo** **(** :ref:`Geometry<class_Geometry>` geo **)**

距离。

----

.. _class_Geometry_method_Area:

- :ref:`Double<class_Double>` **Area** **(** **)**

当前要素的面积

----

.. _class_Geometry_method_Length:

- :ref:`Double<class_Double>` **Length** **(** **)**

当前要素的长度

----

.. _class_Geometry_method_Scale:

- :ref:`List`1<class_List`1>` **Scale** **(** :ref:`Geometry<class_Geometry>` geo, :ref:`Double<class_Double>` ScaleValue **)**

将给定的几何图形缩放到指定的比例。

----

.. _class_Geometry_method_IsClockwise:

- :ref:`Boolean<class_Boolean>` **IsClockwise** **(** **)**

要素是否是顺时针

----

.. _class_Geometry_method_QueryPoint:

- :ref:`Vector3<class_Vector3>` **QueryPoint** **(** :ref:`Double<class_Double>` DistanceAlongCurve, :ref:`Boolean<class_Boolean>` asRatio **)**

查询给定距离处的三维向量。

----

.. _class_Geometry_method_GetOriginData:

- :ref:`List`1<class_List`1>` **GetOriginData** **(** **)**

获取要素的源数据

----

.. _class_Geometry_method_GetLocalData:

- :ref:`List`1<class_List`1>` **GetLocalData** **(** :ref:`Transform<class_Transform>` trans, :ref:`Single<class_Single>` heightOffset, :ref:`Int32<class_Int32>` level **)**

获取在局部坐标系下的笛卡尔坐标，并将这些数据转换为三维向量列表。

----

.. _class_Geometry_method_GetGlobeData:

- :ref:`List`1<class_List`1>` **GetGlobeData** **(** **)**

获取在全球坐标系下的笛卡尔坐标，并将这些数据转换为三维向量列表。

----

