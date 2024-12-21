.. _class_RiverEditTool:

RiverEditTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

河道编辑工具

示例
----

属性
----

+-------------------------------------------------------------+--------------------------------------------------------------------------+
| :ref:`RiverEditOperateOption<class_RiverEditOperateOption>` | :ref:`OperateItem<class_RiverEditTool_property_OperateItem>`             |
+-------------------------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                                   | :ref:`StepLength<class_RiverEditTool_property_StepLength>`               |
+-------------------------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                                 | :ref:`StepProportion<class_RiverEditTool_property_StepProportion>`       |
+-------------------------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                                   | :ref:`SelectedLineColor<class_RiverEditTool_property_SelectedLineColor>` |
+-------------------------------------------------------------+--------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                                   | :ref:`CutLineColor<class_RiverEditTool_property_CutLineColor>`           |
+-------------------------------------------------------------+--------------------------------------------------------------------------+

方法
----

+-----------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                                         | :ref:`ElementCallBack<class_RiverEditTool_method_ElementCallBack>` **(** :ref:`Action`2<class_Action`2>` action **)**                                            |
+-----------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PolygonGeometryElement[]<class_PolygonGeometryElement[]>` | :ref:`GetAllPolygonElement<class_RiverEditTool_method_GetAllPolygonElement>` **(** **)**                                                                         |
+-----------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PolygonGeometryElement<class_PolygonGeometryElement>`     | :ref:`GetSelectedPolygonElement<class_RiverEditTool_method_GetSelectedPolygonElement>` **(** **)**                                                               |
+-----------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                                         | :ref:`OnMouseDown<class_RiverEditTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**                    |
+-----------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                                         | :ref:`OnMouseMove<class_RiverEditTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**                    |
+-----------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                                   | :ref:`OnMouseDoubleClick<class_RiverEditTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**      |
+-----------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                                         | :ref:`AddPolygonGeometryElement<class_RiverEditTool_method_AddPolygonGeometryElement>` **(** :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` p **)** |
+-----------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_RiverEditTool_property_OperateItem:

- :ref:`RiverEditOperateOption<class_RiverEditOperateOption>` **OperateItem**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

传递操作

----

.. _class_RiverEditTool_property_StepLength:

- :ref:`Int32<class_Int32>` **StepLength**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

插值步长（插入多少个点），默认为1

----

.. _class_RiverEditTool_property_StepProportion:

- :ref:`Single<class_Single>` **StepProportion**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

插值公差，

----

.. _class_RiverEditTool_property_SelectedLineColor:

- :ref:`Color<class_Color>` **SelectedLineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

选中线的颜色，默认为Color(241f / 255f, 20f / 255f, 255f / 255f)

----

.. _class_RiverEditTool_property_CutLineColor:

- :ref:`Color<class_Color>` **CutLineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

切割线的时候射线的颜色

----


方法说明
-------

.. _class_RiverEditTool_method_ElementCallBack:

- :ref:`Void<class_Void>` **ElementCallBack** **(** :ref:`Action`2<class_Action`2>` action **)**



----

.. _class_RiverEditTool_method_GetAllPolygonElement:

- :ref:`PolygonGeometryElement[]<class_PolygonGeometryElement[]>` **GetAllPolygonElement** **(** **)**

获取所有面Element

----

.. _class_RiverEditTool_method_GetSelectedPolygonElement:

- :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` **GetSelectedPolygonElement** **(** **)**

获取选中的面Element

----

.. _class_RiverEditTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_RiverEditTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_RiverEditTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标双击事件。

----

.. _class_RiverEditTool_method_AddPolygonGeometryElement:

- :ref:`Void<class_Void>` **AddPolygonGeometryElement** **(** :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` p **)**

添加多边形

----

