.. _class_Envelope:

Envelope 
===================

**Inherits:** :ref:`ValueType<class_ValueType>` **<** :ref:`Object<class_Object>` **<** :ref:`Object<class_Object>`

描述
----

也称为包络线，是一个矩形区域，它定义了一个要素（feature）的空间范围，是每个几何体的最小外接矩形。所有的几何对象都有Envelope属性。
Also known as the envelope, it is a rectangular area that defines the spatial extent of a feature and is the smallest circumscribed rectangle for each geometry. All geometric objects have an Envelope property.

示例
----

属性
----

+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`XMin<class_Envelope_property_XMin>`                 |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`XMax<class_Envelope_property_XMax>`                 |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`YMin<class_Envelope_property_YMin>`                 |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`YMax<class_Envelope_property_YMax>`                 |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`ZMin<class_Envelope_property_ZMin>`                 |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`ZMax<class_Envelope_property_ZMax>`                 |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`MMin<class_Envelope_property_MMin>`                 |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`MMax<class_Envelope_property_MMax>`                 |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`gaeaGeometryType<class_gaeaGeometryType>` | :ref:`GeometryType<class_Envelope_property_GeometryType>` |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                   | :ref:`IsEmpty<class_Envelope_property_IsEmpty>`           |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`Depth<class_Envelope_property_Depth>`               |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`Height<class_Envelope_property_Height>`             |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`                   | :ref:`LowerLeft<class_Envelope_property_LowerLeft>`       |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`                   | :ref:`LowerRight<class_Envelope_property_LowerRight>`     |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`                   | :ref:`UpperLeft<class_Envelope_property_UpperLeft>`       |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`                   | :ref:`UpperRight<class_Envelope_property_UpperRight>`     |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Double<class_Double>`                     | :ref:`Width<class_Envelope_property_Width>`               |
+-------------------------------------------------+-----------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`                   | :ref:`Center<class_Envelope_property_Center>`             |
+-------------------------------------------------+-----------------------------------------------------------+

方法
----

+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`SetEmpty<class_Envelope_method_SetEmpty>` **(** **)**                                                                                                                                          |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`GeoNormalize<class_Envelope_method_GeoNormalize>` **(** **)**                                                                                                                                  |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`GeoNormalizeFromLongitude<class_Envelope_method_GeoNormalizeFromLongitude>` **(** :ref:`Double<class_Double>` Longitude **)**                                                                  |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`SnapToSpatialReference<class_Envelope_method_SnapToSpatialReference>` **(** **)**                                                                                                              |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`Refresh<class_Envelope_method_Refresh>` **(** **)**                                                                                                                                            |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`Dispose<class_Envelope_method_Dispose>` **(** **)**                                                                                                                                            |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`Expand<class_Envelope_method_Expand>` **(** :ref:`Double<class_Double>` dx, :ref:`Double<class_Double>` dy, :ref:`Boolean<class_Boolean>` asRatio **)**                                        |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Envelope<class_Envelope>` | :ref:`Expand<class_Envelope_method_Expand>` **(** :ref:`Envelope<class_Envelope>` envelope **)**                                                                                                     |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`ExpandM<class_Envelope_method_ExpandM>` **(** :ref:`Double<class_Double>` dm, :ref:`Boolean<class_Boolean>` asRatio **)**                                                                      |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`ExpandZ<class_Envelope_method_ExpandZ>` **(** :ref:`Double<class_Double>` dz, :ref:`Boolean<class_Boolean>` asRatio **)**                                                                      |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`   | :ref:`Contain<class_Envelope_method_Contain>` **(** :ref:`Envelope<class_Envelope>` inEnvelope **)**                                                                                                 |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`Intersect<class_Envelope_method_Intersect>` **(** :ref:`Envelope<class_Envelope>` inEnvelope **)**                                                                                             |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`Offset<class_Envelope_method_Offset>` **(** :ref:`Double<class_Double>` X, :ref:`Double<class_Double>` Y **)**                                                                                 |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`OffsetM<class_Envelope_method_OffsetM>` **(** :ref:`Double<class_Double>` M **)**                                                                                                              |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`OffsetZ<class_Envelope_method_OffsetZ>` **(** :ref:`Double<class_Double>` Z **)**                                                                                                              |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`PutCoords<class_Envelope_method_PutCoords>` **(** :ref:`Double<class_Double>` XMin, :ref:`Double<class_Double>` YMin, :ref:`Double<class_Double>` XMax, :ref:`Double<class_Double>` YMax **)** |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`         | :ref:`Union<class_Envelope_method_Union>` **(** :ref:`Envelope<class_Envelope>` inEnvelope **)**                                                                                                     |
+---------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Envelope_property_XMin:

- :ref:`Double<class_Double>` **XMin**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

几何形状的外接矩形的X最小值

----

.. _class_Envelope_property_XMax:

- :ref:`Double<class_Double>` **XMax**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

几何形状的外接矩形的X最大值

----

.. _class_Envelope_property_YMin:

- :ref:`Double<class_Double>` **YMin**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

几何形状的外接矩形的Y最小值

----

.. _class_Envelope_property_YMax:

- :ref:`Double<class_Double>` **YMax**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

几何形状的外接矩形的Y最大值

----

.. _class_Envelope_property_ZMin:

- :ref:`Double<class_Double>` **ZMin**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_Envelope_property_ZMax:

- :ref:`Double<class_Double>` **ZMax**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_Envelope_property_MMin:

- :ref:`Double<class_Double>` **MMin**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_Envelope_property_MMax:

- :ref:`Double<class_Double>` **MMax**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_Envelope_property_GeometryType:

- :ref:`gaeaGeometryType<class_gaeaGeometryType>` **GeometryType**

+----------+---+
| *Getter* |   |
+----------+---+

获取工作区中要素的几何类型。即工作区中要素的几何类型为边界框（envelope）。

----

.. _class_Envelope_property_IsEmpty:

- :ref:`Boolean<class_Boolean>` **IsEmpty**

+----------+---+
| *Getter* |   |
+----------+---+

是否为空

----

.. _class_Envelope_property_Depth:

- :ref:`Double<class_Double>` **Depth**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

获取或设置曲线的深度

----

.. _class_Envelope_property_Height:

- :ref:`Double<class_Double>` **Height**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

获取或设置曲线的的高度。

----

.. _class_Envelope_property_LowerLeft:

- :ref:`Vector2<class_Vector2>` **LowerLeft**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

左下角点

----

.. _class_Envelope_property_LowerRight:

- :ref:`Vector2<class_Vector2>` **LowerRight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

右下角点

----

.. _class_Envelope_property_UpperLeft:

- :ref:`Vector2<class_Vector2>` **UpperLeft**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

左上角点

----

.. _class_Envelope_property_UpperRight:

- :ref:`Vector2<class_Vector2>` **UpperRight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

右上角点

----

.. _class_Envelope_property_Width:

- :ref:`Double<class_Double>` **Width**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

外包矩形的宽度

----

.. _class_Envelope_property_Center:

- :ref:`Vector2<class_Vector2>` **Center**

+----------+---+
| *Getter* |   |
+----------+---+

外包矩形的中心点

----


方法说明
-------

.. _class_Envelope_method_SetEmpty:

- :ref:`Void<class_Void>` **SetEmpty** **(** **)**

未知

----

.. _class_Envelope_method_GeoNormalize:

- :ref:`Void<class_Void>` **GeoNormalize** **(** **)**

未知

----

.. _class_Envelope_method_GeoNormalizeFromLongitude:

- :ref:`Void<class_Void>` **GeoNormalizeFromLongitude** **(** :ref:`Double<class_Double>` Longitude **)**

未知

----

.. _class_Envelope_method_SnapToSpatialReference:

- :ref:`Void<class_Void>` **SnapToSpatialReference** **(** **)**

未知

----

.. _class_Envelope_method_Refresh:

- :ref:`Void<class_Void>` **Refresh** **(** **)**

未知

----

.. _class_Envelope_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**

释放当前对象所占的空间

----

.. _class_Envelope_method_Expand:

- :ref:`Void<class_Void>` **Expand** **(** :ref:`Double<class_Double>` dx, :ref:`Double<class_Double>` dy, :ref:`Boolean<class_Boolean>` asRatio **)**

根据给定的参数来扩展一个矩形的边界。

----

.. _class_Envelope_method_Expand:

- :ref:`Envelope<class_Envelope>` **Expand** **(** :ref:`Envelope<class_Envelope>` envelope **)**

外包矩形的扩展。计算出包含当前矩形和envelope的外包矩形。

----

.. _class_Envelope_method_ExpandM:

- :ref:`Void<class_Void>` **ExpandM** **(** :ref:`Double<class_Double>` dm, :ref:`Boolean<class_Boolean>` asRatio **)**

根据给定的参数来扩展一个矩形的边界。暂未实现

----

.. _class_Envelope_method_ExpandZ:

- :ref:`Void<class_Void>` **ExpandZ** **(** :ref:`Double<class_Double>` dz, :ref:`Boolean<class_Boolean>` asRatio **)**

根据给定的参数来扩展一个矩形的边界。暂未实现

----

.. _class_Envelope_method_Contain:

- :ref:`Boolean<class_Boolean>` **Contain** **(** :ref:`Envelope<class_Envelope>` inEnvelope **)**

包含关系。当前外包矩形是否包含inEnvelope
contain.

----

.. _class_Envelope_method_Intersect:

- :ref:`Void<class_Void>` **Intersect** **(** :ref:`Envelope<class_Envelope>` inEnvelope **)**

相交范围。当前矩形与inEnvelope的重合矩形
Intersection range.

----

.. _class_Envelope_method_Offset:

- :ref:`Void<class_Void>` **Offset** **(** :ref:`Double<class_Double>` X, :ref:`Double<class_Double>` Y **)**

据给定的参数来偏移一个矩形的中心位置。

----

.. _class_Envelope_method_OffsetM:

- :ref:`Void<class_Void>` **OffsetM** **(** :ref:`Double<class_Double>` M **)**

未知

----

.. _class_Envelope_method_OffsetZ:

- :ref:`Void<class_Void>` **OffsetZ** **(** :ref:`Double<class_Double>` Z **)**

未知

----

.. _class_Envelope_method_PutCoords:

- :ref:`Void<class_Void>` **PutCoords** **(** :ref:`Double<class_Double>` XMin, :ref:`Double<class_Double>` YMin, :ref:`Double<class_Double>` XMax, :ref:`Double<class_Double>` YMax **)**

设置矩形的范围

----

.. _class_Envelope_method_Union:

- :ref:`Void<class_Void>` **Union** **(** :ref:`Envelope<class_Envelope>` inEnvelope **)**

包含。将当前矩形范围与inEnvelope联合。

----

