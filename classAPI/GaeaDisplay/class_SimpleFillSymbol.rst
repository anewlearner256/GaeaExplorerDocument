.. _class_SimpleFillSymbol:

SimpleFillSymbol 
===================

**Inherits:** :ref:`Symbol<class_Symbol>` **<** :ref:`Object<class_Object>`

描述
----

简单面填充样式

示例
----

属性
----

+-----------------------------------------------+---------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                 | :ref:`HasOutLine<class_SimpleFillSymbol_property_HasOutLine>`       |
+-----------------------------------------------+---------------------------------------------------------------------+
| :ref:`LineSymbol<class_LineSymbol>`           | :ref:`OutLineSymbol<class_SimpleFillSymbol_property_OutLineSymbol>` |
+-----------------------------------------------+---------------------------------------------------------------------+
| :ref:`SpatialMaterial<class_SpatialMaterial>` | :ref:`FillMaterial<class_SimpleFillSymbol_property_FillMaterial>`   |
+-----------------------------------------------+---------------------------------------------------------------------+
| :ref:`Color<class_Color>`                     | :ref:`FillColor<class_SimpleFillSymbol_property_FillColor>`         |
+-----------------------------------------------+---------------------------------------------------------------------+
| :ref:`Color<class_Color>`                     | :ref:`SymbolColor<class_SimpleFillSymbol_property_SymbolColor>`     |
+-----------------------------------------------+---------------------------------------------------------------------+

方法
----

+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`DrawMesh<class_SimpleFillSymbol_method_DrawMesh>` **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)** |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>`             | :ref:`Clone<class_SimpleFillSymbol_method_Clone>` **(** **)**                                                                                            |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_SimpleFillSymbol_property_HasOutLine:

- :ref:`Boolean<class_Boolean>` **HasOutLine**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否有外边线，默认为fasle

----

.. _class_SimpleFillSymbol_property_OutLineSymbol:

- :ref:`LineSymbol<class_LineSymbol>` **OutLineSymbol**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

外边线样式

----

.. _class_SimpleFillSymbol_property_FillMaterial:

- :ref:`SpatialMaterial<class_SpatialMaterial>` **FillMaterial**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面的材质

----

.. _class_SimpleFillSymbol_property_FillColor:

- :ref:`Color<class_Color>` **FillColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面的填充颜色

----

.. _class_SimpleFillSymbol_property_SymbolColor:

- :ref:`Color<class_Color>` **SymbolColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

填充面的颜色

----


方法说明
-------

.. _class_SimpleFillSymbol_method_DrawMesh:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **DrawMesh** **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**

根据传入的要素构建出模型数组

----

.. _class_SimpleFillSymbol_method_Clone:

- :ref:`Object<class_Object>` **Clone** **(** **)**

克隆当前面样式

----

