.. _class_VolumeRenderer:

VolumeRenderer 
===================

**Inherits:** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------------------------+-----------------------------------------------------------------------------+
| :ref:`DVRBase<class_DVRBase>`                       | :ref:`DVRDriver<class_VolumeRenderer_property_DVRDriver>`                   |
+-----------------------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                         | :ref:`ModelHeight<class_VolumeRenderer_property_ModelHeight>`               |
+-----------------------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                         | :ref:`ZExaggerate<class_VolumeRenderer_property_ZExaggerate>`               |
+-----------------------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                       | :ref:`AutoRender<class_VolumeRenderer_property_AutoRender>`                 |
+-----------------------------------------------------+-----------------------------------------------------------------------------+
| :ref:`MeteorDataProvider<class_MeteorDataProvider>` | :ref:`MeteorDataProvider<class_VolumeRenderer_property_MeteorDataProvider>` |
+-----------------------------------------------------+-----------------------------------------------------------------------------+

方法
----

+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetBlockSize<class_VolumeRenderer_method_SetBlockSize>` **(** :ref:`Int32<class_Int32>` col, :ref:`Int32<class_Int32>` row **)**                                                                                                          |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Initialize<class_VolumeRenderer_method_Initialize>` **(** :ref:`String<class_String>` varName, :ref:`MeteorDataProvider<class_MeteorDataProvider>` mdProvider, :ref:`Single<class_Single>` modelH, :ref:`Single<class_Single>` exgg **)** |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Render<class_VolumeRenderer_method_Render>` **(** **)**                                                                                                                                                                                   |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`DoRender<class_VolumeRenderer_method_DoRender>` **(** **)**                                                                                                                                                                               |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetBitmap<class_VolumeRenderer_method_SetBitmap>` **(** :ref:`List`1<class_List`1>` _colorControlPoints, :ref:`List`1<class_List`1>` _opacityControlPoints **)**                                                                          |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`RefreshData<class_VolumeRenderer_method_RefreshData>` **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` pathFirst, :ref:`String<class_String>` pathlast **)**                                                        |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`RefreshTime<class_VolumeRenderer_method_RefreshTime>` **(** :ref:`Single<class_Single>` time **)**                                                                                                                                        |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`RefreshStep<class_VolumeRenderer_method_RefreshStep>` **(** :ref:`Int32<class_Int32>` step **)**                                                                                                                                          |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_PhysicsProcess<class_VolumeRenderer_method__PhysicsProcess>` **(** :ref:`Single<class_Single>` delta **)**                                                                                                                               |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Dispose<class_VolumeRenderer_method_Dispose>` **(** **)**                                                                                                                                                                                 |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetClipParams<class_VolumeRenderer_method_SetClipParams>` **(** :ref:`MeshInstance<class_MeshInstance>` clipMesh, :ref:`MeshInstance<class_MeshInstance>` meshins, :ref:`ShaderMaterial<class_ShaderMaterial>` mtl **)**                  |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetClipParams2<class_VolumeRenderer_method_SetClipParams2>` **(** :ref:`ShaderMaterial<class_ShaderMaterial>` mtl **)**                                                                                                                   |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_VolumeRenderer_property_DVRDriver:

- :ref:`DVRBase<class_DVRBase>` **DVRDriver**

+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_VolumeRenderer_property_ModelHeight:

- :ref:`Single<class_Single>` **ModelHeight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

模型高度

----

.. _class_VolumeRenderer_property_ZExaggerate:

- :ref:`Single<class_Single>` **ZExaggerate**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

离地高度

----

.. _class_VolumeRenderer_property_AutoRender:

- :ref:`Boolean<class_Boolean>` **AutoRender**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_VolumeRenderer_property_MeteorDataProvider:

- :ref:`MeteorDataProvider<class_MeteorDataProvider>` **MeteorDataProvider**

+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_VolumeRenderer_method_SetBlockSize:

- :ref:`Void<class_Void>` **SetBlockSize** **(** :ref:`Int32<class_Int32>` col, :ref:`Int32<class_Int32>` row **)**



----

.. _class_VolumeRenderer_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** :ref:`String<class_String>` varName, :ref:`MeteorDataProvider<class_MeteorDataProvider>` mdProvider, :ref:`Single<class_Single>` modelH, :ref:`Single<class_Single>` exgg **)**



----

.. _class_VolumeRenderer_method_Render:

- :ref:`Void<class_Void>` **Render** **(** **)**



----

.. _class_VolumeRenderer_method_DoRender:

- :ref:`Void<class_Void>` **DoRender** **(** **)**



----

.. _class_VolumeRenderer_method_SetBitmap:

- :ref:`Void<class_Void>` **SetBitmap** **(** :ref:`List`1<class_List`1>` _colorControlPoints, :ref:`List`1<class_List`1>` _opacityControlPoints **)**



----

.. _class_VolumeRenderer_method_RefreshData:

- :ref:`Void<class_Void>` **RefreshData** **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` pathFirst, :ref:`String<class_String>` pathlast **)**



----

.. _class_VolumeRenderer_method_RefreshTime:

- :ref:`Void<class_Void>` **RefreshTime** **(** :ref:`Single<class_Single>` time **)**



----

.. _class_VolumeRenderer_method_RefreshStep:

- :ref:`Void<class_Void>` **RefreshStep** **(** :ref:`Int32<class_Int32>` step **)**



----

.. _class_VolumeRenderer_method__PhysicsProcess:

- :ref:`Void<class_Void>` **_PhysicsProcess** **(** :ref:`Single<class_Single>` delta **)**



----

.. _class_VolumeRenderer_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**



----

.. _class_VolumeRenderer_method_SetClipParams:

- :ref:`Void<class_Void>` **SetClipParams** **(** :ref:`MeshInstance<class_MeshInstance>` clipMesh, :ref:`MeshInstance<class_MeshInstance>` meshins, :ref:`ShaderMaterial<class_ShaderMaterial>` mtl **)**

设置裁剪参数

----

.. _class_VolumeRenderer_method_SetClipParams2:

- :ref:`Void<class_Void>` **SetClipParams2** **(** :ref:`ShaderMaterial<class_ShaderMaterial>` mtl **)**



----

