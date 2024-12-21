.. _class_MeteorDataProvider:

MeteorDataProvider 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+---------------------------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`DataDateTimeString<class_MeteorDataProvider_property_DataDateTimeString>` |
+-------------------------------+---------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`VerticalReversal<class_MeteorDataProvider_property_VerticalReversal>`     |
+-------------------------------+---------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`Time<class_MeteorDataProvider_property_Time>`                             |
+-------------------------------+---------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`OverlayLevelIndex<class_MeteorDataProvider_property_OverlayLevelIndex>`   |
+-------------------------------+---------------------------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`OverlayVarName<class_MeteorDataProvider_property_OverlayVarName>`         |
+-------------------------------+---------------------------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`MeteoDatasetName<class_MeteorDataProvider_property_MeteoDatasetName>`     |
+-------------------------------+---------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`IsEndRead<class_MeteorDataProvider_property_IsEndRead>`                   |
+-------------------------------+---------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`StartReading<class_MeteorDataProvider_property_StartReading>`             |
+-------------------------------+---------------------------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`ConfigPath<class_MeteorDataProvider_property_ConfigPath>`                 |
+-------------------------------+---------------------------------------------------------------------------------+

方法
----

+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Initialize<class_MeteorDataProvider_method_Initialize>` **(** :ref:`String<class_String>` path **)**                                                                                                                     |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Initialize<class_MeteorDataProvider_method_Initialize>` **(** :ref:`Byte[]<class_Byte[]>` baseStream **)**                                                                                                               |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`UnloadData<class_MeteorDataProvider_method_UnloadData>` **(** **)**                                                                                                                                                      |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`GetMeteorData<class_MeteorDataProvider_method_GetMeteorData>` **(** :ref:`String<class_String>` path, :ref:`Int32<class_Int32>` Tnum **)**                                                                               |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetVarData<class_MeteorDataProvider_method_SetVarData>` **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` tempPath **)**                                                                            |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`GetDataAsyn<class_MeteorDataProvider_method_GetDataAsyn>` **(** :ref:`String<class_String>` path, :ref:`String<class_String>` varName, :ref:`Int32<class_Int32>` Tnum, :ref:`Vector3[]<class_Vector3[]>` refdata **)**   |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`GetDataAsynEx<class_MeteorDataProvider_method_GetDataAsynEx>` **(** :ref:`String<class_String>` path, :ref:`String<class_String>` varName, :ref:`Int32<class_Int32>` Tnum, :ref:`Single[]<class_Single[]>` refdata **)** |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`GetData<class_MeteorDataProvider_method_GetData>` **(** :ref:`String<class_String>` path, :ref:`String<class_String>` varName, :ref:`Int32<class_Int32>` Tnum **)**                                                      |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`GetData<class_MeteorDataProvider_method_GetData>` **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` tempPath **)**                                                                                  |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`GetDataFromStream<class_MeteorDataProvider_method_GetDataFromStream>` **(** :ref:`String<class_String>` varName, :ref:`Byte[]<class_Byte[]>` bytes **)**                                                                 |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_MeteorDataProvider_property_DataDateTimeString:

- :ref:`String<class_String>` **DataDateTimeString**

+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_MeteorDataProvider_property_VerticalReversal:

- :ref:`Boolean<class_Boolean>` **VerticalReversal**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

模型垂直反转

----

.. _class_MeteorDataProvider_property_Time:

- :ref:`Int32<class_Int32>` **Time**

+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_MeteorDataProvider_property_OverlayLevelIndex:

- :ref:`Int32<class_Int32>` **OverlayLevelIndex**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_MeteorDataProvider_property_OverlayVarName:

- :ref:`String<class_String>` **OverlayVarName**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

叠加变量的名称

----

.. _class_MeteorDataProvider_property_MeteoDatasetName:

- :ref:`String<class_String>` **MeteoDatasetName**

+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_MeteorDataProvider_property_IsEndRead:

- :ref:`Boolean<class_Boolean>` **IsEndRead**

+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_MeteorDataProvider_property_StartReading:

- :ref:`Boolean<class_Boolean>` **StartReading**

+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_MeteorDataProvider_property_ConfigPath:

- :ref:`String<class_String>` **ConfigPath**

+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_MeteorDataProvider_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** :ref:`String<class_String>` path **)**



----

.. _class_MeteorDataProvider_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** :ref:`Byte[]<class_Byte[]>` baseStream **)**



----

.. _class_MeteorDataProvider_method_UnloadData:

- :ref:`Void<class_Void>` **UnloadData** **(** **)**



----

.. _class_MeteorDataProvider_method_GetMeteorData:

- :ref:`Void<class_Void>` **GetMeteorData** **(** :ref:`String<class_String>` path, :ref:`Int32<class_Int32>` Tnum **)**

获取气象数据体

----

.. _class_MeteorDataProvider_method_SetVarData:

- :ref:`Void<class_Void>` **SetVarData** **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` tempPath **)**



----

.. _class_MeteorDataProvider_method_GetDataAsyn:

- :ref:`Void<class_Void>` **GetDataAsyn** **(** :ref:`String<class_String>` path, :ref:`String<class_String>` varName, :ref:`Int32<class_Int32>` Tnum, :ref:`Vector3[]<class_Vector3[]>` refdata **)**



----

.. _class_MeteorDataProvider_method_GetDataAsynEx:

- :ref:`Void<class_Void>` **GetDataAsynEx** **(** :ref:`String<class_String>` path, :ref:`String<class_String>` varName, :ref:`Int32<class_Int32>` Tnum, :ref:`Single[]<class_Single[]>` refdata **)**



----

.. _class_MeteorDataProvider_method_GetData:

- :ref:`Void<class_Void>` **GetData** **(** :ref:`String<class_String>` path, :ref:`String<class_String>` varName, :ref:`Int32<class_Int32>` Tnum **)**



----

.. _class_MeteorDataProvider_method_GetData:

- :ref:`Void<class_Void>` **GetData** **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` tempPath **)**



----

.. _class_MeteorDataProvider_method_GetDataFromStream:

- :ref:`Void<class_Void>` **GetDataFromStream** **(** :ref:`String<class_String>` varName, :ref:`Byte[]<class_Byte[]>` bytes **)**



----

