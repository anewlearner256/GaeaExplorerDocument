.. _class_PipeSymbol:

PipeSymbol 
===================

**Inherits:** :ref:`Symbol<class_Symbol>` **<** :ref:`Object<class_Object>`

描述
----

管线符号

示例
----

属性
----

+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                 | :ref:`IsNeedNormal<class_PipeSymbol_property_IsNeedNormal>`             |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                     | :ref:`SectionPointNumber<class_PipeSymbol_property_SectionPointNumber>` |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`PipeRadius<class_PipeSymbol_property_PipeRadius>`                 |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`Sagment<class_PipeSymbol_property_Sagment>`                       |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`SpatialMaterial<class_SpatialMaterial>` | :ref:`PipeMaterial<class_PipeSymbol_property_PipeMaterial>`             |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`                 | :ref:`PipeTexture<class_PipeSymbol_property_PipeTexture>`               |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                     | :ref:`PipeColor<class_PipeSymbol_property_PipeColor>`                   |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                     | :ref:`SymbolColor<class_PipeSymbol_property_SymbolColor>`               |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`Specular<class_PipeSymbol_property_Specular>`                     |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`Roughness<class_PipeSymbol_property_Roughness>`                   |
+-----------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`Metallic<class_PipeSymbol_property_Metallic>`                     |
+-----------------------------------------------+-------------------------------------------------------------------------+

方法
----

+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>`             | :ref:`Clone<class_PipeSymbol_method_Clone>` **(** **)**                                                                                                                                            |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`DrawMesh<class_PipeSymbol_method_DrawMesh>` **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**                                                 |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh<class_SymbolMesh>`     | :ref:`CreateMeshData<class_PipeSymbol_method_CreateMeshData>` **(** :ref:`Geometry<class_Geometry>` geometry, :ref:`Transform<class_Transform>` localorigin, :ref:`Int32<class_Int32>` level **)** |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>`       | :ref:`GenerateNormal<class_PipeSymbol_method_GenerateNormal>` **(** :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Int32[]<class_Int32[]>` index **)**                                           |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh<class_SymbolMesh>`     | :ref:`CreateLineSingleMesh<class_PipeSymbol_method_CreateLineSingleMesh>` **(** **)**                                                                                                              |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                 | :ref:`Dispose<class_PipeSymbol_method_Dispose>` **(** **)**                                                                                                                                        |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_PipeSymbol_property_IsNeedNormal:

- :ref:`Boolean<class_Boolean>` **IsNeedNormal**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否需要法线，默认为true

----

.. _class_PipeSymbol_property_SectionPointNumber:

- :ref:`Int32<class_Int32>` **SectionPointNumber**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

截面控制点的个数，越大越接近圆

----

.. _class_PipeSymbol_property_PipeRadius:

- :ref:`Single<class_Single>` **PipeRadius**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

管线半径

----

.. _class_PipeSymbol_property_Sagment:

- :ref:`Single<class_Single>` **Sagment**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

以该值作为一条管线的长度

----

.. _class_PipeSymbol_property_PipeMaterial:

- :ref:`SpatialMaterial<class_SpatialMaterial>` **PipeMaterial**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

管线的空间材质

----

.. _class_PipeSymbol_property_PipeTexture:

- :ref:`Texture<class_Texture>` **PipeTexture**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

管线的纹理

----

.. _class_PipeSymbol_property_PipeColor:

- :ref:`Color<class_Color>` **PipeColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

管线的颜色

----

.. _class_PipeSymbol_property_SymbolColor:

- :ref:`Color<class_Color>` **SymbolColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

管线的颜色

----

.. _class_PipeSymbol_property_Specular:

- :ref:`Single<class_Single>` **Specular**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

镜面反射值

----

.. _class_PipeSymbol_property_Roughness:

- :ref:`Single<class_Single>` **Roughness**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

管线表面粗糙度

----

.. _class_PipeSymbol_property_Metallic:

- :ref:`Single<class_Single>` **Metallic**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

管线的金属性

----


方法说明
-------

.. _class_PipeSymbol_method_Clone:

- :ref:`Object<class_Object>` **Clone** **(** **)**

克隆当前管线样式

----

.. _class_PipeSymbol_method_DrawMesh:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **DrawMesh** **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**

根据传入的要素构建出模型数组

----

.. _class_PipeSymbol_method_CreateMeshData:

- :ref:`SymbolMesh<class_SymbolMesh>` **CreateMeshData** **(** :ref:`Geometry<class_Geometry>` geometry, :ref:`Transform<class_Transform>` localorigin, :ref:`Int32<class_Int32>` level **)**

根据几何类型创建SymbolMesh

----

.. _class_PipeSymbol_method_GenerateNormal:

- :ref:`Vector3[]<class_Vector3[]>` **GenerateNormal** **(** :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Int32[]<class_Int32[]>` index **)**

计算法线

----

.. _class_PipeSymbol_method_CreateLineSingleMesh:

- :ref:`SymbolMesh<class_SymbolMesh>` **CreateLineSingleMesh** **(** **)**

根据顶点、索引值构建SymbolMesh

----

.. _class_PipeSymbol_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**

释放当前对象

----

