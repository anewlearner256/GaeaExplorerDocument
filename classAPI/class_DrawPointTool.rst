.. _class_DrawPointTool:

DrawPointTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制点工具

示例
----

属性
----

+---------------------------------------------------------+--------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                           | :ref:`Position<class_DrawPointTool_property_Position>` |
+---------------------------------------------------------+--------------------------------------------------------+
| :ref:`PointGeometryElement<class_PointGeometryElement>` | :ref:`Element<class_DrawPointTool_property_Element>`   |
+---------------------------------------------------------+--------------------------------------------------------+

方法
----

+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Ready<class_DrawPointTool_method__Ready>` **(** **)**                                                                                  |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnMouseDown<class_DrawPointTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnMouseMove<class_DrawPointTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Process<class_DrawPointTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                            |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawPointTool_property_Position:

- :ref:`Vector3<class_Vector3>` **Position**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

点的坐标

----

.. _class_DrawPointTool_property_Element:

- :ref:`PointGeometryElement<class_PointGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

点Element

----


方法说明
-------

.. _class_DrawPointTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_DrawPointTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_DrawPointTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_DrawPointTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

