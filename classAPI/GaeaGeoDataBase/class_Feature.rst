.. _class_Feature:

Feature 
===================

**Inherits:** :ref:`Object<class_Object>` **<** :ref:`Row<class_Row>` **<** :ref:`RowBuffer<class_RowBuffer>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------------+----------------------------------------------------------+
| :ref:`IGeometry<class_IGeometry>`       | :ref:`Shape<class_Feature_property_Shape>`               |
+-----------------------------------------+----------------------------------------------------------+
| :ref:`Envelope<class_Envelope>`         | :ref:`Extent<class_Feature_property_Extent>`             |
+-----------------------------------------+----------------------------------------------------------+
| :ref:`Int32<class_Int32>`               | :ref:`Level<class_Feature_property_Level>`               |
+-----------------------------------------+----------------------------------------------------------+
| :ref:`FeatureLayer<class_FeatureLayer>` | :ref:`FeatureLayer<class_Feature_property_FeatureLayer>` |
+-----------------------------------------+----------------------------------------------------------+

方法
----

+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`SetShape<class_Feature_method_SetShape>` **(** :ref:`Geometry<class_Geometry>` shape **)**                                                |
+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>` | :ref:`GetValue<class_Feature_method_GetValue>` **(** :ref:`String<class_String>` fieldName **)**                                                |
+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`set_Value<class_Feature_method_set_Value>` **(** :ref:`String<class_String>` fieldName, :ref:`Object<class_Object>` value **)**           |
+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`SetStringValue<class_Feature_method_SetStringValue>` **(** :ref:`String<class_String>` fieldName, :ref:`String<class_String>` value **)** |
+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>` | :ref:`GetStringValue<class_Feature_method_GetStringValue>` **(** :ref:`String<class_String>` fieldName **)**                                    |
+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`SetFields<class_Feature_method_SetFields>` **(** :ref:`Fields<class_Fields>` fields **)**                                                 |
+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Feature_property_Shape:

- :ref:`IGeometry<class_IGeometry>` **Shape**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

单个要素的几何类型

----

.. _class_Feature_property_Extent:

- :ref:`Envelope<class_Envelope>` **Extent**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

要素的外包络矩形

----

.. _class_Feature_property_Level:

- :ref:`Int32<class_Int32>` **Level**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

要素所在层级

----

.. _class_Feature_property_FeatureLayer:

- :ref:`FeatureLayer<class_FeatureLayer>` **FeatureLayer**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

要素所在图层

----


方法说明
-------

.. _class_Feature_method_SetShape:

- :ref:`Void<class_Void>` **SetShape** **(** :ref:`Geometry<class_Geometry>` shape **)**

将单个要素的几何类型设置为shape类型

----

.. _class_Feature_method_GetValue:

- :ref:`Object<class_Object>` **GetValue** **(** :ref:`String<class_String>` fieldName **)**

通过名称获取要素对象

----

.. _class_Feature_method_set_Value:

- :ref:`Void<class_Void>` **set_Value** **(** :ref:`String<class_String>` fieldName, :ref:`Object<class_Object>` value **)**

设置value要素的属性为fieldName

----

.. _class_Feature_method_SetStringValue:

- :ref:`Void<class_Void>` **SetStringValue** **(** :ref:`String<class_String>` fieldName, :ref:`String<class_String>` value **)**

设置要素属性值

----

.. _class_Feature_method_GetStringValue:

- :ref:`String<class_String>` **GetStringValue** **(** :ref:`String<class_String>` fieldName **)**

未知

----

.. _class_Feature_method_SetFields:

- :ref:`Void<class_Void>` **SetFields** **(** :ref:`Fields<class_Fields>` fields **)**

设置要素的字段值

----

