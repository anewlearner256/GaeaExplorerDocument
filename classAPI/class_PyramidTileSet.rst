.. _class_PyramidTileSet:

PyramidTileSet 
===================

**Inherits:** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`               | :ref:`DisposeTopTile<class_PyramidTileSet_property_DisposeTopTile>`     |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                 | :ref:`TileDrawDistance<class_PyramidTileSet_property_TileDrawDistance>` |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                 | :ref:`TileDrawSpread<class_PyramidTileSet_property_TileDrawSpread>`     |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                 | :ref:`North<class_PyramidTileSet_property_North>`                       |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                 | :ref:`East<class_PyramidTileSet_property_East>`                         |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                 | :ref:`South<class_PyramidTileSet_property_South>`                       |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                 | :ref:`West<class_PyramidTileSet_property_West>`                         |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`               | :ref:`Debug<class_PyramidTileSet_property_Debug>`                       |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`RenderPriority<class_RenderPriority>` | :ref:`Priority<class_PyramidTileSet_property_Priority>`                 |
+---------------------------------------------+-------------------------------------------------------------------------+

方法
----

+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`Initialize<class_PyramidTileSet_method_Initialize>` **(** **)**                                                                                                    |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`Render<class_PyramidTileSet_method_Render>` **(** **)**                                                                                                            |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`Update<class_PyramidTileSet_method_Update>` **(** **)**                                                                                                            |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                       | :ref:`GetStoreCount<class_PyramidTileSet_method_GetStoreCount>` **(** **)**                                                                                              |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PyramidTileStore<class_PyramidTileStore>` | :ref:`GetImageStore<class_PyramidTileSet_method_GetImageStore>` **(** :ref:`String<class_String>` name **)**                                                             |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`AddImageStore<class_PyramidTileSet_method_AddImageStore>` **(** :ref:`PyramidTileStore<class_PyramidTileStore>` store **)**                                        |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`RemoveImageStore<class_PyramidTileSet_method_RemoveImageStore>` **(** :ref:`PyramidTileStore<class_PyramidTileStore>` store **)**                                  |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`InsertImageStore<class_PyramidTileSet_method_InsertImageStore>` **(** :ref:`PyramidTileStore<class_PyramidTileStore>` store, :ref:`Int32<class_Int32>` index **)** |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_PyramidTileSet_property_DisposeTopTile:

- :ref:`Boolean<class_Boolean>` **DisposeTopTile**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_PyramidTileSet_property_TileDrawDistance:

- :ref:`Single<class_Single>` **TileDrawDistance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

可绘制瓦片的距离

----

.. _class_PyramidTileSet_property_TileDrawSpread:

- :ref:`Single<class_Single>` **TileDrawSpread**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

可绘制瓦片的跨度

----

.. _class_PyramidTileSet_property_North:

- :ref:`Double<class_Double>` **North**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

瓦片集的最北端

----

.. _class_PyramidTileSet_property_East:

- :ref:`Double<class_Double>` **East**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

瓦片集的最东端

----

.. _class_PyramidTileSet_property_South:

- :ref:`Double<class_Double>` **South**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

瓦片集的最南端

----

.. _class_PyramidTileSet_property_West:

- :ref:`Double<class_Double>` **West**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

瓦片集的最西端

----

.. _class_PyramidTileSet_property_Debug:

- :ref:`Boolean<class_Boolean>` **Debug**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

调试模式，开启后显示一些调试信息

----

.. _class_PyramidTileSet_property_Priority:

- :ref:`RenderPriority<class_RenderPriority>` **Priority**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

渲染优先级

----


方法说明
-------

.. _class_PyramidTileSet_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** **)**

初始化瓦片集

----

.. _class_PyramidTileSet_method_Render:

- :ref:`Void<class_Void>` **Render** **(** **)**

瓦片集的渲染在这个函数中进行

----

.. _class_PyramidTileSet_method_Update:

- :ref:`Void<class_Void>` **Update** **(** **)**

根据相机位置对金字塔瓦片进行更新

----

.. _class_PyramidTileSet_method_GetStoreCount:

- :ref:`Int32<class_Int32>` **GetStoreCount** **(** **)**

获取图层数量

----

.. _class_PyramidTileSet_method_GetImageStore:

- :ref:`PyramidTileStore<class_PyramidTileStore>` **GetImageStore** **(** :ref:`String<class_String>` name **)**

获取图层

----

.. _class_PyramidTileSet_method_AddImageStore:

- :ref:`Void<class_Void>` **AddImageStore** **(** :ref:`PyramidTileStore<class_PyramidTileStore>` store **)**

加载图层

----

.. _class_PyramidTileSet_method_RemoveImageStore:

- :ref:`Void<class_Void>` **RemoveImageStore** **(** :ref:`PyramidTileStore<class_PyramidTileStore>` store **)**

删除图层

----

.. _class_PyramidTileSet_method_InsertImageStore:

- :ref:`Void<class_Void>` **InsertImageStore** **(** :ref:`PyramidTileStore<class_PyramidTileStore>` store, :ref:`Int32<class_Int32>` index **)**

插入图层

----

