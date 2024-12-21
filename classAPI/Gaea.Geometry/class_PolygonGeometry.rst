.. _class_PolygonGeometry:

PolygonGeometry 
===================

**Inherits:** :ref:`Geometry<class_Geometry>` **<** :ref:`Object<class_Object>`

描述
----

多边形要素

示例
----

属性
----

+-----------------+------------------------------------------+

方法
----

+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`MultiPolylineGeometry<class_MultiPolylineGeometry>` | :ref:`GetRing<class_PolygonGeometry_method_GetRing>` **(** **)**                                                                                                                                                                                                                                                                                                          |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`LineGeometry<class_LineGeometry>`                   | :ref:`GetEdge<class_PolygonGeometry_method_GetEdge>` **(** :ref:`Int32<class_Int32>` index **)**                                                                                                                                                                                                                                                                          |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PolylineGeometry<class_PolylineGeometry>`           | :ref:`GetEdge<class_PolygonGeometry_method_GetEdge>` **(** :ref:`Double<class_Double>` angle **)**                                                                                                                                                                                                                                                                        |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                             | :ref:`IsNormalFacingIn<class_PolygonGeometry_method_IsNormalFacingIn>` **(** :ref:`List`1<class_List`1>` polygon, :ref:`Vector3<class_Vector3>` up, :ref:`Boolean<class_Boolean>` isClose **)**                                                                                                                                                                           |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                                   | :ref:`InvertPolygonVertex<class_PolygonGeometry_method_InvertPolygonVertex>` **(** :ref:`List`1<class_List`1>` polygon **)**                                                                                                                                                                                                                                              |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>`                   | :ref:`PolygonGenerater<class_PolygonGeometry_method_PolygonGenerater>` **(** :ref:`Geometry<class_Geometry>` geo, :ref:`Transform<class_Transform>` localorigin, :ref:`Single<class_Single>` heightOffset, :ref:`Int32<class_Int32>` level, :ref:`Single<class_Single>` unitScale, :ref:`Boolean<class_Boolean>` UVRepeat, :ref:`Boolean<class_Boolean>` NeedInvert **)** |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>`                         | :ref:`GenerateNormal<class_PolygonGeometry_method_GenerateNormal>` **(** :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Int32[]<class_Int32[]>` index **)**                                                                                                                                                                                                             |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double[]<class_Double[]>`                           | :ref:`GetRangeInLocalXY<class_PolygonGeometry_method_GetRangeInLocalXY>` **(** :ref:`Vector3[]<class_Vector3[]>` polygon **)**                                                                                                                                                                                                                                            |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2[]<class_Vector2[]>`                         | :ref:`GenerateUV<class_PolygonGeometry_method_GenerateUV>` **(** :ref:`UVMode<class_UVMode>` uvMode, :ref:`List`1<class_List`1>` polygon, :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Vector2<class_Vector2>` uvScale, :ref:`Single<class_Single>` unitScale **)**                                                                                                   |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2[]<class_Vector2[]>`                         | :ref:`GenerateUV<class_PolygonGeometry_method_GenerateUV>` **(** :ref:`Vector3[]<class_Vector3[]>` polygon, :ref:`Double[]<class_Double[]>` range, :ref:`Vector2<class_Vector2>` uvScale, :ref:`Single<class_Single>` unitScale **)**                                                                                                                                     |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2[]<class_Vector2[]>`                         | :ref:`GenerateUV<class_PolygonGeometry_method_GenerateUV>` **(** :ref:`List`1<class_List`1>` polygon, :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Vector2<class_Vector2>` uvScale, :ref:`Single<class_Single>` unitScale **)**                                                                                                                                       |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                             | :ref:`HitTest<class_PolygonGeometry_method_HitTest>` **(** :ref:`Vector3<class_Vector3>` latlon, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)**                                                                                                                                                                                     |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                             | :ref:`IsClockwise<class_PolygonGeometry_method_IsClockwise>` **(** **)**                                                                                                                                                                                                                                                                                                  |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                             | :ref:`IsClockwise<class_PolygonGeometry_method_IsClockwise>` **(** :ref:`List`1<class_List`1>` polygon **)**                                                                                                                                                                                                                                                              |
+-----------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------


方法说明
-------

.. _class_PolygonGeometry_method_GetRing:

- :ref:`MultiPolylineGeometry<class_MultiPolylineGeometry>` **GetRing** **(** **)**

获取多边形的边线

----

.. _class_PolygonGeometry_method_GetEdge:

- :ref:`LineGeometry<class_LineGeometry>` **GetEdge** **(** :ref:`Int32<class_Int32>` index **)**

根据索引获取多边形的边

----

.. _class_PolygonGeometry_method_GetEdge:

- :ref:`PolylineGeometry<class_PolylineGeometry>` **GetEdge** **(** :ref:`Double<class_Double>` angle **)**

返回一个表示多边形边缘的折线图形的PolylineGeometry对象。暂未实现

----

.. _class_PolygonGeometry_method_IsNormalFacingIn:

- :ref:`Boolean<class_Boolean>` **IsNormalFacingIn** **(** :ref:`List`1<class_List`1>` polygon, :ref:`Vector3<class_Vector3>` up, :ref:`Boolean<class_Boolean>` isClose **)**

判断面的法线是否向内

----

.. _class_PolygonGeometry_method_InvertPolygonVertex:

- :ref:`Void<class_Void>` **InvertPolygonVertex** **(** :ref:`List`1<class_List`1>` polygon **)**

将面的顶点顺序改为顺时针

----

.. _class_PolygonGeometry_method_PolygonGenerater:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **PolygonGenerater** **(** :ref:`Geometry<class_Geometry>` geo, :ref:`Transform<class_Transform>` localorigin, :ref:`Single<class_Single>` heightOffset, :ref:`Int32<class_Int32>` level, :ref:`Single<class_Single>` unitScale, :ref:`Boolean<class_Boolean>` UVRepeat, :ref:`Boolean<class_Boolean>` NeedInvert **)**

通过多边形几何数据生成模型

----

.. _class_PolygonGeometry_method_GenerateNormal:

- :ref:`Vector3[]<class_Vector3[]>` **GenerateNormal** **(** :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Int32[]<class_Int32[]>` index **)**

计算法线

----

.. _class_PolygonGeometry_method_GetRangeInLocalXY:

- :ref:`Double[]<class_Double[]>` **GetRangeInLocalXY** **(** :ref:`Vector3[]<class_Vector3[]>` polygon **)**

计算多边形在xy平面的投影的范围

----

.. _class_PolygonGeometry_method_GenerateUV:

- :ref:`Vector2[]<class_Vector2[]>` **GenerateUV** **(** :ref:`UVMode<class_UVMode>` uvMode, :ref:`List`1<class_List`1>` polygon, :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Vector2<class_Vector2>` uvScale, :ref:`Single<class_Single>` unitScale **)**

计算uv

----

.. _class_PolygonGeometry_method_GenerateUV:

- :ref:`Vector2[]<class_Vector2[]>` **GenerateUV** **(** :ref:`Vector3[]<class_Vector3[]>` polygon, :ref:`Double[]<class_Double[]>` range, :ref:`Vector2<class_Vector2>` uvScale, :ref:`Single<class_Single>` unitScale **)**

使用多边形的各个顶点的range中的比例作为uv

----

.. _class_PolygonGeometry_method_GenerateUV:

- :ref:`Vector2[]<class_Vector2[]>` **GenerateUV** **(** :ref:`List`1<class_List`1>` polygon, :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Vector2<class_Vector2>` uvScale, :ref:`Single<class_Single>` unitScale **)**

计算侧面的uv

----

.. _class_PolygonGeometry_method_HitTest:

- :ref:`Vector3<class_Vector3>` **HitTest** **(** :ref:`Vector3<class_Vector3>` latlon, :ref:`Single<class_Single>` HeightOffset, :ref:`Int32<class_Int32>` Thresholds **)**

计算点latlon是否在多边形内

----

.. _class_PolygonGeometry_method_IsClockwise:

- :ref:`Boolean<class_Boolean>` **IsClockwise** **(** **)**

判断多边形顶点是否是顺时针

----

.. _class_PolygonGeometry_method_IsClockwise:

- :ref:`Boolean<class_Boolean>` **IsClockwise** **(** :ref:`List`1<class_List`1>` polygon **)**



----

