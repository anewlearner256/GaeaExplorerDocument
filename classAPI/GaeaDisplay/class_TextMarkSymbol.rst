.. _class_TextMarkSymbol:

TextMarkSymbol 
===================

**Inherits:** :ref:`MarkSymbol<class_MarkSymbol>` **<** :ref:`Symbol<class_Symbol>` **<** :ref:`Object<class_Object>`

描述
----

文字符号样式

示例
----

属性
----

+-------------------------------------+-----------------------------------------------------------------+
| :ref:`String<class_String>`         | :ref:`Field<class_TextMarkSymbol_property_Field>`               |
+-------------------------------------+-----------------------------------------------------------------+
| :ref:`Single<class_Single>`         | :ref:`MarkSize<class_TextMarkSymbol_property_MarkSize>`         |
+-------------------------------------+-----------------------------------------------------------------+
| :ref:`AnchorType<class_AnchorType>` | :ref:`Anchor<class_TextMarkSymbol_property_Anchor>`             |
+-------------------------------------+-----------------------------------------------------------------+
| :ref:`Color<class_Color>`           | :ref:`OutLineColor<class_TextMarkSymbol_property_OutLineColor>` |
+-------------------------------------+-----------------------------------------------------------------+
| :ref:`Color<class_Color>`           | :ref:`FontColor<class_TextMarkSymbol_property_FontColor>`       |
+-------------------------------------+-----------------------------------------------------------------+
| :ref:`Color<class_Color>`           | :ref:`SymbolColor<class_TextMarkSymbol_property_SymbolColor>`   |
+-------------------------------------+-----------------------------------------------------------------+
| :ref:`Single<class_Single>`         | :ref:`Fontgap<class_TextMarkSymbol_property_Fontgap>`           |
+-------------------------------------+-----------------------------------------------------------------+

方法
----

+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>`             | :ref:`Clone<class_TextMarkSymbol_method_Clone>` **(** **)**                                                                                            |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`DrawMesh<class_TextMarkSymbol_method_DrawMesh>` **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)** |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_TextMarkSymbol_property_Field:

- :ref:`String<class_String>` **Field**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

文字字段

----

.. _class_TextMarkSymbol_property_MarkSize:

- :ref:`Single<class_Single>` **MarkSize**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

文字大小

----

.. _class_TextMarkSymbol_property_Anchor:

- :ref:`AnchorType<class_AnchorType>` **Anchor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

文字停靠方位

----

.. _class_TextMarkSymbol_property_OutLineColor:

- :ref:`Color<class_Color>` **OutLineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

文字外边框颜色

----

.. _class_TextMarkSymbol_property_FontColor:

- :ref:`Color<class_Color>` **FontColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

字体颜色

----

.. _class_TextMarkSymbol_property_SymbolColor:

- :ref:`Color<class_Color>` **SymbolColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

字体颜色

----

.. _class_TextMarkSymbol_property_Fontgap:

- :ref:`Single<class_Single>` **Fontgap**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

字体间距

----


方法说明
-------

.. _class_TextMarkSymbol_method_Clone:

- :ref:`Object<class_Object>` **Clone** **(** **)**

克隆当前面样式

----

.. _class_TextMarkSymbol_method_DrawMesh:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **DrawMesh** **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**

根据传入的要素构建出模型数组

----

