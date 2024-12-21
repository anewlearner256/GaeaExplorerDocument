.. _class_DiscreteField:

DiscreteField 
===================

**Inherits:** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`LevelNum<class_DiscreteField_property_LevelNum>`                   |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`Timer<class_DiscreteField_property_Timer>`                         |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`EmissionPower<class_DiscreteField_property_EmissionPower>`         |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Color<class_Color>`     | :ref:`SymbolColor<class_DiscreteField_property_SymbolColor>`             |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`OrignalHeight<class_DiscreteField_property_OrignalHeight>`         |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`IsLevelColor<class_DiscreteField_property_IsLevelColor>`           |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`MinScale<class_DiscreteField_property_MinScale>`                   |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`MaxScale<class_DiscreteField_property_MaxScale>`                   |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`Density<class_DiscreteField_property_Density>`                     |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Double<class_Double>`   | :ref:`Maximum<class_DiscreteField_property_Maximum>`                     |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Double<class_Double>`   | :ref:`Minimum<class_DiscreteField_property_Minimum>`                     |
+-------------------------------+--------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`Custom_MaxMinimum<class_DiscreteField_property_Custom_MaxMinimum>` |
+-------------------------------+--------------------------------------------------------------------------+

方法
----

+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Initialize<class_DiscreteField_method_Initialize>` **(** :ref:`String<class_String>` name, :ref:`MeteorDataProvider<class_MeteorDataProvider>` provider **)**                                                             |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`RefrhDataFromPath<class_DiscreteField_method_RefrhDataFromPath>` **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` path, :ref:`String<class_String>` path2 **)**                                     |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`RefrhDataFromURL<class_DiscreteField_method_RefrhDataFromURL>` **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` url, :ref:`String<class_String>` url2, :ref:`Action`1<class_Action`1>` action **)** |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetBitmap<class_DiscreteField_method_SetBitmap>` **(** :ref:`Vector2[]<class_Vector2[]>` _colorControlPoints **)**                                                                                                        |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetBitmap<class_DiscreteField_method_SetBitmap>` **(** :ref:`Color[]<class_Color[]>` _colorControlPoints **)**                                                                                                            |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Dispose<class_DiscreteField_method_Dispose>` **(** **)**                                                                                                                                                                  |
+-------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DiscreteField_property_LevelNum:

- :ref:`Int32<class_Int32>` **LevelNum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_Timer:

- :ref:`Single<class_Single>` **Timer**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_EmissionPower:

- :ref:`Single<class_Single>` **EmissionPower**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_SymbolColor:

- :ref:`Color<class_Color>` **SymbolColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_OrignalHeight:

- :ref:`Int32<class_Int32>` **OrignalHeight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_IsLevelColor:

- :ref:`Boolean<class_Boolean>` **IsLevelColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_MinScale:

- :ref:`Single<class_Single>` **MinScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_MaxScale:

- :ref:`Single<class_Single>` **MaxScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_Density:

- :ref:`Single<class_Single>` **Density**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_Maximum:

- :ref:`Double<class_Double>` **Maximum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_Minimum:

- :ref:`Double<class_Double>` **Minimum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DiscreteField_property_Custom_MaxMinimum:

- :ref:`Boolean<class_Boolean>` **Custom_MaxMinimum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_DiscreteField_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** :ref:`String<class_String>` name, :ref:`MeteorDataProvider<class_MeteorDataProvider>` provider **)**



----

.. _class_DiscreteField_method_RefrhDataFromPath:

- :ref:`Void<class_Void>` **RefrhDataFromPath** **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` path, :ref:`String<class_String>` path2 **)**



----

.. _class_DiscreteField_method_RefrhDataFromURL:

- :ref:`Void<class_Void>` **RefrhDataFromURL** **(** :ref:`String<class_String>` varName, :ref:`String<class_String>` url, :ref:`String<class_String>` url2, :ref:`Action`1<class_Action`1>` action **)**



----

.. _class_DiscreteField_method_SetBitmap:

- :ref:`Void<class_Void>` **SetBitmap** **(** :ref:`Vector2[]<class_Vector2[]>` _colorControlPoints **)**



----

.. _class_DiscreteField_method_SetBitmap:

- :ref:`Void<class_Void>` **SetBitmap** **(** :ref:`Color[]<class_Color[]>` _colorControlPoints **)**



----

.. _class_DiscreteField_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**



----

