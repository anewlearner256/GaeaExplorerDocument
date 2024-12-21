.. _class_DrawLineTool:

DrawLineTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制线工具

示例
----

属性
----

+-------------------------------------------------------+-----------------------------------------------------+
| :ref:`LineGeometryElement<class_LineGeometryElement>` | :ref:`Element<class_DrawLineTool_property_Element>` |
+-------------------------------------------------------+-----------------------------------------------------+

方法
----

+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>` | :ref:`GetLine<class_DrawLineTool_method_GetLine>` **(** **)**                                                                                              |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Ready<class_DrawLineTool_method__Ready>` **(** **)**                                                                                                |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseDown<class_DrawLineTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseMove<class_DrawLineTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Process<class_DrawLineTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                          |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`     | :ref:`OnMouseDoubleClick<class_DrawLineTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawLineTool_property_Element:

- :ref:`LineGeometryElement<class_LineGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线Element

----


方法说明
-------

.. _class_DrawLineTool_method_GetLine:

- :ref:`Vector3[]<class_Vector3[]>` **GetLine** **(** **)**

获取线上点的坐标

----

.. _class_DrawLineTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_DrawLineTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_DrawLineTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_DrawLineTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

.. _class_DrawLineTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标双击事件。

----

