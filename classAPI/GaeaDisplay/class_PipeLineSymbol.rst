.. _class_PipeLineSymbol:

PipeLineSymbol 
===================

**Inherits:** :ref:`Symbol<class_Symbol>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                 | :ref:`IsNeedNormal<class_PipeLineSymbol_property_IsNeedNormal>`         |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`Segment<class_PipeLineSymbol_property_Segment>`                   |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`SpatialMaterial<class_SpatialMaterial>` | :ref:`PipeLineMaterial<class_PipeLineSymbol_property_PipeLineMaterial>` |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`Width<class_PipeLineSymbol_property_Width>`                       |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`Height<class_PipeLineSymbol_property_Height>`                     |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`                 | :ref:`PipeLineTexture<class_PipeLineSymbol_property_PipeLineTexture>`   |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                     | :ref:`PipeLineColor<class_PipeLineSymbol_property_PipeLineColor>`       |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                     | :ref:`SymbolColor<class_PipeLineSymbol_property_SymbolColor>`           |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`Roughness<class_PipeLineSymbol_property_Roughness>`               |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`Metallic<class_PipeLineSymbol_property_Metallic>`                 |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`Specular<class_PipeLineSymbol_property_Specular>`                 |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`PolygonGeometry<class_PolygonGeometry>` | :ref:`PolygonGeometry<class_PipeLineSymbol_property_PolygonGeometry>`   |
+-----------------------------------------------+-------------------------------------------------------------------------+

方法
----

+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>`             | :ref:`Clone<class_PipeLineSymbol_method_Clone>` **(** **)**                                                                                                                                            |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`DrawMesh<class_PipeLineSymbol_method_DrawMesh>` **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**                                                 |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh<class_SymbolMesh>`     | :ref:`CreateMeshData<class_PipeLineSymbol_method_CreateMeshData>` **(** :ref:`Geometry<class_Geometry>` geometry, :ref:`Transform<class_Transform>` localorigin, :ref:`Int32<class_Int32>` level **)** |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>`       | :ref:`GenerateNormal<class_PipeLineSymbol_method_GenerateNormal>` **(** :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Int32[]<class_Int32[]>` index **)**                                           |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh<class_SymbolMesh>`     | :ref:`CreatePolygonSingleMesh<class_PipeLineSymbol_method_CreatePolygonSingleMesh>` **(** **)**                                                                                                        |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                 | :ref:`Dispose<class_PipeLineSymbol_method_Dispose>` **(** **)**                                                                                                                                        |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_PipeLineSymbol_property_IsNeedNormal:

- :ref:`Boolean<class_Boolean>` **IsNeedNormal**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_Segment:

- :ref:`Single<class_Single>` **Segment**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_PipeLineMaterial:

- :ref:`SpatialMaterial<class_SpatialMaterial>` **PipeLineMaterial**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_Width:

- :ref:`Single<class_Single>` **Width**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_Height:

- :ref:`Single<class_Single>` **Height**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_PipeLineTexture:

- :ref:`Texture<class_Texture>` **PipeLineTexture**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_PipeLineColor:

- :ref:`Color<class_Color>` **PipeLineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_SymbolColor:

- :ref:`Color<class_Color>` **SymbolColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_Roughness:

- :ref:`Single<class_Single>` **Roughness**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_Metallic:

- :ref:`Single<class_Single>` **Metallic**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_Specular:

- :ref:`Single<class_Single>` **Specular**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PipeLineSymbol_property_PolygonGeometry:

- :ref:`PolygonGeometry<class_PolygonGeometry>` **PolygonGeometry**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_PipeLineSymbol_method_Clone:

- :ref:`Object<class_Object>` **Clone** **(** **)**



----

.. _class_PipeLineSymbol_method_DrawMesh:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **DrawMesh** **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**



----

.. _class_PipeLineSymbol_method_CreateMeshData:

- :ref:`SymbolMesh<class_SymbolMesh>` **CreateMeshData** **(** :ref:`Geometry<class_Geometry>` geometry, :ref:`Transform<class_Transform>` localorigin, :ref:`Int32<class_Int32>` level **)**



----

.. _class_PipeLineSymbol_method_GenerateNormal:

- :ref:`Vector3[]<class_Vector3[]>` **GenerateNormal** **(** :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Int32[]<class_Int32[]>` index **)**

计算法线

----

.. _class_PipeLineSymbol_method_CreatePolygonSingleMesh:

- :ref:`SymbolMesh<class_SymbolMesh>` **CreatePolygonSingleMesh** **(** **)**



----

.. _class_PipeLineSymbol_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**



----

