.. _class_Symbol:

Symbol 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----

样式类

示例
----

属性
----

+---------------------------------------------------------+---------------------------------------------------------+
| :ref:`Single<class_Single>`                             | :ref:`HeightOffset<class_Symbol_property_HeightOffset>` |
+---------------------------------------------------------+---------------------------------------------------------+
| :ref:`Color<class_Color>`                               | :ref:`SymbolColor<class_Symbol_property_SymbolColor>`   |
+---------------------------------------------------------+---------------------------------------------------------+
| :ref:`ShadowCastingSetting<class_ShadowCastingSetting>` | :ref:`CastShadow<class_Symbol_property_CastShadow>`     |
+---------------------------------------------------------+---------------------------------------------------------+

方法
----

+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>`             | :ref:`Clone<class_Symbol_method_Clone>` **(** **)**                                                                                        |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                 | :ref:`Dispose<class_Symbol_method_Dispose>` **(** **)**                                                                                    |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`DrawMesh<class_Symbol_method_DrawMesh>` **(** :ref:`Feature<class_Feature>` geo, :ref:`Transform<class_Transform>` localorigin **)** |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Symbol_property_HeightOffset:

- :ref:`Single<class_Single>` **HeightOffset**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

高度偏移

----

.. _class_Symbol_property_SymbolColor:

- :ref:`Color<class_Color>` **SymbolColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

颜色

----

.. _class_Symbol_property_CastShadow:

- :ref:`ShadowCastingSetting<class_ShadowCastingSetting>` **CastShadow**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_Symbol_method_Clone:

- :ref:`Object<class_Object>` **Clone** **(** **)**

克隆当前面样式

----

.. _class_Symbol_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**

释放当前对象

----

.. _class_Symbol_method_DrawMesh:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **DrawMesh** **(** :ref:`Feature<class_Feature>` geo, :ref:`Transform<class_Transform>` localorigin **)**

根据传入的要素构建出模型数组

----

