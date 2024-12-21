.. _class_ImagePyramidTileStore:

ImagePyramidTileStore 
===================

**Inherits:** :ref:`PyramidTileStore<class_PyramidTileStore>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------+------------------------------------------------+

方法
----

+---------------------------------------+---------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`           | :ref:`GetCacheDirPath<class_ImagePyramidTileStore_method_GetCacheDirPath>` **(** **)**                                          |
+---------------------------------------+---------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`           | :ref:`GetLocalPath<class_ImagePyramidTileStore_method_GetLocalPath>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**     |
+---------------------------------------+---------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`           | :ref:`GetDownloadUrl<class_ImagePyramidTileStore_method_GetDownloadUrl>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)** |
+---------------------------------------+---------------------------------------------------------------------------------------------------------------------------------+
| :ref:`IDisposable<class_IDisposable>` | :ref:`LoadFile<class_ImagePyramidTileStore_method_LoadFile>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**             |
+---------------------------------------+---------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------


方法说明
-------

.. _class_ImagePyramidTileStore_method_GetCacheDirPath:

- :ref:`String<class_String>` **GetCacheDirPath** **(** **)**

获取该图层瓦片的缓存路径

----

.. _class_ImagePyramidTileStore_method_GetLocalPath:

- :ref:`String<class_String>` **GetLocalPath** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

获取某个瓦片的本地缓存路径

----

.. _class_ImagePyramidTileStore_method_GetDownloadUrl:

- :ref:`String<class_String>` **GetDownloadUrl** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

获取某个瓦片的下载地址

----

.. _class_ImagePyramidTileStore_method_LoadFile:

- :ref:`IDisposable<class_IDisposable>` **LoadFile** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

加载某个瓦片

----

