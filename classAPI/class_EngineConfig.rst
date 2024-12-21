.. _class_EngineConfig:

EngineConfig 
===================

**Inherits:** :ref:`ConfigFile<class_ConfigFile>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

描述
----

系统配置

示例
----

属性
----

+-----------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`EngineConfig<class_EngineConfig>` | :ref:`Instance<class_EngineConfig_property_Instance>`                                       |
+-----------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`             | :ref:`AssetHost<class_EngineConfig_property_AssetHost>`                                     |
+-----------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`             | :ref:`ServerHost<class_EngineConfig_property_ServerHost>`                                   |
+-----------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`             | :ref:`DefaultImageServer<class_EngineConfig_property_DefaultImageServer>`                   |
+-----------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`             | :ref:`DefaultTerrainServer<class_EngineConfig_property_DefaultTerrainServer>`               |
+-----------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`             | :ref:`DefaultGlobalOverview<class_EngineConfig_property_DefaultGlobalOverview>`             |
+-----------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`             | :ref:`DefaultImageServerExtension<class_EngineConfig_property_DefaultImageServerExtension>` |
+-----------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`           | :ref:`HasConfigCache<class_EngineConfig_property_HasConfigCache>`                           |
+-----------------------------------------+---------------------------------------------------------------------------------------------+

方法
----

+-------------------------------+------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`LoadConfig<class_EngineConfig_method_LoadConfig>` **(** :ref:`String<class_String>` userConfig **)** |
+-------------------------------+------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_EngineConfig_property_Instance:

- :ref:`EngineConfig<class_EngineConfig>` **Instance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

EngineConfig的单例对象

----

.. _class_EngineConfig_property_AssetHost:

- :ref:`String<class_String>` **AssetHost**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

内置资源请求地址

----

.. _class_EngineConfig_property_ServerHost:

- :ref:`String<class_String>` **ServerHost**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

服务地址

----

.. _class_EngineConfig_property_DefaultImageServer:

- :ref:`String<class_String>` **DefaultImageServer**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

默认影像服务

----

.. _class_EngineConfig_property_DefaultTerrainServer:

- :ref:`String<class_String>` **DefaultTerrainServer**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

默认地形服务

----

.. _class_EngineConfig_property_DefaultGlobalOverview:

- :ref:`String<class_String>` **DefaultGlobalOverview**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

默认的全球概图

----

.. _class_EngineConfig_property_DefaultImageServerExtension:

- :ref:`String<class_String>` **DefaultImageServerExtension**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

默认的图片格式

----

.. _class_EngineConfig_property_HasConfigCache:

- :ref:`Boolean<class_Boolean>` **HasConfigCache**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_EngineConfig_method_LoadConfig:

- :ref:`Boolean<class_Boolean>` **LoadConfig** **(** :ref:`String<class_String>` userConfig **)**

从字符串文本加载配置

----

