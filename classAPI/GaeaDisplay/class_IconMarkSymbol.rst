.. _class_IconMarkSymbol:

IconMarkSymbol 
===================

**Inherits:** :ref:`MarkSymbol<class_MarkSymbol>` **<** :ref:`Symbol<class_Symbol>` **<** :ref:`Object<class_Object>`

描述
----

图标样式

示例
----

属性
----

+-------------------------------+---------------------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`Priority<class_IconMarkSymbol_property_Priority>`       |
+-------------------------------+---------------------------------------------------------------+
| :ref:`Texture<class_Texture>` | :ref:`Icon<class_IconMarkSymbol_property_Icon>`               |
+-------------------------------+---------------------------------------------------------------+
| :ref:`Color<class_Color>`     | :ref:`SymbolColor<class_IconMarkSymbol_property_SymbolColor>` |
+-------------------------------+---------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`MarkSize<class_IconMarkSymbol_property_MarkSize>`       |
+-------------------------------+---------------------------------------------------------------+

方法
----

+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`DrawMesh<class_IconMarkSymbol_method_DrawMesh>` **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)** |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_IconMarkSymbol_property_Priority:

- :ref:`Int32<class_Int32>` **Priority**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

渲染优先级

----

.. _class_IconMarkSymbol_property_Icon:

- :ref:`Texture<class_Texture>` **Icon**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

图标

----

.. _class_IconMarkSymbol_property_SymbolColor:

- :ref:`Color<class_Color>` **SymbolColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

图标颜色设置

----

.. _class_IconMarkSymbol_property_MarkSize:

- :ref:`Single<class_Single>` **MarkSize**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

图标大小

----


方法说明
-------

.. _class_IconMarkSymbol_method_DrawMesh:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **DrawMesh** **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**

根据传入的要素构建出模型数组

----

