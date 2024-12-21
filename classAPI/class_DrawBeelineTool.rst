.. _class_DrawBeelineTool:

DrawBeelineTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制直线工具

示例
----

属性
----

+-------------------------------------------------------+--------------------------------------------------------+
| :ref:`LineGeometryElement<class_LineGeometryElement>` | :ref:`Element<class_DrawBeelineTool_property_Element>` |
+-------------------------------------------------------+--------------------------------------------------------+

方法
----

+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>` | :ref:`GetBeeline<class_DrawBeelineTool_method_GetBeeline>` **(** **)**                                                                                        |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Ready<class_DrawBeelineTool_method__Ready>` **(** **)**                                                                                                |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseDown<class_DrawBeelineTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseMove<class_DrawBeelineTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Process<class_DrawBeelineTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                          |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`     | :ref:`OnMouseDoubleClick<class_DrawBeelineTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawBeelineTool_property_Element:

- :ref:`LineGeometryElement<class_LineGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线Element对象

----


方法说明
-------

.. _class_DrawBeelineTool_method_GetBeeline:

- :ref:`Vector3[]<class_Vector3[]>` **GetBeeline** **(** **)**

获取直线点的坐标（纬经度）

----

.. _class_DrawBeelineTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_DrawBeelineTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_DrawBeelineTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_DrawBeelineTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

.. _class_DrawBeelineTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标双击事件。

----

