.. _class_DecalItem:

DecalItem 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`String<class_String>`                   | :ref:`TerrainMapPath<class_DecalItem_property_TerrainMapPath>`           |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`String<class_String>`                   | :ref:`BaseMapPath<class_DecalItem_property_BaseMapPath>`                 |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`String<class_String>`                   | :ref:`DetailMapPath<class_DecalItem_property_DetailMapPath>`             |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`String<class_String>`                   | :ref:`DetailMaskPath<class_DecalItem_property_DetailMaskPath>`           |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`DetailScale<class_DecalItem_property_DetailScale>`                 |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`BaseScale<class_DecalItem_property_BaseScale>`                     |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`MeshInstance<class_MeshInstance>`       | :ref:`renderBox<class_DecalItem_property_renderBox>`                     |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`                 | :ref:`TerrainMap<class_DecalItem_property_TerrainMap>`                   |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`                 | :ref:`BaseMap<class_DecalItem_property_BaseMap>`                         |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                     | :ref:`BaseMapInvalidColor<class_DecalItem_property_BaseMapInvalidColor>` |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`TerrainInvalidValue<class_DecalItem_property_TerrainInvalidValue>` |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`                 | :ref:`DetailMap<class_DecalItem_property_DetailMap>`                     |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`                 | :ref:`DetailMaskMap<class_DecalItem_property_DetailMaskMap>`             |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`                 | :ref:`TerrainMinMaxValue<class_DecalItem_property_TerrainMinMaxValue>`   |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`BaseMapTypeEnum<class_BaseMapTypeEnum>` | :ref:`BaseMapType<class_DecalItem_property_BaseMapType>`                 |
+-----------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                 | :ref:`IsOverlay<class_DecalItem_property_IsOverlay>`                     |
+-----------------------------------------------+--------------------------------------------------------------------------+

方法
----

+-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Transform<class_Transform>` | :ref:`GetMatWorldToLocal<class_DecalItem_method_GetMatWorldToLocal>` **(** :ref:`Vector3<class_Vector3>` right, :ref:`Vector3<class_Vector3>` up, :ref:`Vector3<class_Vector3>` view **)**    |
+-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`ChangeRange<class_DecalItem_method_ChangeRange>` **(** :ref:`Double<class_Double>` n, :ref:`Double<class_Double>` s, :ref:`Double<class_Double>` w, :ref:`Double<class_Double>` e **)** |
+-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DecalItem_property_TerrainMapPath:

- :ref:`String<class_String>` **TerrainMapPath**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

地形贴花所用图片的路径

----

.. _class_DecalItem_property_BaseMapPath:

- :ref:`String<class_String>` **BaseMapPath**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

影像贴花所用图片的路径

----

.. _class_DecalItem_property_DetailMapPath:

- :ref:`String<class_String>` **DetailMapPath**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

细节贴花所用图片的路径

----

.. _class_DecalItem_property_DetailMaskPath:

- :ref:`String<class_String>` **DetailMaskPath**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

细节遮罩贴花所用图片的路径

----

.. _class_DecalItem_property_DetailScale:

- :ref:`Single<class_Single>` **DetailScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

细节贴花的缩放系数

----

.. _class_DecalItem_property_BaseScale:

- :ref:`Single<class_Single>` **BaseScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

基础影像贴花的缩放系数

----

.. _class_DecalItem_property_renderBox:

- :ref:`MeshInstance<class_MeshInstance>` **renderBox**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

屏幕空间贴花所用的渲染盒

----

.. _class_DecalItem_property_TerrainMap:

- :ref:`Texture<class_Texture>` **TerrainMap**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

地形贴花纹理

----

.. _class_DecalItem_property_BaseMap:

- :ref:`Texture<class_Texture>` **BaseMap**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

影像贴花纹理

----

.. _class_DecalItem_property_BaseMapInvalidColor:

- :ref:`Color<class_Color>` **BaseMapInvalidColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

指定影像贴花中的无效颜色，贴花中对应的像素不会被显示

----

.. _class_DecalItem_property_TerrainInvalidValue:

- :ref:`Single<class_Single>` **TerrainInvalidValue**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

地形的无效值，表示对应位置没有地形数据

----

.. _class_DecalItem_property_DetailMap:

- :ref:`Texture<class_Texture>` **DetailMap**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

细节贴花纹理

----

.. _class_DecalItem_property_DetailMaskMap:

- :ref:`Texture<class_Texture>` **DetailMaskMap**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

细节遮罩贴花纹理

----

.. _class_DecalItem_property_TerrainMinMaxValue:

- :ref:`Vector2<class_Vector2>` **TerrainMinMaxValue**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

地形贴花的最小值和最大值

----

.. _class_DecalItem_property_BaseMapType:

- :ref:`BaseMapTypeEnum<class_BaseMapTypeEnum>` **BaseMapType**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

贴花图片类型，影像或者色带

----

.. _class_DecalItem_property_IsOverlay:

- :ref:`Boolean<class_Boolean>` **IsOverlay**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

色带采样覆盖模式

----


方法说明
-------

.. _class_DecalItem_method_GetMatWorldToLocal:

- :ref:`Transform<class_Transform>` **GetMatWorldToLocal** **(** :ref:`Vector3<class_Vector3>` right, :ref:`Vector3<class_Vector3>` up, :ref:`Vector3<class_Vector3>` view **)**

计算世界坐标系转换到局部坐标系的矩阵

----

.. _class_DecalItem_method_ChangeRange:

- :ref:`Void<class_Void>` **ChangeRange** **(** :ref:`Double<class_Double>` n, :ref:`Double<class_Double>` s, :ref:`Double<class_Double>` w, :ref:`Double<class_Double>` e **)**

改变贴花区域

----

