.. _class_Row:

Row 
===================

**Inherits:** :ref:`RowBuffer<class_RowBuffer>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+---------------------------+------------------------------------+
| :ref:`Int32<class_Int32>` | :ref:`OID<class_Row_property_OID>` |
+---------------------------+------------------------------------+

方法
----

+-------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>`   | :ref:`get_OriginalValue<class_Row_method_get_OriginalValue>` **(** :ref:`Int32<class_Int32>` Index **)** |
+-------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`get_ValueChanged<class_Row_method_get_ValueChanged>` **(** :ref:`Int32<class_Int32>` Index **)**   |
+-------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`get_IsEqual<class_Row_method_get_IsEqual>` **(** :ref:`Row<class_Row>` otherRow **)**              |
+-------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnChanged<class_Row_method_OnChanged>` **(** **)**                                                 |
+-------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnDelete<class_Row_method_OnDelete>` **(** **)**                                                   |
+-------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnInitialize<class_Row_method_OnInitialize>` **(** **)**                                           |
+-------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnNew<class_Row_method_OnNew>` **(** **)**                                                         |
+-------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnValidate<class_Row_method_OnValidate>` **(** **)**                                               |
+-------------------------------+----------------------------------------------------------------------------------------------------------+
| :ref:`Fields<class_Fields>`   | :ref:`GetInvalidFields<class_Row_method_GetInvalidFields>` **(** **)**                                   |
+-------------------------------+----------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Row_property_OID:

- :ref:`Int32<class_Int32>` **OID**

+----------+---+
| *Getter* |   |
+----------+---+

在Feature对象中获取唯一标识符

----


方法说明
-------

.. _class_Row_method_get_OriginalValue:

- :ref:`Object<class_Object>` **get_OriginalValue** **(** :ref:`Int32<class_Int32>` Index **)**

未知

----

.. _class_Row_method_get_ValueChanged:

- :ref:`Boolean<class_Boolean>` **get_ValueChanged** **(** :ref:`Int32<class_Int32>` Index **)**



----

.. _class_Row_method_get_IsEqual:

- :ref:`Boolean<class_Boolean>` **get_IsEqual** **(** :ref:`Row<class_Row>` otherRow **)**

未知

----

.. _class_Row_method_OnChanged:

- :ref:`Void<class_Void>` **OnChanged** **(** **)**



----

.. _class_Row_method_OnDelete:

- :ref:`Void<class_Void>` **OnDelete** **(** **)**



----

.. _class_Row_method_OnInitialize:

- :ref:`Void<class_Void>` **OnInitialize** **(** **)**



----

.. _class_Row_method_OnNew:

- :ref:`Void<class_Void>` **OnNew** **(** **)**



----

.. _class_Row_method_OnValidate:

- :ref:`Void<class_Void>` **OnValidate** **(** **)**



----

.. _class_Row_method_GetInvalidFields:

- :ref:`Fields<class_Fields>` **GetInvalidFields** **(** **)**



----

