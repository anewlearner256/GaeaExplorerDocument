.. _class_MeasureHeightTool:

MeasureHeightTool 
===================

**Inherits:** :ref:`MeasureTool<class_MeasureTool>` **<** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

测量高度工具

示例
----

属性
----

+-------------------------------------------------------------+----------------------------------------------------------+
| :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` | :ref:`Element<class_MeasureHeightTool_property_Element>` |
+-------------------------------------------------------------+----------------------------------------------------------+

方法
----

+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Ready<class_MeasureHeightTool_method__Ready>` **(** **)**                                                                                       |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseDown<class_MeasureHeightTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**      |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseMove<class_MeasureHeightTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**      |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Process<class_MeasureHeightTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                 |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>` | :ref:`LocalToWorld<class_MeasureHeightTool_method_LocalToWorld>` **(** :ref:`Vector3<class_Vector3>` pos, :ref:`Vector3[]<class_Vector3[]>` line **)** |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`       | :ref:`Convert<class_MeasureHeightTool_method_Convert>` **(** :ref:`Single<class_Single>` total **)**                                                   |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_MeasureHeightTool_property_Element:

- :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_MeasureHeightTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_MeasureHeightTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_MeasureHeightTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_MeasureHeightTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

.. _class_MeasureHeightTool_method_LocalToWorld:

- :ref:`Vector3[]<class_Vector3[]>` **LocalToWorld** **(** :ref:`Vector3<class_Vector3>` pos, :ref:`Vector3[]<class_Vector3[]>` line **)**

局部转全局

----

.. _class_MeasureHeightTool_method_Convert:

- :ref:`String<class_String>` **Convert** **(** :ref:`Single<class_Single>` total **)**

距离转换。当总距离超过1千米时，单位用公里

----

