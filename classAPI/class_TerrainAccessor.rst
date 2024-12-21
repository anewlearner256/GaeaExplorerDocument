.. _class_TerrainAccessor:

TerrainAccessor 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------------------------------+------------------------------------------------------------------------------+
| :ref:`TerrainAccessor<class_TerrainAccessor>`             | :ref:`Owner<class_TerrainAccessor_property_Owner>`                           |
+-----------------------------------------------------------+------------------------------------------------------------------------------+
| :ref:`String<class_String>`                               | :ref:`Name<class_TerrainAccessor_property_Name>`                             |
+-----------------------------------------------------------+------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                               | :ref:`North<class_TerrainAccessor_property_North>`                           |
+-----------------------------------------------------------+------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                               | :ref:`South<class_TerrainAccessor_property_South>`                           |
+-----------------------------------------------------------+------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                               | :ref:`West<class_TerrainAccessor_property_West>`                             |
+-----------------------------------------------------------+------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                               | :ref:`East<class_TerrainAccessor_property_East>`                             |
+-----------------------------------------------------------+------------------------------------------------------------------------------+
| :ref:`GeographicBoundingBox<class_GeographicBoundingBox>` | :ref:`BoundingBox<class_TerrainAccessor_property_BoundingBox>`               |
+-----------------------------------------------------------+------------------------------------------------------------------------------+
| :ref:`TerrainTileService<class_TerrainTileService>`       | :ref:`TerrainTileService<class_TerrainAccessor_property_TerrainTileService>` |
+-----------------------------------------------------------+------------------------------------------------------------------------------+

方法
----

+-----------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                             | :ref:`AddSubTerrainServer<class_TerrainAccessor_method_AddSubTerrainServer>` **(** :ref:`TerrainAccessor<class_TerrainAccessor>` terrain **)**                                                                                    |
+-----------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                             | :ref:`RemoveSubTerrainServer<class_TerrainAccessor_method_RemoveSubTerrainServer>` **(** :ref:`TerrainAccessor<class_TerrainAccessor>` terrain **)**                                                                              |
+-----------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                         | :ref:`GetElevationAt<class_TerrainAccessor_method_GetElevationAt>` **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude, :ref:`Double<class_Double>` targetSamplesPerDegree **)**                    |
+-----------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                         | :ref:`GetElevationByCurrentViewRangeAt<class_TerrainAccessor_method_GetElevationByCurrentViewRangeAt>` **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude **)**                                    |
+-----------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                             | :ref:`Dispose<class_TerrainAccessor_method_Dispose>` **(** **)**                                                                                                                                                                  |
+-----------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PyramidTileTerrain<class_PyramidTileTerrain>` | :ref:`GetPyramidTileTerrain<class_TerrainAccessor_method_GetPyramidTileTerrain>` **(** :ref:`ImagePyramidTile<class_ImagePyramidTile>` tile **)**                                                                                 |
+-----------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`TerrainTile<class_TerrainTile>`               | :ref:`GetTileByLatlonLevelWithCache<class_TerrainAccessor_method_GetTileByLatlonLevelWithCache>` **(** :ref:`Double<class_Double>` samplesPerDegree, :ref:`Double<class_Double>` curLat, :ref:`Double<class_Double>` curLon **)** |
+-----------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                         | :ref:`GetElevationValue<class_TerrainAccessor_method_GetElevationValue>` **(** :ref:`Double<class_Double>` samplesPerDegree, :ref:`Double<class_Double>` curLat, :ref:`Double<class_Double>` curLon **)**                         |
+-----------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`IEnumerator<class_IEnumerator>`               | :ref:`GetElevationArrayByTileCo<class_TerrainAccessor_method_GetElevationArrayByTileCo>` **(** :ref:`ImagePyramidTile<class_ImagePyramidTile>` tile **)**                                                                         |
+-----------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_TerrainAccessor_property_Owner:

- :ref:`TerrainAccessor<class_TerrainAccessor>` **Owner**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

地形访问器的所有者

----

.. _class_TerrainAccessor_property_Name:

- :ref:`String<class_String>` **Name**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

待删除

----

.. _class_TerrainAccessor_property_North:

- :ref:`Double<class_Double>` **North**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

地形访问器的北部边界

----

.. _class_TerrainAccessor_property_South:

- :ref:`Double<class_Double>` **South**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

地形访问器的南部边界

----

.. _class_TerrainAccessor_property_West:

- :ref:`Double<class_Double>` **West**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

地形访问器的西部边界

----

.. _class_TerrainAccessor_property_East:

- :ref:`Double<class_Double>` **East**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

地形访问器的东部边界

----

.. _class_TerrainAccessor_property_BoundingBox:

- :ref:`GeographicBoundingBox<class_GeographicBoundingBox>` **BoundingBox**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

地形访问器的边界盒

----

.. _class_TerrainAccessor_property_TerrainTileService:

- :ref:`TerrainTileService<class_TerrainTileService>` **TerrainTileService**

+----------+---+
| *Getter* |   |
+----------+---+

所使用的地形服务

----


方法说明
-------

.. _class_TerrainAccessor_method_AddSubTerrainServer:

- :ref:`Void<class_Void>` **AddSubTerrainServer** **(** :ref:`TerrainAccessor<class_TerrainAccessor>` terrain **)**

添加子地形访问器

----

.. _class_TerrainAccessor_method_RemoveSubTerrainServer:

- :ref:`Void<class_Void>` **RemoveSubTerrainServer** **(** :ref:`TerrainAccessor<class_TerrainAccessor>` terrain **)**

移除子地形访问器

----

.. _class_TerrainAccessor_method_GetElevationAt:

- :ref:`Single<class_Single>` **GetElevationAt** **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude, :ref:`Double<class_Double>` targetSamplesPerDegree **)**

获取指定位置在指定的采样密度下的海拔高度

----

.. _class_TerrainAccessor_method_GetElevationByCurrentViewRangeAt:

- :ref:`Single<class_Single>` **GetElevationByCurrentViewRangeAt** **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude **)**

根据当前视图范围获取指定位置的海拔高度

----

.. _class_TerrainAccessor_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**

当被释放时调用此函数

----

.. _class_TerrainAccessor_method_GetPyramidTileTerrain:

- :ref:`PyramidTileTerrain<class_PyramidTileTerrain>` **GetPyramidTileTerrain** **(** :ref:`ImagePyramidTile<class_ImagePyramidTile>` tile **)**

获取指定影像瓦片对应的地形瓦片

----

.. _class_TerrainAccessor_method_GetTileByLatlonLevelWithCache:

- :ref:`TerrainTile<class_TerrainTile>` **GetTileByLatlonLevelWithCache** **(** :ref:`Double<class_Double>` samplesPerDegree, :ref:`Double<class_Double>` curLat, :ref:`Double<class_Double>` curLon **)**

获取某个级别下指定位置所属的地形瓦片

----

.. _class_TerrainAccessor_method_GetElevationValue:

- :ref:`Single<class_Single>` **GetElevationValue** **(** :ref:`Double<class_Double>` samplesPerDegree, :ref:`Double<class_Double>` curLat, :ref:`Double<class_Double>` curLon **)**

获取指定位置在某个级别下的地形高度

----

.. _class_TerrainAccessor_method_GetElevationArrayByTileCo:

- :ref:`IEnumerator<class_IEnumerator>` **GetElevationArrayByTileCo** **(** :ref:`ImagePyramidTile<class_ImagePyramidTile>` tile **)**

获取指定瓦片对应的地形数据

----

