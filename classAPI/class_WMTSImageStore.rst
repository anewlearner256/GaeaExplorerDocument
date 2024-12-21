.. _class_WMTSImageStore:

WMTSImageStore 
===================

**Inherits:** :ref:`ImagePyramidTileStore<class_ImagePyramidTileStore>` **<** :ref:`PyramidTileStore<class_PyramidTileStore>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+---------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Capabilitie<class_Capabilitie>` | :ref:`CurrentCapabilitie<class_WMTSImageStore_property_CurrentCapabilitie>` |
+---------------------------------------+-----------------------------------------------------------------------------+

方法
----

+-------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                   | :ref:`Init<class_WMTSImageStore_method_Init>` **(** :ref:`Capabilitie<class_Capabilitie>` capabilitie **)**                                                             |
+-------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Capabilitie[]<class_Capabilitie[]>` | :ref:`GetWMTSCapabilities<class_WMTSImageStore_method_GetWMTSCapabilities>` **(** :ref:`String<class_String>` host **)**                                                |
+-------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                   | :ref:`SaveCapabilities<class_WMTSImageStore_method_SaveCapabilities>` **(** :ref:`String<class_String>` host, :ref:`String<class_String>` xmlstr **)**                  |
+-------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Capabilitie[]<class_Capabilitie[]>` | :ref:`ParserXml2Capabilities<class_WMTSImageStore_method_ParserXml2Capabilities>` **(** :ref:`String<class_String>` ServerUri, :ref:`String<class_String>` xmlstr **)** |
+-------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Capabilitie<class_Capabilitie>`     | :ref:`GetLayerByName<class_WMTSImageStore_method_GetLayerByName>` **(** :ref:`String<class_String>` ServerUri, :ref:`String<class_String>` name **)**                   |
+-------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`               | :ref:`GetLocalPath<class_WMTSImageStore_method_GetLocalPath>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**                                                    |
+-------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`               | :ref:`GetDownloadUrl<class_WMTSImageStore_method_GetDownloadUrl>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**                                                |
+-------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                   | :ref:`DeleteCapabilitie<class_WMTSImageStore_method_DeleteCapabilitie>` **(** :ref:`String<class_String>` host, :ref:`Boolean<class_Boolean>` OnlyCapabilitie **)**     |
+-------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_WMTSImageStore_property_CurrentCapabilitie:

- :ref:`Capabilitie<class_Capabilitie>` **CurrentCapabilitie**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

wmts服务的服务元数据

----


方法说明
-------

.. _class_WMTSImageStore_method_Init:

- :ref:`Void<class_Void>` **Init** **(** :ref:`Capabilitie<class_Capabilitie>` capabilitie **)**

初始化wms服务

----

.. _class_WMTSImageStore_method_GetWMTSCapabilities:

- :ref:`Capabilitie[]<class_Capabilitie[]>` **GetWMTSCapabilities** **(** :ref:`String<class_String>` host **)**

取得本地Capabilities中的内容

----

.. _class_WMTSImageStore_method_SaveCapabilities:

- :ref:`Void<class_Void>` **SaveCapabilities** **(** :ref:`String<class_String>` host, :ref:`String<class_String>` xmlstr **)**

保存所有的Capabilities到本地文件

----

.. _class_WMTSImageStore_method_ParserXml2Capabilities:

- :ref:`Capabilitie[]<class_Capabilitie[]>` **ParserXml2Capabilities** **(** :ref:`String<class_String>` ServerUri, :ref:`String<class_String>` xmlstr **)**

解析服务元数据

----

.. _class_WMTSImageStore_method_GetLayerByName:

- :ref:`Capabilitie<class_Capabilitie>` **GetLayerByName** **(** :ref:`String<class_String>` ServerUri, :ref:`String<class_String>` name **)**

通过名称获取指定的服务元数据

----

.. _class_WMTSImageStore_method_GetLocalPath:

- :ref:`String<class_String>` **GetLocalPath** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

获取某个瓦片的本地缓存路径

----

.. _class_WMTSImageStore_method_GetDownloadUrl:

- :ref:`String<class_String>` **GetDownloadUrl** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

获取某个瓦片的下载地址

----

.. _class_WMTSImageStore_method_DeleteCapabilitie:

- :ref:`Void<class_Void>` **DeleteCapabilitie** **(** :ref:`String<class_String>` host, :ref:`Boolean<class_Boolean>` OnlyCapabilitie **)**

删除服务元数据

----

