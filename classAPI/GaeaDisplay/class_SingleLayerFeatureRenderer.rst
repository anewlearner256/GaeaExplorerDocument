.. _class_SingleLayerFeatureRenderer:

SingleLayerFeatureRenderer 
===================

**Inherits:** :ref:`FeatureRenderer<class_FeatureRenderer>` **<** :ref:`Object<class_Object>`

描述
----

单图层要素绘制类，继承自FeatureRenderer

示例
----

属性
----

+-----------------------------+-----------------------------------------------------------------+
| :ref:`Symbol<class_Symbol>` | :ref:`Symbol<class_SingleLayerFeatureRenderer_property_Symbol>` |
+-----------------------------+-----------------------------------------------------------------+

方法
----

+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`             | :ref:`Initialize<class_SingleLayerFeatureRenderer_method_Initialize>` **(** :ref:`FeatureLayer<class_FeatureLayer>` layer **)**                                                               |
+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`IEnumerable`1<class_IEnumerable`1>` | :ref:`CombineSymbolMeshs<class_SingleLayerFeatureRenderer_method_CombineSymbolMeshs>` **(** :ref:`Transform<class_Transform>` trans, :ref:`IEnumerable`1<class_IEnumerable`1>` allMeshs **)** |
+-------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_SingleLayerFeatureRenderer_property_Symbol:

- :ref:`Symbol<class_Symbol>` **Symbol**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

当前图层的样式

----


方法说明
-------

.. _class_SingleLayerFeatureRenderer_method_Initialize:

- :ref:`Boolean<class_Boolean>` **Initialize** **(** :ref:`FeatureLayer<class_FeatureLayer>` layer **)**

图层初始化

----

.. _class_SingleLayerFeatureRenderer_method_CombineSymbolMeshs:

- :ref:`IEnumerable`1<class_IEnumerable`1>` **CombineSymbolMeshs** **(** :ref:`Transform<class_Transform>` trans, :ref:`IEnumerable`1<class_IEnumerable`1>` allMeshs **)**

根据传入的模型生成MeshInstance

----

