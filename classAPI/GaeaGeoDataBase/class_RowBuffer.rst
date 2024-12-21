.. _class_RowBuffer:

RowBuffer 
===================

**Inherits:** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

描述
----

定义一个GaeaGeoDataBase.RowBuffer类。
Define a GaeaGeoDataBase.RowBuffer class.

示例
----

属性
----

+-----------------------------+------------------------------------------------+
| :ref:`Fields<class_Fields>` | :ref:`Fields<class_RowBuffer_property_Fields>` |
+-----------------------------+------------------------------------------------+

方法
----

+-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>` | :ref:`get_Value<class_RowBuffer_method_get_Value>` **(** :ref:`Int32<class_Int32>` index **)**                                          |
+-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`set_Value<class_RowBuffer_method_set_Value>` **(** :ref:`Int32<class_Int32>` index, :ref:`Object<class_Object>` value **)**       |
+-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>` | :ref:`GetValue<class_RowBuffer_method_GetValue>` **(** :ref:`String<class_String>` fieldName **)**                                      |
+-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`set_Value<class_RowBuffer_method_set_Value>` **(** :ref:`String<class_String>` fieldName, :ref:`Object<class_Object>` value **)** |
+-----------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_RowBuffer_property_Fields:

- :ref:`Fields<class_Fields>` **Fields**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

字段

----


方法说明
-------

.. _class_RowBuffer_method_get_Value:

- :ref:`Object<class_Object>` **get_Value** **(** :ref:`Int32<class_Int32>` index **)**

通过索引值获取对象

----

.. _class_RowBuffer_method_set_Value:

- :ref:`Void<class_Void>` **set_Value** **(** :ref:`Int32<class_Int32>` index, :ref:`Object<class_Object>` value **)**

该方法的作用是在Feature对象中设置指定索引处的值，如果索引无效，则不进行设置。

----

.. _class_RowBuffer_method_GetValue:

- :ref:`Object<class_Object>` **GetValue** **(** :ref:`String<class_String>` fieldName **)**

是在Feature对象中获取指定字段的值，如果字段不存在，则返回null。

----

.. _class_RowBuffer_method_set_Value:

- :ref:`Void<class_Void>` **set_Value** **(** :ref:`String<class_String>` fieldName, :ref:`Object<class_Object>` value **)**

在Feature对象中设置指定字段的值，如果字段不存在，则不进行设置。

----

