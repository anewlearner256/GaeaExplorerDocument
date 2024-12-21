.. _class_GroundPolylineSymbol:

GroundPolylineSymbol 
===================

**Inherits:** :ref:`Symbol<class_Symbol>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+-----------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`Loop<class_GroundPolylineSymbol_property_Loop>`           |
+-------------------------------+-----------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`Width<class_GroundPolylineSymbol_property_Width>`         |
+-------------------------------+-----------------------------------------------------------------+
| :ref:`Color<class_Color>`     | :ref:`LineColor<class_GroundPolylineSymbol_property_LineColor>` |
+-------------------------------+-----------------------------------------------------------------+

方法
----

+-----------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>`       | :ref:`GetPositions<class_GroundPolylineSymbol_method_GetPositions>` **(** **)**                                                                                                                                        |
+-----------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`             | :ref:`GetWidth<class_GroundPolylineSymbol_method_GetWidth>` **(** **)**                                                                                                                                                |
+-----------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`ArrayMesh<class_ArrayMesh>`       | :ref:`CreateGeometry<class_GroundPolylineSymbol_method_CreateGeometry>` **(** :ref:`Single<class_Single>` wallHeight **)**                                                                                             |
+-----------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`DrawMesh<class_GroundPolylineSymbol_method_DrawMesh>` **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**                                                           |
+-----------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>`             | :ref:`Combine<class_GroundPolylineSymbol_method_Combine>` **(** :ref:`List`1<class_List`1>` symbolMeshes, :ref:`Color<class_Color>` lineColor, :ref:`Single<class_Single>` width, :ref:`Int32<class_Int32>` size **)** |
+-----------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_GroundPolylineSymbol_property_Loop:

- :ref:`Boolean<class_Boolean>` **Loop**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_GroundPolylineSymbol_property_Width:

- :ref:`Single<class_Single>` **Width**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_GroundPolylineSymbol_property_LineColor:

- :ref:`Color<class_Color>` **LineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_GroundPolylineSymbol_method_GetPositions:

- :ref:`Vector3[]<class_Vector3[]>` **GetPositions** **(** **)**



----

.. _class_GroundPolylineSymbol_method_GetWidth:

- :ref:`Single<class_Single>` **GetWidth** **(** **)**



----

.. _class_GroundPolylineSymbol_method_CreateGeometry:

- :ref:`ArrayMesh<class_ArrayMesh>` **CreateGeometry** **(** :ref:`Single<class_Single>` wallHeight **)**



----

.. _class_GroundPolylineSymbol_method_DrawMesh:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **DrawMesh** **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**



----

.. _class_GroundPolylineSymbol_method_Combine:

- :ref:`List`1<class_List`1>` **Combine** **(** :ref:`List`1<class_List`1>` symbolMeshes, :ref:`Color<class_Color>` lineColor, :ref:`Single<class_Single>` width, :ref:`Int32<class_Int32>` size **)**



----

