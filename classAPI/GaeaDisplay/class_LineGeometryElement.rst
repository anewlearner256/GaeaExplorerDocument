.. _class_LineGeometryElement:

LineGeometryElement 
===================

**Inherits:** :ref:`GeometryElementHelperPoint<class_GeometryElementHelperPoint>` **<** :ref:`GeometryElement<class_GeometryElement>` **<** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

线要素的Element

示例
----

属性
----

+---------------------------+--------------------------------------------------------------------------------+
| :ref:`Color<class_Color>` | :ref:`InitialLineColor<class_LineGeometryElement_property_InitialLineColor>`   |
+---------------------------+--------------------------------------------------------------------------------+
| :ref:`Color<class_Color>` | :ref:`SelectedLineColor<class_LineGeometryElement_property_SelectedLineColor>` |
+---------------------------+--------------------------------------------------------------------------------+

方法
----

+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                             | :ref:`OnMouseDown<class_LineGeometryElement_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**             |
+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>`                         | :ref:`GetLineData<class_LineGeometryElement_method_GetLineData>` **(** **)**                                                                              |
+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`LineGeometryElement[]<class_LineGeometryElement[]>` | :ref:`SplitLine<class_LineGeometryElement_method_SplitLine>` **(** :ref:`Vector3<class_Vector3>` CutPoints, :ref:`Double<class_Double>` PixDistance **)** |
+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_LineGeometryElement_property_InitialLineColor:

- :ref:`Color<class_Color>` **InitialLineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线的初始颜色

----

.. _class_LineGeometryElement_property_SelectedLineColor:

- :ref:`Color<class_Color>` **SelectedLineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线被选中的颜色

----


方法说明
-------

.. _class_LineGeometryElement_method_OnMouseDown:

- :ref:`Boolean<class_Boolean>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**

鼠标是否左击点中

----

.. _class_LineGeometryElement_method_GetLineData:

- :ref:`Vector3[]<class_Vector3[]>` **GetLineData** **(** **)**

获取线的坐标数据

----

.. _class_LineGeometryElement_method_SplitLine:

- :ref:`LineGeometryElement[]<class_LineGeometryElement[]>` **SplitLine** **(** :ref:`Vector3<class_Vector3>` CutPoints, :ref:`Double<class_Double>` PixDistance **)**

传入一个切点，切割成功返回一个LineGeometryElement数组
失败返回一个空数组

----

