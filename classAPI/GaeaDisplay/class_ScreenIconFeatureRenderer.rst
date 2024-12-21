.. _class_ScreenIconFeatureRenderer:

ScreenIconFeatureRenderer 
===================

**Inherits:** :ref:`MultiLayerFeatureRenderer<class_MultiLayerFeatureRenderer>` **<** :ref:`FeatureRenderer<class_FeatureRenderer>` **<** :ref:`Object<class_Object>`

描述
----

ScreenIcon渲染器，用来显示图层的图标和文字

示例
----

属性
----

+-------------------------------------------------------------------+----------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                                     | :ref:`MouseHover<class_ScreenIconFeatureRenderer_property_MouseHover>`           |
+-------------------------------------------------------------------+----------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                                     | :ref:`MouseClick<class_ScreenIconFeatureRenderer_property_MouseClick>`           |
+-------------------------------------------------------------------+----------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                                     | :ref:`TurnOnCollision<class_ScreenIconFeatureRenderer_property_TurnOnCollision>` |
+-------------------------------------------------------------------+----------------------------------------------------------------------------------+
| :ref:`ScreenIconFeatureRenderer<class_ScreenIconFeatureRenderer>` | :ref:`Instance<class_ScreenIconFeatureRenderer_property_Instance>`               |
+-------------------------------------------------------------------+----------------------------------------------------------------------------------+

方法
----

+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`ScreenIconCallBack<class_ScreenIconFeatureRenderer_method_ScreenIconCallBack>` **(** :ref:`Action`3<class_Action`3>` action **)** |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnLayerInit<class_ScreenIconFeatureRenderer_method_OnLayerInit>` **(** :ref:`Action`1<class_Action`1>` onhit **)**                |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`Initialize<class_ScreenIconFeatureRenderer_method_Initialize>` **(** :ref:`FeatureLayer<class_FeatureLayer>` layer **)**          |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`RemoveLayer<class_ScreenIconFeatureRenderer_method_RemoveLayer>` **(** :ref:`FeatureLayer<class_FeatureLayer>` featureLayer **)** |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_ScreenIconFeatureRenderer_property_MouseHover:

- :ref:`Boolean<class_Boolean>` **MouseHover**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否开启鼠标悬停

----

.. _class_ScreenIconFeatureRenderer_property_MouseClick:

- :ref:`Boolean<class_Boolean>` **MouseClick**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否开启鼠标点击

----

.. _class_ScreenIconFeatureRenderer_property_TurnOnCollision:

- :ref:`Boolean<class_Boolean>` **TurnOnCollision**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否开启碰撞，默认开启

----

.. _class_ScreenIconFeatureRenderer_property_Instance:

- :ref:`ScreenIconFeatureRenderer<class_ScreenIconFeatureRenderer>` **Instance**

+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_ScreenIconFeatureRenderer_method_ScreenIconCallBack:

- :ref:`Void<class_Void>` **ScreenIconCallBack** **(** :ref:`Action`3<class_Action`3>` action **)**



----

.. _class_ScreenIconFeatureRenderer_method_OnLayerInit:

- :ref:`Void<class_Void>` **OnLayerInit** **(** :ref:`Action`1<class_Action`1>` onhit **)**

图层初始化完成的回调函数

----

.. _class_ScreenIconFeatureRenderer_method_Initialize:

- :ref:`Boolean<class_Boolean>` **Initialize** **(** :ref:`FeatureLayer<class_FeatureLayer>` layer **)**

图层初始化

----

.. _class_ScreenIconFeatureRenderer_method_RemoveLayer:

- :ref:`Void<class_Void>` **RemoveLayer** **(** :ref:`FeatureLayer<class_FeatureLayer>` featureLayer **)**

移除单个图层

----

