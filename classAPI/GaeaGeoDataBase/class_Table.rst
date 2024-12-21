.. _class_Table:

Table 
===================

**Inherits:** :ref:`Dataset<class_Dataset>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+--------------------------------------------------------+
| :ref:`Fields<class_Fields>`   | :ref:`Fields<class_Table_property_Fields>`             |
+-------------------------------+--------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`OIDFieldName<class_Table_property_OIDFieldName>` |
+-------------------------------+--------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`HasOID<class_Table_property_HasOID>`             |
+-------------------------------+--------------------------------------------------------+
| :ref:`Object<class_Object>`   | :ref:`Extension<class_Table_property_Extension>`       |
+-------------------------------+--------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`CanSelect<class_Table_property_CanSelect>`       |
+-------------------------------+--------------------------------------------------------+

方法
----

+-----------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`         | :ref:`FindField<class_Table_method_FindField>` **(** :ref:`String<class_String>` fieldName **)** |
+-----------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`Row<class_Row>`             | :ref:`CreateRow<class_Table_method_CreateRow>` **(** **)**                                       |
+-----------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`RowBuffer<class_RowBuffer>` | :ref:`CreateRowBuffer<class_Table_method_CreateRowBuffer>` **(** **)**                           |
+-----------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`Row<class_Row>`             | :ref:`GetRow<class_Table_method_GetRow>` **(** :ref:`Int32<class_Int32>` OID **)**               |
+-----------------------------------+--------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Table_property_Fields:

- :ref:`Fields<class_Fields>` **Fields**

+----------+---+
| *Getter* |   |
+----------+---+

Fields类型的只读属性，表示数据表的字段。

----

.. _class_Table_property_OIDFieldName:

- :ref:`String<class_String>` **OIDFieldName**

+----------+---+
| *Getter* |   |
+----------+---+

字符串类型的只读属性，表示唯一标识符的字段名称。

----

.. _class_Table_property_HasOID:

- :ref:`Boolean<class_Boolean>` **HasOID**

+----------+---+
| *Getter* |   |
+----------+---+

布尔类型的只读属性，表示数据表是否包含唯一标识符字段。

----

.. _class_Table_property_Extension:

- :ref:`Object<class_Object>` **Extension**

+----------+---+
| *Getter* |   |
+----------+---+

返回_Extension属性的值

----

.. _class_Table_property_CanSelect:

- :ref:`Boolean<class_Boolean>` **CanSelect**

+----------+---+
| *Getter* |   |
+----------+---+

返回true，表示该类支持选择操作。该方法尚未实现

----


方法说明
-------

.. _class_Table_method_FindField:

- :ref:`Int32<class_Int32>` **FindField** **(** :ref:`String<class_String>` fieldName **)**

用于查找指定字段在字段列表中的索引。如果字段不存在，则返回-1。

----

.. _class_Table_method_CreateRow:

- :ref:`Row<class_Row>` **CreateRow** **(** **)**

创建一个新的Row对象，将其添加到_Row列表中，并返回该对象。

----

.. _class_Table_method_CreateRowBuffer:

- :ref:`RowBuffer<class_RowBuffer>` **CreateRowBuffer** **(** **)**

创建一个新的RowBuffer对象，并将其转换为Row类型。

----

.. _class_Table_method_GetRow:

- :ref:`Row<class_Row>` **GetRow** **(** :ref:`Int32<class_Int32>` OID **)**

获取具有指定OID的Row对象。该方法尚未实现

----

