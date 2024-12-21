.. _class_DrawSquareTool:

DrawSquareTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制正方形工具

示例
----

属性
----

+-------------------------------------------------------------+-------------------------------------------------------+
| :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` | :ref:`Element<class_DrawSquareTool_property_Element>` |
+-------------------------------------------------------------+-------------------------------------------------------+

方法
----

+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>` | :ref:`GetLine<class_DrawSquareTool_method_GetLine>` **(** **)**                                                                                |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Ready<class_DrawSquareTool_method__Ready>` **(** **)**                                                                                  |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseDown<class_DrawSquareTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseMove<class_DrawSquareTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Process<class_DrawSquareTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                            |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>` | :ref:`GetPolygon<class_DrawSquareTool_method_GetPolygon>` **(** **)**                                                                          |
+-----------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawSquareTool_property_Element:

- :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_DrawSquareTool_method_GetLine:

- :ref:`Vector3[]<class_Vector3[]>` **GetLine** **(** **)**

获取正方形的顶点坐标（纬经度）。

----

.. _class_DrawSquareTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_DrawSquareTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_DrawSquareTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_DrawSquareTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

.. _class_DrawSquareTool_method_GetPolygon:

- :ref:`Vector3[]<class_Vector3[]>` **GetPolygon** **(** **)**

获取水平面点的顶点坐标（纬经度）。

----

