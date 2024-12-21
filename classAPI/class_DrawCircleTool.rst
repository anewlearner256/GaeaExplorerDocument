.. _class_DrawCircleTool:

DrawCircleTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制圆工具

示例
----

属性
----

+-------------------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                                   | :ref:`CircleVerticdsNumber<class_DrawCircleTool_property_CircleVerticdsNumber>` |
+-------------------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` | :ref:`Element<class_DrawCircleTool_property_Element>`                           |
+-------------------------------------------------------------+---------------------------------------------------------------------------------+

方法
----

+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>` | :ref:`GetCircle<class_DrawCircleTool_method_GetCircle>` **(** **)**                                                                            |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Ready<class_DrawCircleTool_method__Ready>` **(** **)**                                                                                  |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseDown<class_DrawCircleTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseMove<class_DrawCircleTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Process<class_DrawCircleTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                            |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawCircleTool_property_CircleVerticdsNumber:

- :ref:`Int32<class_Int32>` **CircleVerticdsNumber**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

圆的控制点数量，数值越大越接近圆，默认为36

----

.. _class_DrawCircleTool_property_Element:

- :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面Element要素

----


方法说明
-------

.. _class_DrawCircleTool_method_GetCircle:

- :ref:`Vector3[]<class_Vector3[]>` **GetCircle** **(** **)**

获取圆的控制点坐标（纬经度）

----

.. _class_DrawCircleTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_DrawCircleTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_DrawCircleTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_DrawCircleTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

