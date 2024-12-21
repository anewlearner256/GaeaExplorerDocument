.. _class_FeatureClass:

FeatureClass 
===================

**Inherits:** :ref:`ObjectClass<class_ObjectClass>` **<** :ref:`Table<class_Table>` **<** :ref:`Dataset<class_Dataset>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

描述
----

要素类是存储在工作空间中的一种数据组织方式，要素类是在对象类的基础上的进一步扩展，包含了 现实世界中的空间实体。
A feature class is a way of organizing data stored in a workspace. A feature class is a further extension based on an object class and contains spatial entities in the real world.

示例
----

属性
----

+-------------------------------------------------+-------------------------------------------------------------------+
| :ref:`FeatureLayer<class_FeatureLayer>`         | :ref:`featureLayer<class_FeatureClass_property_featureLayer>`     |
+-------------------------------------------------+-------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                       | :ref:`FeatureCount<class_FeatureClass_property_FeatureCount>`     |
+-------------------------------------------------+-------------------------------------------------------------------+
| :ref:`Envelope<class_Envelope>`                 | :ref:`Extent<class_FeatureClass_property_Extent>`                 |
+-------------------------------------------------+-------------------------------------------------------------------+
| :ref:`gaeaGeometryType<class_gaeaGeometryType>` | :ref:`ShapeType<class_FeatureClass_property_ShapeType>`           |
+-------------------------------------------------+-------------------------------------------------------------------+
| :ref:`String<class_String>`                     | :ref:`AliasName<class_FeatureClass_property_AliasName>`           |
+-------------------------------------------------+-------------------------------------------------------------------+
| :ref:`Field<class_Field>`                       | :ref:`AreaField<class_FeatureClass_property_AreaField>`           |
+-------------------------------------------------+-------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                       | :ref:`FeatureClassID<class_FeatureClass_property_FeatureClassID>` |
+-------------------------------------------------+-------------------------------------------------------------------+
| :ref:`Field<class_Field>`                       | :ref:`LengthField<class_FeatureClass_property_LengthField>`       |
+-------------------------------------------------+-------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                       | :ref:`ObjectClassID<class_FeatureClass_property_ObjectClassID>`   |
+-------------------------------------------------+-------------------------------------------------------------------+
| :ref:`String<class_String>`                     | :ref:`ShapeFieldName<class_FeatureClass_property_ShapeFieldName>` |
+-------------------------------------------------+-------------------------------------------------------------------+

方法
----

+-------------------------------------------+--------------------------------------------------------------------------------------------------------+
| :ref:`IEnumerable`1<class_IEnumerable`1>` | :ref:`GetFeatures<class_FeatureClass_method_GetFeatures>` **(** **)**                                  |
+-------------------------------------------+--------------------------------------------------------------------------------------------------------+
| :ref:`Feature<class_Feature>`             | :ref:`GetFeature<class_FeatureClass_method_GetFeature>` **(** :ref:`Int32<class_Int32>` index **)**    |
+-------------------------------------------+--------------------------------------------------------------------------------------------------------+
| :ref:`FeatureCursor<class_FeatureCursor>` | :ref:`Insert<class_FeatureClass_method_Insert>` **(** :ref:`Boolean<class_Boolean>` useBuffering **)** |
+-------------------------------------------+--------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                   | :ref:`Delete<class_FeatureClass_method_Delete>` **(** **)**                                            |
+-------------------------------------------+--------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_FeatureClass_property_featureLayer:

- :ref:`FeatureLayer<class_FeatureLayer>` **featureLayer**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

要素类所在图层

----

.. _class_FeatureClass_property_FeatureCount:

- :ref:`Int32<class_Int32>` **FeatureCount**

+----------+---+
| *Getter* |   |
+----------+---+

要素类里的要素总数

----

.. _class_FeatureClass_property_Extent:

- :ref:`Envelope<class_Envelope>` **Extent**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

要素类的外包络矩形范围

----

.. _class_FeatureClass_property_ShapeType:

- :ref:`gaeaGeometryType<class_gaeaGeometryType>` **ShapeType**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

要素类的几何类型

----

.. _class_FeatureClass_property_AliasName:

- :ref:`String<class_String>` **AliasName**

+----------+---+
| *Getter* |   |
+----------+---+

要素类的别名

----

.. _class_FeatureClass_property_AreaField:

- :ref:`Field<class_Field>` **AreaField**

+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_FeatureClass_property_FeatureClassID:

- :ref:`Int32<class_Int32>` **FeatureClassID**

+----------+---+
| *Getter* |   |
+----------+---+

要素类的ID

----

.. _class_FeatureClass_property_LengthField:

- :ref:`Field<class_Field>` **LengthField**

+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_FeatureClass_property_ObjectClassID:

- :ref:`Int32<class_Int32>` **ObjectClassID**

+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_FeatureClass_property_ShapeFieldName:

- :ref:`String<class_String>` **ShapeFieldName**

+----------+---+
| *Getter* |   |
+----------+---+

Shape字段名称

----


方法说明
-------

.. _class_FeatureClass_method_GetFeatures:

- :ref:`IEnumerable`1<class_IEnumerable`1>` **GetFeatures** **(** **)**

获取要素类里的所有要素

----

.. _class_FeatureClass_method_GetFeature:

- :ref:`Feature<class_Feature>` **GetFeature** **(** :ref:`Int32<class_Int32>` index **)**

根据索引值获取要素

----

.. _class_FeatureClass_method_Insert:

- :ref:`FeatureCursor<class_FeatureCursor>` **Insert** **(** :ref:`Boolean<class_Boolean>` useBuffering **)**

未知

----

.. _class_FeatureClass_method_Delete:

- :ref:`Void<class_Void>` **Delete** **(** **)**

删除

----

