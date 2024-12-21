.. _class_Fields:

Fields 
===================

**Inherits:** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+-----------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`FieldCount<class_Fields_property_FieldCount>` |
+-------------------------------+-----------------------------------------------------+
| :ref:`Field[]<class_Field[]>` | :ref:`Field<class_Fields_property_Field>`           |
+-------------------------------+-----------------------------------------------------+

方法
----

+-------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`FindField<class_Fields_method_FindField>` **(** :ref:`String<class_String>` fieldName **)**                          |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`AddField<class_Fields_method_AddField>` **(** :ref:`Field<class_Field>` field **)**                                  |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`DeleteAllFields<class_Fields_method_DeleteAllFields>` **(** **)**                                                    |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`DeleteField<class_Fields_method_DeleteField>` **(** :ref:`Field<class_Field>` Field **)**                            |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :ref:`Field<class_Field>`     | :ref:`GetField<class_Fields_method_GetField>` **(** :ref:`Int32<class_Int32>` Index **)**                                  |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`SetField<class_Fields_method_SetField>` **(** :ref:`Int32<class_Int32>` Index, :ref:`Field<class_Field>` Field **)** |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`HasFieldName<class_Fields_method_HasFieldName>` **(** :ref:`String<class_String>` name **)**                         |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Fields_property_FieldCount:

- :ref:`Int32<class_Int32>` **FieldCount**

+----------+---+
| *Getter* |   |
+----------+---+

字段总数

----

.. _class_Fields_property_Field:

- :ref:`Field[]<class_Field[]>` **Field**

+----------+---+
| *Getter* |   |
+----------+---+

字段列表转换为字段数组

----


方法说明
-------

.. _class_Fields_method_FindField:

- :ref:`Int32<class_Int32>` **FindField** **(** :ref:`String<class_String>` fieldName **)**

返回-1标示没找到对应字段。
Return -1 indicates that the corresponding field was not found.

----

.. _class_Fields_method_AddField:

- :ref:`Void<class_Void>` **AddField** **(** :ref:`Field<class_Field>` field **)**

AddField在创建字段集合时使用，不能用于将字段插入到属于现有表的字段集合中。若要将字段添加到现有对象类，请使用IClass：：AddField方法。

----

.. _class_Fields_method_DeleteAllFields:

- :ref:`Void<class_Void>` **DeleteAllFields** **(** **)**

清空所有字段

----

.. _class_Fields_method_DeleteField:

- :ref:`Void<class_Void>` **DeleteField** **(** :ref:`Field<class_Field>` Field **)**

根据字段对象删除字段

----

.. _class_Fields_method_GetField:

- :ref:`Field<class_Field>` **GetField** **(** :ref:`Int32<class_Int32>` Index **)**

根据索引值获取字段

----

.. _class_Fields_method_SetField:

- :ref:`Void<class_Void>` **SetField** **(** :ref:`Int32<class_Int32>` Index, :ref:`Field<class_Field>` Field **)**

将索引值为index的字段设置为Field

----

.. _class_Fields_method_HasFieldName:

- :ref:`Boolean<class_Boolean>` **HasFieldName** **(** :ref:`String<class_String>` name **)**

检查是否有字段名为name的字段

----

