.. _class_CompositeSymbol:

CompositeSymbol 
===================

**Inherits:** :ref:`Symbol<class_Symbol>` **<** :ref:`Object<class_Object>`

描述
----

组合符号，继承自Symbol

示例
----

属性
----

+-----------------+------------------------------------------+

方法
----

+-----------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                 | :ref:`AddSymbol<class_CompositeSymbol_method_AddSymbol>` **(** :ref:`Symbol<class_Symbol>` symbol **)**                                             |
+-----------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                 | :ref:`RemoveSymbol<class_CompositeSymbol_method_RemoveSymbol>` **(** :ref:`Symbol<class_Symbol>` symbol **)**                                       |
+-----------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>`             | :ref:`Clone<class_CompositeSymbol_method_Clone>` **(** **)**                                                                                        |
+-----------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`DrawMesh<class_CompositeSymbol_method_DrawMesh>` **(** :ref:`Feature<class_Feature>` geo, :ref:`Transform<class_Transform>` localorigin **)** |
+-----------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------


方法说明
-------

.. _class_CompositeSymbol_method_AddSymbol:

- :ref:`Void<class_Void>` **AddSymbol** **(** :ref:`Symbol<class_Symbol>` symbol **)**

向组合符号添加单个样式

----

.. _class_CompositeSymbol_method_RemoveSymbol:

- :ref:`Void<class_Void>` **RemoveSymbol** **(** :ref:`Symbol<class_Symbol>` symbol **)**

移除单个样式

----

.. _class_CompositeSymbol_method_Clone:

- :ref:`Object<class_Object>` **Clone** **(** **)**

克隆当前组合样式

----

.. _class_CompositeSymbol_method_DrawMesh:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **DrawMesh** **(** :ref:`Feature<class_Feature>` geo, :ref:`Transform<class_Transform>` localorigin **)**

根据传入的要素构建出模型数组

----

