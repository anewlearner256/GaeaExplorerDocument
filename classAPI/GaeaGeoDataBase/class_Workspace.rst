.. _class_Workspace:

Workspace 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------+--------------------------------------------+
| :ref:`String<class_String>` | :ref:`Path<class_Workspace_property_Path>` |
+-----------------------------+--------------------------------------------+

方法
----

+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`IEnumerator<class_IEnumerator>`   | :ref:`OpenFeatureClassCo<class_Workspace_method_OpenFeatureClassCo>` **(** :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`Boolean<class_Boolean>` readProp **)**             |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`FeatureClass<class_FeatureClass>` | :ref:`OpenFeatureClass<class_Workspace_method_OpenFeatureClass>` **(** :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`Boolean<class_Boolean>` readProp **)**                 |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`FeatureClass<class_FeatureClass>` | :ref:`OpenFeatureClassWithBuffer<class_Workspace_method_OpenFeatureClassWithBuffer>` **(** :ref:`Byte[]<class_Byte[]>` buffer, :ref:`Boolean<class_Boolean>` inverseLatLon **)** |
+-----------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Workspace_property_Path:

- :ref:`String<class_String>` **Path**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

工作区路径

----


方法说明
-------

.. _class_Workspace_method_OpenFeatureClassCo:

- :ref:`IEnumerator<class_IEnumerator>` **OpenFeatureClassCo** **(** :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`Boolean<class_Boolean>` readProp **)**

用于打开工作区中的要素类。

----

.. _class_Workspace_method_OpenFeatureClass:

- :ref:`FeatureClass<class_FeatureClass>` **OpenFeatureClass** **(** :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`Boolean<class_Boolean>` readProp **)**

用于打开工作区中的要素类。

----

.. _class_Workspace_method_OpenFeatureClassWithBuffer:

- :ref:`FeatureClass<class_FeatureClass>` **OpenFeatureClassWithBuffer** **(** :ref:`Byte[]<class_Byte[]>` buffer, :ref:`Boolean<class_Boolean>` inverseLatLon **)**

用于打开工作区中的要素类。并将字节数组作为缓冲区传递

----

