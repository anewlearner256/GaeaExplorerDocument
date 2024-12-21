.. _class_FeatureLayer:

FeatureLayer 
===================

**Inherits:** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

要素图层，继承自RenderableObject。
要素图层是包含一组相似要素及其相关属性的图层。 要素图层是 GaeaExplorer 表示要素 Feature的方式。 是最常用的图层类型。
这些要素类通常包含在**地理数据库**中，但还存在许多其他内容，包括 shapefile 和在线要素服务。

示例
----

属性
----

+-----------------------------------------------+---------------------------------------------------------------------+
| :ref:`FeatureRenderer<class_FeatureRenderer>` | :ref:`FeatureRenderer<class_FeatureLayer_property_FeatureRenderer>` |
+-----------------------------------------------+---------------------------------------------------------------------+
| :ref:`FeatureClass<class_FeatureClass>`       | :ref:`FeatureClass<class_FeatureLayer_property_FeatureClass>`       |
+-----------------------------------------------+---------------------------------------------------------------------+
| :ref:`RenderPriority<class_RenderPriority>`   | :ref:`Priority<class_FeatureLayer_property_Priority>`               |
+-----------------------------------------------+---------------------------------------------------------------------+
| :ref:`Symbol<class_Symbol>`                   | :ref:`Symbol<class_FeatureLayer_property_Symbol>`                   |
+-----------------------------------------------+---------------------------------------------------------------------+

方法
----

+-------------------------+---------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Initialize<class_FeatureLayer_method_Initialize>` **(** **)** |
+-------------------------+---------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Render<class_FeatureLayer_method_Render>` **(** **)**         |
+-------------------------+---------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Update<class_FeatureLayer_method_Update>` **(** **)**         |
+-------------------------+---------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Delete<class_FeatureLayer_method_Delete>` **(** **)**         |
+-------------------------+---------------------------------------------------------------------+

属性说明
-------

.. _class_FeatureLayer_property_FeatureRenderer:

- :ref:`FeatureRenderer<class_FeatureRenderer>` **FeatureRenderer**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

当前要素的渲染器

----

.. _class_FeatureLayer_property_FeatureClass:

- :ref:`FeatureClass<class_FeatureClass>` **FeatureClass**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

要素类

----

.. _class_FeatureLayer_property_Priority:

- :ref:`RenderPriority<class_RenderPriority>` **Priority**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

图层渲染的优先级，默认为RenderPriority.Custom=600

----

.. _class_FeatureLayer_property_Symbol:

- :ref:`Symbol<class_Symbol>` **Symbol**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

当前使用的样式

----


方法说明
-------

.. _class_FeatureLayer_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** **)**

图层初始化

----

.. _class_FeatureLayer_method_Render:

- :ref:`Void<class_Void>` **Render** **(** **)**

渲染函数

----

.. _class_FeatureLayer_method_Update:

- :ref:`Void<class_Void>` **Update** **(** **)**

图层更新

----

.. _class_FeatureLayer_method_Delete:

- :ref:`Void<class_Void>` **Delete** **(** **)**

移除当前图层

----

