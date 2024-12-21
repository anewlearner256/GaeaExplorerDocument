.. _class_MeasureAreaPolygonTool:

MeasureAreaPolygonTool 
===================

**Inherits:** :ref:`MeasureTool<class_MeasureTool>` **<** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

测量面积工具

示例
----

属性
----

+-------------------------------------------------------------+---------------------------------------------------------------+
| :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` | :ref:`Element<class_MeasureAreaPolygonTool_property_Element>` |
+-------------------------------------------------------------+---------------------------------------------------------------+

方法
----

+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Ready<class_MeasureAreaPolygonTool_method__Ready>` **(** **)**                                                                                                |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseDown<class_MeasureAreaPolygonTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseDoubleClick<class_MeasureAreaPolygonTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseMove<class_MeasureAreaPolygonTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Process<class_MeasureAreaPolygonTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                          |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`UnitConversion<class_MeasureAreaPolygonTool_method_UnitConversion>` **(** :ref:`Single<class_Single>` total, :ref:`Label<class_Label>` label **)**             |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_MeasureAreaPolygonTool_property_Element:

- :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面要素Element

----


方法说明
-------

.. _class_MeasureAreaPolygonTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_MeasureAreaPolygonTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_MeasureAreaPolygonTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标双击事件。

----

.. _class_MeasureAreaPolygonTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_MeasureAreaPolygonTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

.. _class_MeasureAreaPolygonTool_method_UnitConversion:

- :ref:`Void<class_Void>` **UnitConversion** **(** :ref:`Single<class_Single>` total, :ref:`Label<class_Label>` label **)**

将计算出的多边形面积转换为适合显示的单位

----

