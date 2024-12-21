.. _class_MeasureAzimuthTool:

MeasureAzimuthTool 
===================

**Inherits:** :ref:`MeasureTool<class_MeasureTool>` **<** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

测量方位角工具

示例
----

属性
----

+-------------------------------------------------------+-----------------------------------------------------------+
| :ref:`LineGeometryElement<class_LineGeometryElement>` | :ref:`Element<class_MeasureAzimuthTool_property_Element>` |
+-------------------------------------------------------+-----------------------------------------------------------+

方法
----

+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Ready<class_MeasureAzimuthTool_method__Ready>` **(** **)**                                                                                  |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnMouseDown<class_MeasureAzimuthTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnMouseMove<class_MeasureAzimuthTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Process<class_MeasureAzimuthTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                            |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_MeasureAzimuthTool_property_Element:

- :ref:`LineGeometryElement<class_LineGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_MeasureAzimuthTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_MeasureAzimuthTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_MeasureAzimuthTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_MeasureAzimuthTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

