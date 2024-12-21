.. _class_TemplateUrlImageStore:

TemplateUrlImageStore 
===================

**Inherits:** :ref:`ImagePyramidTileStore<class_ImagePyramidTileStore>` **<** :ref:`PyramidTileStore<class_PyramidTileStore>` **<** :ref:`Object<class_Object>`

描述
----

模板服务代理类

示例
----

属性
----

+-------------------------------+----------------------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`UrlTemple<class_TemplateUrlImageStore_property_UrlTemple>`           |
+-------------------------------+----------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`InvertLatitude<class_TemplateUrlImageStore_property_InvertLatitude>` |
+-------------------------------+----------------------------------------------------------------------------+

方法
----

+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>` | :ref:`GetDownloadUrl<class_TemplateUrlImageStore_method_GetDownloadUrl>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**     |
+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`Init<class_TemplateUrlImageStore_method_Init>` **(** :ref:`String<class_String>` host, :ref:`String<class_String>` name **)** |
+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>` | :ref:`GetLocalPath<class_TemplateUrlImageStore_method_GetLocalPath>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**         |
+-----------------------------+-------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_TemplateUrlImageStore_property_UrlTemple:

- :ref:`String<class_String>` **UrlTemple**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

代理地址

----

.. _class_TemplateUrlImageStore_property_InvertLatitude:

- :ref:`Boolean<class_Boolean>` **InvertLatitude**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否使用翻转，默认为false

----


方法说明
-------

.. _class_TemplateUrlImageStore_method_GetDownloadUrl:

- :ref:`String<class_String>` **GetDownloadUrl** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

根据瓦片计算瓦片的请求地址

----

.. _class_TemplateUrlImageStore_method_Init:

- :ref:`Void<class_Void>` **Init** **(** :ref:`String<class_String>` host, :ref:`String<class_String>` name **)**

保存在本地的路径

----

.. _class_TemplateUrlImageStore_method_GetLocalPath:

- :ref:`String<class_String>` **GetLocalPath** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

根据瓦片获取本地地址

----

