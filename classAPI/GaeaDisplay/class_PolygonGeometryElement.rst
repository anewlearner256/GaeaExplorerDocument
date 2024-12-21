.. _class_PolygonGeometryElement:

PolygonGeometryElement 
===================

**Inherits:** :ref:`GeometryElementHelperPoint<class_GeometryElementHelperPoint>` **<** :ref:`GeometryElement<class_GeometryElement>` **<** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

面Element，用来表示交互绘制面时的对象，用户可以获取到面的点坐标信息，也可以改变面的相关属性，如颜色、点的位置。

示例
----

属性
----

+---------------------------+-----------------------------------------------------------------------------------+
| :ref:`Color<class_Color>` | :ref:`InitialLineColor<class_PolygonGeometryElement_property_InitialLineColor>`   |
+---------------------------+-----------------------------------------------------------------------------------+
| :ref:`Color<class_Color>` | :ref:`SelectedLineColor<class_PolygonGeometryElement_property_SelectedLineColor>` |
+---------------------------+-----------------------------------------------------------------------------------+
| :ref:`Color<class_Color>` | :ref:`InitialFillColor<class_PolygonGeometryElement_property_InitialFillColor>`   |
+---------------------------+-----------------------------------------------------------------------------------+
| :ref:`Color<class_Color>` | :ref:`SelectedFillColor<class_PolygonGeometryElement_property_SelectedFillColor>` |
+---------------------------+-----------------------------------------------------------------------------------+

方法
----

+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`     | :ref:`OnMouseDown<class_PolygonGeometryElement_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)** |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>` | :ref:`GetPolygonData<class_PolygonGeometryElement_method_GetPolygonData>` **(** **)**                                                            |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_PolygonGeometryElement_property_InitialLineColor:

- :ref:`Color<class_Color>` **InitialLineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面的边线初始颜色

----

.. _class_PolygonGeometryElement_property_SelectedLineColor:

- :ref:`Color<class_Color>` **SelectedLineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面的边线被选中后的颜色

----

.. _class_PolygonGeometryElement_property_InitialFillColor:

- :ref:`Color<class_Color>` **InitialFillColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面的初始填充颜色

----

.. _class_PolygonGeometryElement_property_SelectedFillColor:

- :ref:`Color<class_Color>` **SelectedFillColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面被选中的颜色

----


方法说明
-------

.. _class_PolygonGeometryElement_method_OnMouseDown:

- :ref:`Boolean<class_Boolean>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**

鼠标是否左击点中

----

.. _class_PolygonGeometryElement_method_GetPolygonData:

- :ref:`Vector3[]<class_Vector3[]>` **GetPolygonData** **(** **)**

获得多边形的点数据

----

