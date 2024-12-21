.. _class_LineSymbol:

LineSymbol 
===================

**Inherits:** :ref:`Symbol<class_Symbol>` **<** :ref:`Object<class_Object>`

描述
----

线的样式

示例
----

属性
----

+---------------------------------+-------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`   | :ref:`DepthTestEnable<class_LineSymbol_property_DepthTestEnable>` |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`       | :ref:`Priority<class_LineSymbol_property_Priority>`               |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`Single<class_Single>`     | :ref:`LineWidth<class_LineSymbol_property_LineWidth>`             |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`Color<class_Color>`       | :ref:`LineColor<class_LineSymbol_property_LineColor>`             |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`   | :ref:`LineTexture<class_LineSymbol_property_LineTexture>`         |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`   | :ref:`HasLineTexture<class_LineSymbol_property_HasLineTexture>`   |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`LineType<class_LineType>` | :ref:`LineStyle<class_LineSymbol_property_LineStyle>`             |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`   | :ref:`IsFlowing<class_LineSymbol_property_IsFlowing>`             |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`Single<class_Single>`     | :ref:`EmissionPower<class_LineSymbol_property_EmissionPower>`     |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`Single<class_Single>`     | :ref:`FlowVelocity<class_LineSymbol_property_FlowVelocity>`       |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`Color<class_Color>`       | :ref:`SymbolColor<class_LineSymbol_property_SymbolColor>`         |
+---------------------------------+-------------------------------------------------------------------+
| :ref:`Single<class_Single>`     | :ref:`RepeatTimes<class_LineSymbol_property_RepeatTimes>`         |
+---------------------------------+-------------------------------------------------------------------+

方法
----

+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>`             | :ref:`Clone<class_LineSymbol_method_Clone>` **(** **)**                                                                                                                                            |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`DrawMesh<class_LineSymbol_method_DrawMesh>` **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**                                                 |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh<class_SymbolMesh>`     | :ref:`CreateMeshData<class_LineSymbol_method_CreateMeshData>` **(** :ref:`Geometry<class_Geometry>` geometry, :ref:`Transform<class_Transform>` localorigin, :ref:`Int32<class_Int32>` level **)** |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh<class_SymbolMesh>`     | :ref:`CreateLineSingleMesh<class_LineSymbol_method_CreateLineSingleMesh>` **(** **)**                                                                                                              |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                 | :ref:`Dispose<class_LineSymbol_method_Dispose>` **(** **)**                                                                                                                                        |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_LineSymbol_property_DepthTestEnable:

- :ref:`Boolean<class_Boolean>` **DepthTestEnable**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否开启深度检测

----

.. _class_LineSymbol_property_Priority:

- :ref:`Int32<class_Int32>` **Priority**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

渲染优先级

----

.. _class_LineSymbol_property_LineWidth:

- :ref:`Single<class_Single>` **LineWidth**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线的宽度

----

.. _class_LineSymbol_property_LineColor:

- :ref:`Color<class_Color>` **LineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线的颜色

----

.. _class_LineSymbol_property_LineTexture:

- :ref:`Texture<class_Texture>` **LineTexture**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线的纹理

----

.. _class_LineSymbol_property_HasLineTexture:

- :ref:`Boolean<class_Boolean>` **HasLineTexture**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否有线的纹理

----

.. _class_LineSymbol_property_LineStyle:

- :ref:`LineType<class_LineType>` **LineStyle**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线的样式

----

.. _class_LineSymbol_property_IsFlowing:

- :ref:`Boolean<class_Boolean>` **IsFlowing**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否是流线

----

.. _class_LineSymbol_property_EmissionPower:

- :ref:`Single<class_Single>` **EmissionPower**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

发射功率

----

.. _class_LineSymbol_property_FlowVelocity:

- :ref:`Single<class_Single>` **FlowVelocity**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

流速

----

.. _class_LineSymbol_property_SymbolColor:

- :ref:`Color<class_Color>` **SymbolColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线的颜色

----

.. _class_LineSymbol_property_RepeatTimes:

- :ref:`Single<class_Single>` **RepeatTimes**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

流线的重复次数

----


方法说明
-------

.. _class_LineSymbol_method_Clone:

- :ref:`Object<class_Object>` **Clone** **(** **)**

复制当前的LineSymbol对象

----

.. _class_LineSymbol_method_DrawMesh:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **DrawMesh** **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**

根据传入的要素构建出模型数组

----

.. _class_LineSymbol_method_CreateMeshData:

- :ref:`SymbolMesh<class_SymbolMesh>` **CreateMeshData** **(** :ref:`Geometry<class_Geometry>` geometry, :ref:`Transform<class_Transform>` localorigin, :ref:`Int32<class_Int32>` level **)**

根据几何类型创建SymbolMesh

----

.. _class_LineSymbol_method_CreateLineSingleMesh:

- :ref:`SymbolMesh<class_SymbolMesh>` **CreateLineSingleMesh** **(** **)**

创建单个SymbolMesh

----

.. _class_LineSymbol_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**

释放当前对象

----

