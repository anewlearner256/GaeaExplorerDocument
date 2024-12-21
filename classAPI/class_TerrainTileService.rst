.. _class_TerrainTileService:

TerrainTileService 
===================

**Inherits:** :ref:`Object<class_Object>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`TerrainAccessor<class_TerrainAccessor>` | :ref:`Owner<class_TerrainTileService_property_Owner>`                                       |
+-----------------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`                   | :ref:`ServerUrl<class_TerrainTileService_property_ServerUrl>`                               |
+-----------------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`                   | :ref:`DataSet<class_TerrainTileService_property_DataSet>`                                   |
+-----------------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                   | :ref:`LevelZeroTileSizeDegrees<class_TerrainTileService_property_LevelZeroTileSizeDegrees>` |
+-----------------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                     | :ref:`SamplesPerTile<class_TerrainTileService_property_SamplesPerTile>`                     |
+-----------------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`                   | :ref:`FileExtension<class_TerrainTileService_property_FileExtension>`                       |
+-----------------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`                   | :ref:`TerrainTileDirectory<class_TerrainTileService_property_TerrainTileDirectory>`         |
+-----------------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`TimeSpan<class_TimeSpan>`               | :ref:`TerrainTileRetryInterval<class_TerrainTileService_property_TerrainTileRetryInterval>` |
+-----------------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`                   | :ref:`DataType<class_TerrainTileService_property_DataType>`                                 |
+-----------------------------------------------+---------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                 | :ref:`IsFile<class_TerrainTileService_property_IsFile>`                                     |
+-----------------------------------------------+---------------------------------------------------------------------------------------------+

方法
----

+---------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`               | :ref:`AddInValidValue<class_TerrainTileService_method_AddInValidValue>` **(** :ref:`Single<class_Single>` value **)**                                                                                          |
+---------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`TerrainTile<class_TerrainTile>` | :ref:`GetTerrainTile<class_TerrainTileService_method_GetTerrainTile>` **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude, :ref:`Double<class_Double>` samplesPerDegree **)**    |
+---------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`TerrainTile<class_TerrainTile>` | :ref:`GetTerrainTile<class_TerrainTileService_method_GetTerrainTile>` **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude, :ref:`Int32<class_Int32>` targetLevel **)**           |
+---------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`             | :ref:`ComputeTerrainTileLevel<class_TerrainTileService_method_ComputeTerrainTileLevel>` **(** :ref:`Double<class_Double>` samplesPerDegree **)**                                                               |
+---------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`             | :ref:`GetColFromLongitude<class_TerrainTileService_method_GetColFromLongitude>` **(** :ref:`Double<class_Double>` longitude, :ref:`Double<class_Double>` tileSize, :ref:`Boolean<class_Boolean>` inverse **)** |
+---------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`             | :ref:`GetRowFromLatitude<class_TerrainTileService_method_GetRowFromLatitude>` **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` tileSize, :ref:`Boolean<class_Boolean>` inverse **)**    |
+---------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`               | :ref:`Dispose<class_TerrainTileService_method_Dispose>` **(** **)**                                                                                                                                            |
+---------------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_TerrainTileService_property_Owner:

- :ref:`TerrainAccessor<class_TerrainAccessor>` **Owner**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

父地形服务

----

.. _class_TerrainTileService_property_ServerUrl:

- :ref:`String<class_String>` **ServerUrl**

+----------+---+
| *Getter* |   |
+----------+---+

服务地址

----

.. _class_TerrainTileService_property_DataSet:

- :ref:`String<class_String>` **DataSet**

+----------+---+
| *Getter* |   |
+----------+---+

数据集的本地路径

----

.. _class_TerrainTileService_property_LevelZeroTileSizeDegrees:

- :ref:`Double<class_Double>` **LevelZeroTileSizeDegrees**

+----------+---+
| *Getter* |   |
+----------+---+

0级瓦片的经纬度跨度

----

.. _class_TerrainTileService_property_SamplesPerTile:

- :ref:`Int32<class_Int32>` **SamplesPerTile**

+----------+---+
| *Getter* |   |
+----------+---+

每个瓦片的采样数量

----

.. _class_TerrainTileService_property_FileExtension:

- :ref:`String<class_String>` **FileExtension**

+----------+---+
| *Getter* |   |
+----------+---+

地形数据文件拓展名

----

.. _class_TerrainTileService_property_TerrainTileDirectory:

- :ref:`String<class_String>` **TerrainTileDirectory**

+----------+---+
| *Getter* |   |
+----------+---+

地形文件存储目录

----

.. _class_TerrainTileService_property_TerrainTileRetryInterval:

- :ref:`TimeSpan<class_TimeSpan>` **TerrainTileRetryInterval**

+----------+---+
| *Getter* |   |
+----------+---+

地形瓦片重试间隔

----

.. _class_TerrainTileService_property_DataType:

- :ref:`String<class_String>` **DataType**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

数据类型

----

.. _class_TerrainTileService_property_IsFile:

- :ref:`Boolean<class_Boolean>` **IsFile**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

指示Terrain文件是多个还是单个文件
Indicates whether the Terrain file is multiple or a single file

----


方法说明
-------

.. _class_TerrainTileService_method_AddInValidValue:

- :ref:`Void<class_Void>` **AddInValidValue** **(** :ref:`Single<class_Single>` value **)**

新增无效值

----

.. _class_TerrainTileService_method_GetTerrainTile:

- :ref:`TerrainTile<class_TerrainTile>` **GetTerrainTile** **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude, :ref:`Double<class_Double>` samplesPerDegree **)**

获取某个级别下指定位置所属的地形瓦片

----

.. _class_TerrainTileService_method_GetTerrainTile:

- :ref:`TerrainTile<class_TerrainTile>` **GetTerrainTile** **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude, :ref:`Int32<class_Int32>` targetLevel **)**

获取某个级别下指定位置所属的地形瓦片

----

.. _class_TerrainTileService_method_ComputeTerrainTileLevel:

- :ref:`Int32<class_Int32>` **ComputeTerrainTileLevel** **(** :ref:`Double<class_Double>` samplesPerDegree **)**

根据采样密度计算地形瓦片的级别

----

.. _class_TerrainTileService_method_GetColFromLongitude:

- :ref:`Int32<class_Int32>` **GetColFromLongitude** **(** :ref:`Double<class_Double>` longitude, :ref:`Double<class_Double>` tileSize, :ref:`Boolean<class_Boolean>` inverse **)**

获取某个经度在指定的瓦片级别下所属的列号

----

.. _class_TerrainTileService_method_GetRowFromLatitude:

- :ref:`Int32<class_Int32>` **GetRowFromLatitude** **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` tileSize, :ref:`Boolean<class_Boolean>` inverse **)**

获取某个纬度在指定的瓦片级别下所属的行号

----

.. _class_TerrainTileService_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**

地形服务被释放时调用此函数

----

