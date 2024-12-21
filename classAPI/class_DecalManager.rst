.. _class_DecalManager:

DecalManager 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------+
| :ref:`DecalManager<class_DecalManager>`                   | :ref:`Instance<class_DecalManager_property_Instance>`                                         |
+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                                 | :ref:`UpdateFlag<class_DecalManager_property_UpdateFlag>`                                     |
+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                               | :ref:`TerrainMapInterpolationValue<class_DecalManager_property_TerrainMapInterpolationValue>` |
+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                             | :ref:`OpenColor<class_DecalManager_property_OpenColor>`                                       |
+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`                             | :ref:`ColorRamp<class_DecalManager_property_ColorRamp>`                                       |
+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------+
| :ref:`PixelToHeightModeEnum<class_PixelToHeightModeEnum>` | :ref:`PixelToHeightMode<class_DecalManager_property_PixelToHeightMode>`                       |
+-----------------------------------------------------------+-----------------------------------------------------------------------------------------------+

方法
----

+-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`AddItem<class_DecalManager_method_AddItem>` **(** :ref:`DecalItem<class_DecalItem>` item **)**                                                                                                                                                                                                                                                      |
+-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`RemoveItem<class_DecalManager_method_RemoveItem>` **(** :ref:`DecalItem<class_DecalItem>` item **)**                                                                                                                                                                                                                                                |
+-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`DecalItem<class_DecalItem>` | :ref:`CreateItem<class_DecalManager_method_CreateItem>` **(** :ref:`Double<class_Double>` north, :ref:`Double<class_Double>` south, :ref:`Double<class_Double>` west, :ref:`Double<class_Double>` east, :ref:`Color<class_Color>` color, :ref:`String<class_String>` baseImage **)**                                                                      |
+-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`DecalItem<class_DecalItem>` | :ref:`CreateTerrainItem<class_DecalManager_method_CreateTerrainItem>` **(** :ref:`Double<class_Double>` north, :ref:`Double<class_Double>` south, :ref:`Double<class_Double>` west, :ref:`Double<class_Double>` east, :ref:`Single<class_Single>` invalidValue, :ref:`String<class_String>` terrainImage, :ref:`Vector2<class_Vector2>` minMaxValue **)** |
+-----------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DecalManager_property_Instance:

- :ref:`DecalManager<class_DecalManager>` **Instance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DecalManager_property_UpdateFlag:

- :ref:`Int32<class_Int32>` **UpdateFlag**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DecalManager_property_TerrainMapInterpolationValue:

- :ref:`Single<class_Single>` **TerrainMapInterpolationValue**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

当存在两个地形贴花时，取值时的比例系数

----

.. _class_DecalManager_property_OpenColor:

- :ref:`Boolean<class_Boolean>` **OpenColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_DecalManager_property_ColorRamp:

- :ref:`Vector2<class_Vector2>` **ColorRamp**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_DecalManager_property_PixelToHeightMode:

- :ref:`PixelToHeightModeEnum<class_PixelToHeightModeEnum>` **PixelToHeightMode**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

像素值转为高度值的方式

----


方法说明
-------

.. _class_DecalManager_method_AddItem:

- :ref:`Void<class_Void>` **AddItem** **(** :ref:`DecalItem<class_DecalItem>` item **)**

添加一个贴花

----

.. _class_DecalManager_method_RemoveItem:

- :ref:`Void<class_Void>` **RemoveItem** **(** :ref:`DecalItem<class_DecalItem>` item **)**

移除一个贴花

----

.. _class_DecalManager_method_CreateItem:

- :ref:`DecalItem<class_DecalItem>` **CreateItem** **(** :ref:`Double<class_Double>` north, :ref:`Double<class_Double>` south, :ref:`Double<class_Double>` west, :ref:`Double<class_Double>` east, :ref:`Color<class_Color>` color, :ref:`String<class_String>` baseImage **)**

创建一个影像贴花

----

.. _class_DecalManager_method_CreateTerrainItem:

- :ref:`DecalItem<class_DecalItem>` **CreateTerrainItem** **(** :ref:`Double<class_Double>` north, :ref:`Double<class_Double>` south, :ref:`Double<class_Double>` west, :ref:`Double<class_Double>` east, :ref:`Single<class_Single>` invalidValue, :ref:`String<class_String>` terrainImage, :ref:`Vector2<class_Vector2>` minMaxValue **)**

创建一个地形贴花

----

