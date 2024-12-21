.. _class_ParticleTracks:

ParticleTracks 
===================

**Inherits:** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Double<class_Double>`   | :ref:`Speed<class_ParticleTracks_property_Speed>`                         |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`InstanceCount<class_ParticleTracks_property_InstanceCount>`         |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`MinScale<class_ParticleTracks_property_MinScale>`                   |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`MaxScale<class_ParticleTracks_property_MaxScale>`                   |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`Interval<class_ParticleTracks_property_Interval>`                   |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`EmissionPower<class_ParticleTracks_property_EmissionPower>`         |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Color<class_Color>`     | :ref:`SymbolColor<class_ParticleTracks_property_SymbolColor>`             |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`OrignalHeight<class_ParticleTracks_property_OrignalHeight>`         |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`IsLevelColor<class_ParticleTracks_property_IsLevelColor>`           |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`Height_Scale<class_ParticleTracks_property_Height_Scale>`           |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`Width_Scale<class_ParticleTracks_property_Width_Scale>`             |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`Density<class_ParticleTracks_property_Density>`                     |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Double<class_Double>`   | :ref:`Maximum<class_ParticleTracks_property_Maximum>`                     |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Double<class_Double>`   | :ref:`Minimum<class_ParticleTracks_property_Minimum>`                     |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`Custom_MaxMinimum<class_ParticleTracks_property_Custom_MaxMinimum>` |
+-------------------------------+---------------------------------------------------------------------------+

方法
----

+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Initialize<class_ParticleTracks_method_Initialize>` **(** :ref:`String<class_String>` name, :ref:`MeteorDataProvider<class_MeteorDataProvider>` provider **)**                       |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`RefrhDataFromPath<class_ParticleTracks_method_RefrhDataFromPath>` **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` path **)**                                  |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`RefrhDataFromURL<class_ParticleTracks_method_RefrhDataFromURL>` **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` url, :ref:`Action<class_Action>` action **)** |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetAlpha<class_ParticleTracks_method_SetAlpha>` **(** :ref:`Single[]<class_Single[]>` _opacityControlPoints **)**                                                                    |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetAlpha<class_ParticleTracks_method_SetAlpha>` **(** :ref:`Vector2[]<class_Vector2[]>` _opacityControlPoints **)**                                                                  |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetBitmap<class_ParticleTracks_method_SetBitmap>` **(** :ref:`Vector2[]<class_Vector2[]>` _colorControlPoints **)**                                                                  |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetBitmap<class_ParticleTracks_method_SetBitmap>` **(** :ref:`Color[]<class_Color[]>` _colorControlPoints **)**                                                                      |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Process<class_ParticleTracks_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                                                        |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Dispose<class_ParticleTracks_method_Dispose>` **(** **)**                                                                                                                            |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_ParticleTracks_property_Speed:

- :ref:`Double<class_Double>` **Speed**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_InstanceCount:

- :ref:`Int32<class_Int32>` **InstanceCount**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_MinScale:

- :ref:`Single<class_Single>` **MinScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_MaxScale:

- :ref:`Single<class_Single>` **MaxScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_Interval:

- :ref:`Single<class_Single>` **Interval**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

时间间隔，单位为秒

----

.. _class_ParticleTracks_property_EmissionPower:

- :ref:`Single<class_Single>` **EmissionPower**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_SymbolColor:

- :ref:`Color<class_Color>` **SymbolColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_OrignalHeight:

- :ref:`Int32<class_Int32>` **OrignalHeight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_IsLevelColor:

- :ref:`Boolean<class_Boolean>` **IsLevelColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_Height_Scale:

- :ref:`Single<class_Single>` **Height_Scale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

界面设置控制在5左右，而实际放大倍数500左右为宜

----

.. _class_ParticleTracks_property_Width_Scale:

- :ref:`Single<class_Single>` **Width_Scale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

界面设置控制在5左右，而实际放大倍数500左右为宜

----

.. _class_ParticleTracks_property_Density:

- :ref:`Single<class_Single>` **Density**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_Maximum:

- :ref:`Double<class_Double>` **Maximum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_Minimum:

- :ref:`Double<class_Double>` **Minimum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ParticleTracks_property_Custom_MaxMinimum:

- :ref:`Boolean<class_Boolean>` **Custom_MaxMinimum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_ParticleTracks_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** :ref:`String<class_String>` name, :ref:`MeteorDataProvider<class_MeteorDataProvider>` provider **)**



----

.. _class_ParticleTracks_method_RefrhDataFromPath:

- :ref:`Void<class_Void>` **RefrhDataFromPath** **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` path **)**



----

.. _class_ParticleTracks_method_RefrhDataFromURL:

- :ref:`Void<class_Void>` **RefrhDataFromURL** **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` url, :ref:`Action<class_Action>` action **)**



----

.. _class_ParticleTracks_method_SetAlpha:

- :ref:`Void<class_Void>` **SetAlpha** **(** :ref:`Single[]<class_Single[]>` _opacityControlPoints **)**



----

.. _class_ParticleTracks_method_SetAlpha:

- :ref:`Void<class_Void>` **SetAlpha** **(** :ref:`Vector2[]<class_Vector2[]>` _opacityControlPoints **)**



----

.. _class_ParticleTracks_method_SetBitmap:

- :ref:`Void<class_Void>` **SetBitmap** **(** :ref:`Vector2[]<class_Vector2[]>` _colorControlPoints **)**



----

.. _class_ParticleTracks_method_SetBitmap:

- :ref:`Void<class_Void>` **SetBitmap** **(** :ref:`Color[]<class_Color[]>` _colorControlPoints **)**



----

.. _class_ParticleTracks_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**



----

.. _class_ParticleTracks_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**



----

