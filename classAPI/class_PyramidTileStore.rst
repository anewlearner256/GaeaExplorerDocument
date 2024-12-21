.. _class_PyramidTileStore:

PyramidTileStore 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                           | :ref:`SplitDirectionRefreshFlag<class_PyramidTileStore_property_SplitDirectionRefreshFlag>`       |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                           | :ref:`SplitDirection<class_PyramidTileStore_property_SplitDirection>`                             |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`                         | :ref:`Name<class_PyramidTileStore_property_Name>`                                                 |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`                       | :ref:`LevelRange<class_PyramidTileStore_property_LevelRange>`                                     |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                         | :ref:`Transparency<class_PyramidTileStore_property_Transparency>`                                 |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                         | :ref:`LevelZeroTileSizeDegrees<class_PyramidTileStore_property_LevelZeroTileSizeDegrees>`         |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                           | :ref:`StartLevel<class_PyramidTileStore_property_StartLevel>`                                     |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                           | :ref:`LevelCount<class_PyramidTileStore_property_LevelCount>`                                     |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`ImageExtensionEnum<class_ImageExtensionEnum>` | :ref:`ImageExtension<class_PyramidTileStore_property_ImageExtension>`                             |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                         | :ref:`North<class_PyramidTileStore_property_North>`                                               |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                         | :ref:`West<class_PyramidTileStore_property_West>`                                                 |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                         | :ref:`South<class_PyramidTileStore_property_South>`                                               |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                         | :ref:`East<class_PyramidTileStore_property_East>`                                                 |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                       | :ref:`Visible<class_PyramidTileStore_property_Visible>`                                           |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                           | :ref:`ImageTransparencyRefreshFlag<class_PyramidTileStore_property_ImageTransparencyRefreshFlag>` |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                         | :ref:`ImageTransparency<class_PyramidTileStore_property_ImageTransparency>`                       |
+-----------------------------------------------------+---------------------------------------------------------------------------------------------------+

方法
----

+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`ImageExtensionEnum<class_ImageExtensionEnum>` | :ref:`SetExtensionByStr<class_PyramidTileStore_method_SetExtensionByStr>` **(** :ref:`String<class_String>` ext **)**                                                                                                    |
+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32[]<class_Int32[]>`                       | :ref:`GetDisplayViewportIds<class_PyramidTileStore_method_GetDisplayViewportIds>` **(** **)**                                                                                                                            |
+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                             | :ref:`AddDisplayViewportId<class_PyramidTileStore_method_AddDisplayViewportId>` **(** :ref:`Int32<class_Int32>` viewportId **)**                                                                                         |
+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                             | :ref:`RemoveDisplayViewportId<class_PyramidTileStore_method_RemoveDisplayViewportId>` **(** :ref:`Int32<class_Int32>` viewportId **)**                                                                                   |
+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                             | :ref:`ClearDisplayViewportId<class_PyramidTileStore_method_ClearDisplayViewportId>` **(** **)**                                                                                                                          |
+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                             | :ref:`SetBoundingBox<class_PyramidTileStore_method_SetBoundingBox>` **(** :ref:`Double<class_Double>` north, :ref:`Double<class_Double>` south, :ref:`Double<class_Double>` east, :ref:`Double<class_Double>` west **)** |
+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`                         | :ref:`GetLocalPath<class_PyramidTileStore_method_GetLocalPath>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**                                                                                                   |
+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`                         | :ref:`GetCacheDirPath<class_PyramidTileStore_method_GetCacheDirPath>` **(** **)**                                                                                                                                        |
+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`                         | :ref:`GetDownloadUrl<class_PyramidTileStore_method_GetDownloadUrl>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**                                                                                               |
+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`IDisposable<class_IDisposable>`               | :ref:`LoadFile<class_PyramidTileStore_method_LoadFile>` **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**                                                                                                           |
+-----------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_PyramidTileStore_property_SplitDirectionRefreshFlag:

- :ref:`Int32<class_Int32>` **SplitDirectionRefreshFlag**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_PyramidTileStore_property_SplitDirection:

- :ref:`Int32<class_Int32>` **SplitDirection**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

卷帘状态下，所加的图层的位置，0加在两边，1加在左边，2加在右边

----

.. _class_PyramidTileStore_property_Name:

- :ref:`String<class_String>` **Name**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

金字塔瓦片图层名

----

.. _class_PyramidTileStore_property_LevelRange:

- :ref:`Vector2<class_Vector2>` **LevelRange**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

金字塔瓦片的层级范围

----

.. _class_PyramidTileStore_property_Transparency:

- :ref:`Single<class_Single>` **Transparency**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

图层透明度

----

.. _class_PyramidTileStore_property_LevelZeroTileSizeDegrees:

- :ref:`Double<class_Double>` **LevelZeroTileSizeDegrees**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

0级瓦片的经纬度跨度

----

.. _class_PyramidTileStore_property_StartLevel:

- :ref:`Int32<class_Int32>` **StartLevel**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

瓦片服务的起始层

----

.. _class_PyramidTileStore_property_LevelCount:

- :ref:`Int32<class_Int32>` **LevelCount**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

详细级别数

----

.. _class_PyramidTileStore_property_ImageExtension:

- :ref:`ImageExtensionEnum<class_ImageExtensionEnum>` **ImageExtension**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

源图像文件格式的文件扩展名

----

.. _class_PyramidTileStore_property_North:

- :ref:`Double<class_Double>` **North**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

该瓦片图层北部边界

----

.. _class_PyramidTileStore_property_West:

- :ref:`Double<class_Double>` **West**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

该瓦片图层西部边界

----

.. _class_PyramidTileStore_property_South:

- :ref:`Double<class_Double>` **South**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

该瓦片图层南部边界

----

.. _class_PyramidTileStore_property_East:

- :ref:`Double<class_Double>` **East**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

该瓦片图层东部边界

----

.. _class_PyramidTileStore_property_Visible:

- :ref:`Boolean<class_Boolean>` **Visible**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

隐藏显示某个图层

----

.. _class_PyramidTileStore_property_ImageTransparencyRefreshFlag:

- :ref:`Int32<class_Int32>` **ImageTransparencyRefreshFlag**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

该图层的透明度刷新标志

----

.. _class_PyramidTileStore_property_ImageTransparency:

- :ref:`Single<class_Single>` **ImageTransparency**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

该图层的透明度

----


方法说明
-------

.. _class_PyramidTileStore_method_SetExtensionByStr:

- :ref:`ImageExtensionEnum<class_ImageExtensionEnum>` **SetExtensionByStr** **(** :ref:`String<class_String>` ext **)**

设置源图像文件格式的文件扩展名

----

.. _class_PyramidTileStore_method_GetDisplayViewportIds:

- :ref:`Int32[]<class_Int32[]>` **GetDisplayViewportIds** **(** **)**



----

.. _class_PyramidTileStore_method_AddDisplayViewportId:

- :ref:`Void<class_Void>` **AddDisplayViewportId** **(** :ref:`Int32<class_Int32>` viewportId **)**



----

.. _class_PyramidTileStore_method_RemoveDisplayViewportId:

- :ref:`Void<class_Void>` **RemoveDisplayViewportId** **(** :ref:`Int32<class_Int32>` viewportId **)**



----

.. _class_PyramidTileStore_method_ClearDisplayViewportId:

- :ref:`Void<class_Void>` **ClearDisplayViewportId** **(** **)**



----

.. _class_PyramidTileStore_method_SetBoundingBox:

- :ref:`Void<class_Void>` **SetBoundingBox** **(** :ref:`Double<class_Double>` north, :ref:`Double<class_Double>` south, :ref:`Double<class_Double>` east, :ref:`Double<class_Double>` west **)**

设置瓦片图层的边界范围

----

.. _class_PyramidTileStore_method_GetLocalPath:

- :ref:`String<class_String>` **GetLocalPath** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

获取某个瓦片的本地缓存路径

----

.. _class_PyramidTileStore_method_GetCacheDirPath:

- :ref:`String<class_String>` **GetCacheDirPath** **(** **)**

获取该图层瓦片的缓存路径

----

.. _class_PyramidTileStore_method_GetDownloadUrl:

- :ref:`String<class_String>` **GetDownloadUrl** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

获取某个瓦片的下载地址

----

.. _class_PyramidTileStore_method_LoadFile:

- :ref:`IDisposable<class_IDisposable>` **LoadFile** **(** :ref:`PyramidTile<class_PyramidTile>` tile **)**

加载某个瓦片

----

