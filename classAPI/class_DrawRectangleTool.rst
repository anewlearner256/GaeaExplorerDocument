.. _class_DrawRectangleTool:

DrawRectangleTool 
===================

**Inherits:** :ref:`BaseConvertVolumeTool<class_BaseConvertVolumeTool>` **<** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制矩形工具

示例
----

属性
----

+-------------------------------------------------------------+--------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>`                           | :ref:`VertexInLocalInteractive<class_DrawRectangleTool_property_VertexInLocalInteractive>` |
+-------------------------------------------------------------+--------------------------------------------------------------------------------------------+
| :ref:`RectangleVolumeElement<class_RectangleVolumeElement>` | :ref:`VolumeElementObjectRect<class_DrawRectangleTool_property_VolumeElementObjectRect>`   |
+-------------------------------------------------------------+--------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                                 | :ref:`OffsetWidth<class_DrawRectangleTool_property_OffsetWidth>`                           |
+-------------------------------------------------------------+--------------------------------------------------------------------------------------------+
| :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` | :ref:`nowElement<class_DrawRectangleTool_property_nowElement>`                             |
+-------------------------------------------------------------+--------------------------------------------------------------------------------------------+
| :ref:`Geometry<class_Geometry>`                             | :ref:`OffsetGeometry<class_DrawRectangleTool_property_OffsetGeometry>`                     |
+-------------------------------------------------------------+--------------------------------------------------------------------------------------------+

方法
----

+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Ready<class_DrawRectangleTool_method__Ready>` **(** **)**                                                                                                |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`   | :ref:`GetPolygon<class_DrawRectangleTool_method_GetPolygon>` **(** **)**                                                                                        |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseDown<class_DrawRectangleTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseMove<class_DrawRectangleTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseDoubleClick<class_DrawRectangleTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Process<class_DrawRectangleTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                          |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawRectangleTool_property_VertexInLocalInteractive:

- :ref:`Vector3[]<class_Vector3[]>` **VertexInLocalInteractive**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

用于绘制点集合

----

.. _class_DrawRectangleTool_property_VolumeElementObjectRect:

- :ref:`RectangleVolumeElement<class_RectangleVolumeElement>` **VolumeElementObjectRect**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

体对象

----

.. _class_DrawRectangleTool_property_OffsetWidth:

- :ref:`Double<class_Double>` **OffsetWidth**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

宽度设置

----

.. _class_DrawRectangleTool_property_nowElement:

- :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` **nowElement**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面要素

----

.. _class_DrawRectangleTool_property_OffsetGeometry:

- :ref:`Geometry<class_Geometry>` **OffsetGeometry**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

绘制点集合

----


方法说明
-------

.. _class_DrawRectangleTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_DrawRectangleTool_method_GetPolygon:

- :ref:`List`1<class_List`1>` **GetPolygon** **(** **)**

获取坐标

----

.. _class_DrawRectangleTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件（绘制矩形）

----

.. _class_DrawRectangleTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。（绘制矩形）

----

.. _class_DrawRectangleTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标双击事件

----

.. _class_DrawRectangleTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

