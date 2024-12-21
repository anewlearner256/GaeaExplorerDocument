.. _class_GaeaResourceLoader:

GaeaResourceLoader 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----

资源加载

示例
----

属性
----

+-----------------------------------------------------+-------------------------------------------------------------+
| :ref:`GaeaResourceLoader<class_GaeaResourceLoader>` | :ref:`Instance<class_GaeaResourceLoader_property_Instance>` |
+-----------------------------------------------------+-------------------------------------------------------------+

方法
----

+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`UInt64<class_UInt64>`       | :ref:`GetResource<class_GaeaResourceLoader_method_GetResource>` **(** :ref:`String<class_String>` name **)**                                                                                            |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`LoadResourceFromUrl<class_GaeaResourceLoader_method_LoadResourceFromUrl>` **(** :ref:`String<class_String>` url, :ref:`String<class_String>` name, :ref:`Action`2<class_Action`2>` loadOver **)** |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`LoadResourceFromUrl<class_GaeaResourceLoader_method_LoadResourceFromUrl>` **(** :ref:`String<class_String>` url, :ref:`String<class_String>` name **)**                                           |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`UInt64<class_UInt64>`       | :ref:`LoadResourceFromBase64<class_GaeaResourceLoader_method_LoadResourceFromBase64>` **(** :ref:`String<class_String>` base64, :ref:`String<class_String>` name **)**                                  |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnLoadResourceFromUrl<class_GaeaResourceLoader_method_OnLoadResourceFromUrl>` **(** :ref:`Int32<class_Int32>` code, :ref:`String<class_String>` msg **)**                                         |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`LoadGLTFFromUrl<class_GaeaResourceLoader_method_LoadGLTFFromUrl>` **(** :ref:`String<class_String>` url, :ref:`String<class_String>` name, :ref:`Action`2<class_Action`2>` callback **)**         |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnLoadGLTFFromUrl<class_GaeaResourceLoader_method_OnLoadGLTFFromUrl>` **(** :ref:`Int32<class_Int32>` code, :ref:`UInt64[]<class_UInt64[]>` resources **)**                                       |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Reference<class_Reference>` | :ref:`LoadLoaclResource<class_GaeaResourceLoader_method_LoadLoaclResource>` **(** :ref:`String<class_String>` path **)**                                                                                |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`UInt64<class_UInt64>`       | :ref:`LoadLocalSceneID<class_GaeaResourceLoader_method_LoadLocalSceneID>` **(** :ref:`String<class_String>` path, :ref:`String<class_String>` name **)**                                                |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_GaeaResourceLoader_property_Instance:

- :ref:`GaeaResourceLoader<class_GaeaResourceLoader>` **Instance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

GaeaResourceLoader单例对象

----


方法说明
-------

.. _class_GaeaResourceLoader_method_GetResource:

- :ref:`UInt64<class_UInt64>` **GetResource** **(** :ref:`String<class_String>` name **)**

通过名称获取资源

----

.. _class_GaeaResourceLoader_method_LoadResourceFromUrl:

- :ref:`Void<class_Void>` **LoadResourceFromUrl** **(** :ref:`String<class_String>` url, :ref:`String<class_String>` name, :ref:`Action`2<class_Action`2>` loadOver **)**

通过URL路径加载资源到内存，并保存到本地目录

----

.. _class_GaeaResourceLoader_method_LoadResourceFromUrl:

- :ref:`Void<class_Void>` **LoadResourceFromUrl** **(** :ref:`String<class_String>` url, :ref:`String<class_String>` name **)**

从URL中加载资源并存储到文件系统

----

.. _class_GaeaResourceLoader_method_LoadResourceFromBase64:

- :ref:`UInt64<class_UInt64>` **LoadResourceFromBase64** **(** :ref:`String<class_String>` base64, :ref:`String<class_String>` name **)**

从流中加载资源并存储到文件系统

----

.. _class_GaeaResourceLoader_method_OnLoadResourceFromUrl:

- :ref:`Void<class_Void>` **OnLoadResourceFromUrl** **(** :ref:`Int32<class_Int32>` code, :ref:`String<class_String>` msg **)**

加载完资源后的网页回调，仅供网页使用

----

.. _class_GaeaResourceLoader_method_LoadGLTFFromUrl:

- :ref:`Void<class_Void>` **LoadGLTFFromUrl** **(** :ref:`String<class_String>` url, :ref:`String<class_String>` name, :ref:`Action`2<class_Action`2>` callback **)**

请求GLTF资源

----

.. _class_GaeaResourceLoader_method_OnLoadGLTFFromUrl:

- :ref:`Void<class_Void>` **OnLoadGLTFFromUrl** **(** :ref:`Int32<class_Int32>` code, :ref:`UInt64[]<class_UInt64[]>` resources **)**

加载完gltf后的网页回调，仅供网页使用

----

.. _class_GaeaResourceLoader_method_LoadLoaclResource:

- :ref:`Reference<class_Reference>` **LoadLoaclResource** **(** :ref:`String<class_String>` path **)**

加载本地引用资源

----

.. _class_GaeaResourceLoader_method_LoadLocalSceneID:

- :ref:`UInt64<class_UInt64>` **LoadLocalSceneID** **(** :ref:`String<class_String>` path, :ref:`String<class_String>` name **)**

网页端加载场景资源

----

