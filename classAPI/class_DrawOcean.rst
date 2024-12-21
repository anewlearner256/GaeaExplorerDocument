.. _class_DrawOcean:

DrawOcean 
===================

**Inherits:** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Single<class_Single>`               | :ref:`SeaHeight<class_DrawOcean_property_SeaHeight>`               |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Single<class_Single>`               | :ref:`SeaChoppy<class_DrawOcean_property_SeaChoppy>`               |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Single<class_Single>`               | :ref:`SeaSpeed<class_DrawOcean_property_SeaSpeed>`                 |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Single<class_Single>`               | :ref:`SeaFreq<class_DrawOcean_property_SeaFreq>`                   |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Color<class_Color>`                 | :ref:`SeaBase<class_DrawOcean_property_SeaBase>`                   |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Color<class_Color>`                 | :ref:`SeaWaterColor<class_DrawOcean_property_SeaWaterColor>`       |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Single<class_Single>`               | :ref:`SeaFresnelFactor<class_DrawOcean_property_SeaFresnelFactor>` |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Single<class_Single>`               | :ref:`SeaAlbeoFactor<class_DrawOcean_property_SeaAlbeoFactor>`     |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`             | :ref:`SeaAA<class_DrawOcean_property_SeaAA>`                       |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Single<class_Single>`               | :ref:`SeaDistFactor<class_DrawOcean_property_SeaDistFactor>`       |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`OceanTypeEunm<class_OceanTypeEunm>` | :ref:`OceanType<class_DrawOcean_property_OceanType>`               |
+-------------------------------------------+--------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`             | :ref:`DrawWireFrame<class_DrawOcean_property_DrawWireFrame>`       |
+-------------------------------------------+--------------------------------------------------------------------+

方法
----

+-------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Process<class_DrawOcean_method__Process>` **(** :ref:`Single<class_Single>` delta **)** |
+-------------------------+------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawOcean_property_SeaHeight:

- :ref:`Single<class_Single>` **SeaHeight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

浪高

----

.. _class_DrawOcean_property_SeaChoppy:

- :ref:`Single<class_Single>` **SeaChoppy**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

起伏

----

.. _class_DrawOcean_property_SeaSpeed:

- :ref:`Single<class_Single>` **SeaSpeed**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

波浪速度

----

.. _class_DrawOcean_property_SeaFreq:

- :ref:`Single<class_Single>` **SeaFreq**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

波浪频率

----

.. _class_DrawOcean_property_SeaBase:

- :ref:`Color<class_Color>` **SeaBase**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

海水底色

----

.. _class_DrawOcean_property_SeaWaterColor:

- :ref:`Color<class_Color>` **SeaWaterColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

海水颜色

----

.. _class_DrawOcean_property_SeaFresnelFactor:

- :ref:`Single<class_Single>` **SeaFresnelFactor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

菲涅尔反射强度

----

.. _class_DrawOcean_property_SeaAlbeoFactor:

- :ref:`Single<class_Single>` **SeaAlbeoFactor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

反射强度， 越小越亮

----

.. _class_DrawOcean_property_SeaAA:

- :ref:`Boolean<class_Boolean>` **SeaAA**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

模糊处理，降低噪点强度，比较影响效率，可以不开

----

.. _class_DrawOcean_property_SeaDistFactor:

- :ref:`Single<class_Single>` **SeaDistFactor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

控制菲涅尔反射随距离衰减的程度，调小可以避免光斑现象

----

.. _class_DrawOcean_property_OceanType:

- :ref:`OceanTypeEunm<class_OceanTypeEunm>` **OceanType**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_DrawOcean_property_DrawWireFrame:

- :ref:`Boolean<class_Boolean>` **DrawWireFrame**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_DrawOcean_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**



----

