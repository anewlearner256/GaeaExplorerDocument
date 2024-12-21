.. _class_WeatherManager:

WeatherManager 
===================

**Inherits:** :ref:`MeshInstance<class_MeshInstance>` **<** :ref:`GeometryInstance<class_GeometryInstance>` **<** :ref:`VisualInstance<class_VisualInstance>` **<** :ref:`CullInstance<class_CullInstance>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`Flash<class_WeatherManager_property_Flash>`                         |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`Rainy<class_WeatherManager_property_Rainy>`                         |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`Snowy<class_WeatherManager_property_Snowy>`                         |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`NeedAtmosphere<class_WeatherManager_property_NeedAtmosphere>`       |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`WindDirection<class_WeatherManager_property_WindDirection>`         |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`Speed<class_WeatherManager_property_Speed>`                         |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Color<class_Color>`     | :ref:`RainyColor<class_WeatherManager_property_RainyColor>`               |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`RainyCount<class_WeatherManager_property_RainyCount>`               |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`SnowyCount<class_WeatherManager_property_SnowyCount>`               |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`SnowySize<class_WeatherManager_property_SnowySize>`                 |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`FlashFrequency<class_WeatherManager_property_FlashFrequency>`       |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`FlashStrength<class_WeatherManager_property_FlashStrength>`         |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>` | :ref:`RainyVisibleRange<class_WeatherManager_property_RainyVisibleRange>` |
+-------------------------------+---------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>` | :ref:`SnowyVisibleRange<class_WeatherManager_property_SnowyVisibleRange>` |
+-------------------------------+---------------------------------------------------------------------------+

方法
----

+---------------------------------------------+-----------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                     | :ref:`_Ready<class_WeatherManager_method__Ready>` **(** **)**                                       |
+---------------------------------------------+-----------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                     | :ref:`_Process<class_WeatherManager_method__Process>` **(** :ref:`Single<class_Single>` delta **)** |
+---------------------------------------------+-----------------------------------------------------------------------------------------------------+
| :ref:`ShaderMaterial<class_ShaderMaterial>` | :ref:`GetWeatherShader<class_WeatherManager_method_GetWeatherShader>` **(** **)**                   |
+---------------------------------------------+-----------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_WeatherManager_property_Flash:

- :ref:`Boolean<class_Boolean>` **Flash**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

闪电控制，true为出现闪电，默认为false

----

.. _class_WeatherManager_property_Rainy:

- :ref:`Boolean<class_Boolean>` **Rainy**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

雨控制，true为出现雨，默认为false

----

.. _class_WeatherManager_property_Snowy:

- :ref:`Boolean<class_Boolean>` **Snowy**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

雪控制，true为出现雪，默认为false

----

.. _class_WeatherManager_property_NeedAtmosphere:

- :ref:`Boolean<class_Boolean>` **NeedAtmosphere**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

大气控制，true为出现大气，默认为false

----

.. _class_WeatherManager_property_WindDirection:

- :ref:`Single<class_Single>` **WindDirection**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

风向控制，范围[-1.5,1.5]表示从左到右，默认为-0.5

----

.. _class_WeatherManager_property_Speed:

- :ref:`Single<class_Single>` **Speed**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

雨、雪速度控制，范围[0,100]数值越大速度越快，默认为10

----

.. _class_WeatherManager_property_RainyColor:

- :ref:`Color<class_Color>` **RainyColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

雨的颜色控制，默认为Color(0.9411f, 0.9764f, 1.0f, 1.0f)

----

.. _class_WeatherManager_property_RainyCount:

- :ref:`Single<class_Single>` **RainyCount**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

雨数量控制，范围[0,500]数值越大数量越多，默认为50

----

.. _class_WeatherManager_property_SnowyCount:

- :ref:`Single<class_Single>` **SnowyCount**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

雪数量控制，范围[0,500]数值越大数量越多，默认为50

----

.. _class_WeatherManager_property_SnowySize:

- :ref:`Single<class_Single>` **SnowySize**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

雪数量控制，范围[0,500]数值越大数量越多，默认为50

----

.. _class_WeatherManager_property_FlashFrequency:

- :ref:`Single<class_Single>` **FlashFrequency**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

闪电间隙控制，范围[4,12]数值越小频率越快，默认为8

----

.. _class_WeatherManager_property_FlashStrength:

- :ref:`Single<class_Single>` **FlashStrength**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

闪电强度控制，范围[0.5,4]数值越大越亮，默认为2

----

.. _class_WeatherManager_property_RainyVisibleRange:

- :ref:`Vector2<class_Vector2>` **RainyVisibleRange**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

VisibleRange 在大气开启的情况下，最大显示高度为 min(VisibleRange.y, 大气高度)

----

.. _class_WeatherManager_property_SnowyVisibleRange:

- :ref:`Vector2<class_Vector2>` **SnowyVisibleRange**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_WeatherManager_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**



----

.. _class_WeatherManager_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**



----

.. _class_WeatherManager_method_GetWeatherShader:

- :ref:`ShaderMaterial<class_ShaderMaterial>` **GetWeatherShader** **(** **)**



----

