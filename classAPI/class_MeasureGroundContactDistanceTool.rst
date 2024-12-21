.. _class_MeasureGroundContactDistanceTool:

MeasureGroundContactDistanceTool 
===================

**Inherits:** :ref:`MeasureTool<class_MeasureTool>` **<** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

测量贴地距离工具

示例
----

属性
----

+-------------------------------------------------------+-------------------------------------------------------------------------+
| :ref:`LineGeometryElement<class_LineGeometryElement>` | :ref:`Element<class_MeasureGroundContactDistanceTool_property_Element>` |
+-------------------------------------------------------+-------------------------------------------------------------------------+

方法
----

+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Ready<class_MeasureGroundContactDistanceTool_method__Ready>` **(** **)**                                                                                                |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseDoubleClick<class_MeasureGroundContactDistanceTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseDown<class_MeasureGroundContactDistanceTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseMove<class_MeasureGroundContactDistanceTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Process<class_MeasureGroundContactDistanceTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                          |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`Convert<class_MeasureGroundContactDistanceTool_method_Convert>` **(** :ref:`Single<class_Single>` total **)**                                                            |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_MeasureGroundContactDistanceTool_property_Element:

- :ref:`LineGeometryElement<class_LineGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_MeasureGroundContactDistanceTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_MeasureGroundContactDistanceTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标双击事件。

----

.. _class_MeasureGroundContactDistanceTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_MeasureGroundContactDistanceTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_MeasureGroundContactDistanceTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

.. _class_MeasureGroundContactDistanceTool_method_Convert:

- :ref:`String<class_String>` **Convert** **(** :ref:`Single<class_Single>` total **)**

距离转换。当总距离超过1千米时，单位用公里

----

