.. _class_StreamLineTD:

StreamLineTD 
===================

**Inherits:** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`               | :ref:`ArrowDensity<class_StreamLineTD_property_ArrowDensity>`           |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`               | :ref:`TimeNum<class_StreamLineTD_property_TimeNum>`                     |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`               | :ref:`LineLevel<class_StreamLineTD_property_LineLevel>`                 |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`               | :ref:`LineDensity<class_StreamLineTD_property_LineDensity>`             |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`             | :ref:`ArrowSize<class_StreamLineTD_property_ArrowSize>`                 |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`             | :ref:`LineDensity2<class_StreamLineTD_property_LineDensity2>`           |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Color<class_Color>`               | :ref:`LineColor<class_StreamLineTD_property_LineColor>`                 |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Color<class_Color>`               | :ref:`ArrowColor<class_StreamLineTD_property_ArrowColor>`               |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`           | :ref:`IsRefresh<class_StreamLineTD_property_IsRefresh>`                 |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Color<class_Color>`               | :ref:`ColorEnd<class_StreamLineTD_property_ColorEnd>`                   |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Color<class_Color>`               | :ref:`ColorStart<class_StreamLineTD_property_ColorStart>`               |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Double<class_Double>`             | :ref:`ModelHeight<class_StreamLineTD_property_ModelHeight>`             |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`           | :ref:`IsAddDatToLine<class_StreamLineTD_property_IsAddDatToLine>`       |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`               | :ref:`Speed<class_StreamLineTD_property_Speed>`                         |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Double<class_Double>`             | :ref:`Maximum<class_StreamLineTD_property_Maximum>`                     |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Double<class_Double>`             | :ref:`Minimum<class_StreamLineTD_property_Minimum>`                     |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`           | :ref:`Custom_MaxMinimum<class_StreamLineTD_property_Custom_MaxMinimum>` |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Color[]<class_Color[]>`           | :ref:`ColorRanges<class_StreamLineTD_property_ColorRanges>`             |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`               | :ref:`ColorCount<class_StreamLineTD_property_ColorCount>`               |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`             | :ref:`EmissionPower<class_StreamLineTD_property_EmissionPower>`         |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`             | :ref:`VisibleLength<class_StreamLineTD_property_VisibleLength>`         |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Single<class_Single>`             | :ref:`VisiblePer<class_StreamLineTD_property_VisiblePer>`               |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`               | :ref:`ColortransLength<class_StreamLineTD_property_ColortransLength>`   |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`               | :ref:`GapFrame<class_StreamLineTD_property_GapFrame>`                   |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`MeshInstance<class_MeshInstance>` | :ref:`MeshInstance<class_StreamLineTD_property_MeshInstance>`           |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`           | :ref:`EnablePick<class_StreamLineTD_property_EnablePick>`               |
+-----------------------------------------+-------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`               | :ref:`ClickThreshold<class_StreamLineTD_property_ClickThreshold>`       |
+-----------------------------------------+-------------------------------------------------------------------------+

方法
----

+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Initialize<class_StreamLineTD_method_Initialize>` **(** :ref:`String<class_String>` name, :ref:`MeteorDataProvider<class_MeteorDataProvider>` mdProvider **)** |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Initialize<class_StreamLineTD_method_Initialize>` **(** **)**                                                                                                  |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`DoRender<class_StreamLineTD_method_DoRender>` **(** **)**                                                                                                      |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SelectedCallBack<class_StreamLineTD_method_SelectedCallBack>` **(** :ref:`Action`2<class_Action`2>` action **)**                                               |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Render<class_StreamLineTD_method_Render>` **(** **)**                                                                                                          |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_PhysicsProcess<class_StreamLineTD_method__PhysicsProcess>` **(** :ref:`Single<class_Single>` delta **)**                                                      |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Process<class_StreamLineTD_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                                    |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Update<class_StreamLineTD_method_Update>` **(** **)**                                                                                                          |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`RefrhData<class_StreamLineTD_method_RefrhData>` **(** :ref:`String<class_String>` _varName, :ref:`String<class_String>` path **)**                             |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`RefrhDataFromURL<class_StreamLineTD_method_RefrhDataFromURL>` **(** :ref:`String<class_String>` _varName, :ref:`String<class_String>` url **)**                |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Dispose<class_StreamLineTD_method_Dispose>` **(** **)**                                                                                                        |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_StreamLineTD_property_ArrowDensity:

- :ref:`Int32<class_Int32>` **ArrowDensity**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

箭头密度

----

.. _class_StreamLineTD_property_TimeNum:

- :ref:`Int32<class_Int32>` **TimeNum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_LineLevel:

- :ref:`Int32<class_Int32>` **LineLevel**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_LineDensity:

- :ref:`Int32<class_Int32>` **LineDensity**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

流线的生成密度

----

.. _class_StreamLineTD_property_ArrowSize:

- :ref:`Single<class_Single>` **ArrowSize**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

箭头大小

----

.. _class_StreamLineTD_property_LineDensity2:

- :ref:`Single<class_Single>` **LineDensity2**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

流线的显示密度  2表示两条显示一条

----

.. _class_StreamLineTD_property_LineColor:

- :ref:`Color<class_Color>` **LineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

流线颜色

----

.. _class_StreamLineTD_property_ArrowColor:

- :ref:`Color<class_Color>` **ArrowColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

箭头颜色

----

.. _class_StreamLineTD_property_IsRefresh:

- :ref:`Boolean<class_Boolean>` **IsRefresh**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_ColorEnd:

- :ref:`Color<class_Color>` **ColorEnd**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_ColorStart:

- :ref:`Color<class_Color>` **ColorStart**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_ModelHeight:

- :ref:`Double<class_Double>` **ModelHeight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_IsAddDatToLine:

- :ref:`Boolean<class_Boolean>` **IsAddDatToLine**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_Speed:

- :ref:`Int32<class_Int32>` **Speed**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_Maximum:

- :ref:`Double<class_Double>` **Maximum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_Minimum:

- :ref:`Double<class_Double>` **Minimum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_Custom_MaxMinimum:

- :ref:`Boolean<class_Boolean>` **Custom_MaxMinimum**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_ColorRanges:

- :ref:`Color[]<class_Color[]>` **ColorRanges**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_ColorCount:

- :ref:`Int32<class_Int32>` **ColorCount**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_EmissionPower:

- :ref:`Single<class_Single>` **EmissionPower**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_VisibleLength:

- :ref:`Single<class_Single>` **VisibleLength**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_VisiblePer:

- :ref:`Single<class_Single>` **VisiblePer**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_ColortransLength:

- :ref:`Int32<class_Int32>` **ColortransLength**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_GapFrame:

- :ref:`Int32<class_Int32>` **GapFrame**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

每隔多少帧渲染一次，默认为5

----

.. _class_StreamLineTD_property_MeshInstance:

- :ref:`MeshInstance<class_MeshInstance>` **MeshInstance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_StreamLineTD_property_EnablePick:

- :ref:`Boolean<class_Boolean>` **EnablePick**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否允许点击

----

.. _class_StreamLineTD_property_ClickThreshold:

- :ref:`Int32<class_Int32>` **ClickThreshold**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

点击查询阈值

----


方法说明
-------

.. _class_StreamLineTD_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** :ref:`String<class_String>` name, :ref:`MeteorDataProvider<class_MeteorDataProvider>` mdProvider **)**



----

.. _class_StreamLineTD_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** **)**



----

.. _class_StreamLineTD_method_DoRender:

- :ref:`Void<class_Void>` **DoRender** **(** **)**



----

.. _class_StreamLineTD_method_SelectedCallBack:

- :ref:`Void<class_Void>` **SelectedCallBack** **(** :ref:`Action`2<class_Action`2>` action **)**

回调函数

----

.. _class_StreamLineTD_method_Render:

- :ref:`Void<class_Void>` **Render** **(** **)**

渲染函数

----

.. _class_StreamLineTD_method__PhysicsProcess:

- :ref:`Void<class_Void>` **_PhysicsProcess** **(** :ref:`Single<class_Single>` delta **)**



----

.. _class_StreamLineTD_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**



----

.. _class_StreamLineTD_method_Update:

- :ref:`Void<class_Void>` **Update** **(** **)**



----

.. _class_StreamLineTD_method_RefrhData:

- :ref:`Void<class_Void>` **RefrhData** **(** :ref:`String<class_String>` _varName, :ref:`String<class_String>` path **)**



----

.. _class_StreamLineTD_method_RefrhDataFromURL:

- :ref:`Void<class_Void>` **RefrhDataFromURL** **(** :ref:`String<class_String>` _varName, :ref:`String<class_String>` url **)**



----

.. _class_StreamLineTD_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**



----

