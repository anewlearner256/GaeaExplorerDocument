.. _class_VisualAnalysisTool:

VisualAnalysisTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制线工具

示例
----

属性
----

+-------------------------------------------------------+-----------------------------------------------------------------------------------+
| :ref:`LineGeometryElement<class_LineGeometryElement>` | :ref:`VisibleElement<class_VisualAnalysisTool_property_VisibleElement>`           |
+-------------------------------------------------------+-----------------------------------------------------------------------------------+
| :ref:`LineGeometryElement<class_LineGeometryElement>` | :ref:`InVisibleElement<class_VisualAnalysisTool_property_InVisibleElement>`       |
+-------------------------------------------------------+-----------------------------------------------------------------------------------+
| :ref:`LineGeometryElement<class_LineGeometryElement>` | :ref:`DotVisibleElement<class_VisualAnalysisTool_property_DotVisibleElement>`     |
+-------------------------------------------------------+-----------------------------------------------------------------------------------+
| :ref:`LineGeometryElement<class_LineGeometryElement>` | :ref:`DotInVisibleElement<class_VisualAnalysisTool_property_DotInVisibleElement>` |
+-------------------------------------------------------+-----------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                           | :ref:`DeafaultHeight<class_VisualAnalysisTool_property_DeafaultHeight>`           |
+-------------------------------------------------------+-----------------------------------------------------------------------------------+

方法
----

+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Process<class_VisualAnalysisTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                          |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseDown<class_VisualAnalysisTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseMove<class_VisualAnalysisTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseDoubleClick<class_VisualAnalysisTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`   | :ref:`GetLocalLine<class_VisualAnalysisTool_method_GetLocalLine>` **(** **)**                                                                                    |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`   | :ref:`GetResultLine<class_VisualAnalysisTool_method_GetResultLine>` **(** **)**                                                                                  |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Ready<class_VisualAnalysisTool_method__Ready>` **(** **)**                                                                                                |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_VisualAnalysisTool_property_VisibleElement:

- :ref:`LineGeometryElement<class_LineGeometryElement>` **VisibleElement**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

可见线Element

----

.. _class_VisualAnalysisTool_property_InVisibleElement:

- :ref:`LineGeometryElement<class_LineGeometryElement>` **InVisibleElement**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

不可见线Element

----

.. _class_VisualAnalysisTool_property_DotVisibleElement:

- :ref:`LineGeometryElement<class_LineGeometryElement>` **DotVisibleElement**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

可见虚线Element

----

.. _class_VisualAnalysisTool_property_DotInVisibleElement:

- :ref:`LineGeometryElement<class_LineGeometryElement>` **DotInVisibleElement**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

不可见虚线Element

----

.. _class_VisualAnalysisTool_property_DeafaultHeight:

- :ref:`Single<class_Single>` **DeafaultHeight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_VisualAnalysisTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**



----

.. _class_VisualAnalysisTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**



----

.. _class_VisualAnalysisTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_VisualAnalysisTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标双击事件。

----

.. _class_VisualAnalysisTool_method_GetLocalLine:

- :ref:`List`1<class_List`1>` **GetLocalLine** **(** **)**

获取原始线上点的坐标

----

.. _class_VisualAnalysisTool_method_GetResultLine:

- :ref:`List`1<class_List`1>` **GetResultLine** **(** **)**

获取结果线上点的坐标

----

.. _class_VisualAnalysisTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

