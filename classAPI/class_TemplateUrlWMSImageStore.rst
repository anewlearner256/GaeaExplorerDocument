.. _class_TemplateUrlWMSImageStore:

TemplateUrlWMSImageStore 
===================

**Inherits:** :ref:`ImagePyramidTileStore<class_ImagePyramidTileStore>` **<** :ref:`PyramidTileStore<class_PyramidTileStore>` **<** :ref:`Object<class_Object>`

描述
----

模板服务代理类

示例
----

属性
----

+-----------------------------+---------------------------------------------------------------------+
| :ref:`String<class_String>` | :ref:`UrlTemple<class_TemplateUrlWMSImageStore_property_UrlTemple>` |
+-----------------------------+---------------------------------------------------------------------+

方法
----

+-----------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`Init<class_TemplateUrlWMSImageStore_method_Init>` **(** :ref:`String<class_String>` host, :ref:`String<class_String>` name **)** |
+-----------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>` | :ref:`GetLocalPath<class_TemplateUrlWMSImageStore_method_GetLocalPath>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**         |
+-----------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>` | :ref:`GetDownloadUrl<class_TemplateUrlWMSImageStore_method_GetDownloadUrl>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**     |
+-----------------------------+----------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_TemplateUrlWMSImageStore_property_UrlTemple:

- :ref:`String<class_String>` **UrlTemple**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

代理地址

----


方法说明
-------

.. _class_TemplateUrlWMSImageStore_method_Init:

- :ref:`Void<class_Void>` **Init** **(** :ref:`String<class_String>` host, :ref:`String<class_String>` name **)**

保存在本地的路径

----

.. _class_TemplateUrlWMSImageStore_method_GetLocalPath:

- :ref:`String<class_String>` **GetLocalPath** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

根据瓦片获取本地路径

----

.. _class_TemplateUrlWMSImageStore_method_GetDownloadUrl:

- :ref:`String<class_String>` **GetDownloadUrl** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

根据瓦片获取瓦片的请求地址

----

