.. _class_DrawViewshedTool:

DrawViewshedTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制可视域框

示例
----

属性
----

+-----------------------------------+---------------------------------------------------------------------------+
| :ref:`SpotLight<class_SpotLight>` | :ref:`_spotLight<class_DrawViewshedTool_property__spotLight>`             |
+-----------------------------------+---------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`StartPoint<class_DrawViewshedTool_property_StartPoint>`             |
+-----------------------------------+---------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`EndPoint<class_DrawViewshedTool_property_EndPoint>`                 |
+-----------------------------------+---------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`Angle<class_DrawViewshedTool_property_Angle>`                       |
+-----------------------------------+---------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`nowcenter<class_DrawViewshedTool_property_nowcenter>`               |
+-----------------------------------+---------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`nowboundary<class_DrawViewshedTool_property_nowboundary>`           |
+-----------------------------------+---------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`MeshHight<class_DrawViewshedTool_property_MeshHight>`               |
+-----------------------------------+---------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`HorizontalOffset<class_DrawViewshedTool_property_HorizontalOffset>` |
+-----------------------------------+---------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`VerticalOffset<class_DrawViewshedTool_property_VerticalOffset>`     |
+-----------------------------------+---------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`Size<class_DrawViewshedTool_property_Size>`                         |
+-----------------------------------+---------------------------------------------------------------------------+

方法
----

+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Ready<class_DrawViewshedTool_method__Ready>` **(** **)**                                                                                                                                                                           |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseDown<class_DrawViewshedTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**                                                                                          |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseMove<class_DrawViewshedTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**                                                                                          |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`RotateLineSegment<class_DrawViewshedTool_method_RotateLineSegment>` **(** :ref:`Vector3<class_Vector3>` startPoint, :ref:`Vector3<class_Vector3>` endPoint, :ref:`Vector3<class_Vector3>` up, :ref:`Double<class_Double>` rad **)** |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseDoubleClick<class_DrawViewshedTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**                                                                            |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Process<class_DrawViewshedTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                                                                                                     |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawViewshedTool_property__spotLight:

- :ref:`SpotLight<class_SpotLight>` **_spotLight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

聚光灯

----

.. _class_DrawViewshedTool_property_StartPoint:

- :ref:`Vector3<class_Vector3>` **StartPoint**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

起始点位

----

.. _class_DrawViewshedTool_property_EndPoint:

- :ref:`Vector3<class_Vector3>` **EndPoint**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

终止点位

----

.. _class_DrawViewshedTool_property_Angle:

- :ref:`Double<class_Double>` **Angle**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

夹角

----

.. _class_DrawViewshedTool_property_nowcenter:

- :ref:`Vector3<class_Vector3>` **nowcenter**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DrawViewshedTool_property_nowboundary:

- :ref:`Vector3<class_Vector3>` **nowboundary**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DrawViewshedTool_property_MeshHight:

- :ref:`Double<class_Double>` **MeshHight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

用于挤压可视范围的高度

----

.. _class_DrawViewshedTool_property_HorizontalOffset:

- :ref:`Double<class_Double>` **HorizontalOffset**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

水平偏移

----

.. _class_DrawViewshedTool_property_VerticalOffset:

- :ref:`Double<class_Double>` **VerticalOffset**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

垂直偏移

----

.. _class_DrawViewshedTool_property_Size:

- :ref:`Double<class_Double>` **Size**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

长度

----


方法说明
-------

.. _class_DrawViewshedTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_DrawViewshedTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件（绘制可视域框）

----

.. _class_DrawViewshedTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。（绘制可视域框）

----

.. _class_DrawViewshedTool_method_RotateLineSegment:

- :ref:`Vector3<class_Vector3>` **RotateLineSegment** **(** :ref:`Vector3<class_Vector3>` startPoint, :ref:`Vector3<class_Vector3>` endPoint, :ref:`Vector3<class_Vector3>` up, :ref:`Double<class_Double>` rad **)**



----

.. _class_DrawViewshedTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**



----

.. _class_DrawViewshedTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

