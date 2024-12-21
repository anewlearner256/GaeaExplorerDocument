.. _class_ContourRender:

ContourRender 
===================

**Inherits:** :ref:`MeshInstance<class_MeshInstance>` **<** :ref:`GeometryInstance<class_GeometryInstance>` **<** :ref:`VisualInstance<class_VisualInstance>` **<** :ref:`CullInstance<class_CullInstance>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

控制等值云图渲染类

示例
----

属性
----

+-------------------------------+----------------------------------------------------------------+
| :ref:`Texture<class_Texture>` | :ref:`ColorTexture<class_ContourRender_property_ColorTexture>` |
+-------------------------------+----------------------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`Count<class_ContourRender_property_Count>`               |
+-------------------------------+----------------------------------------------------------------+

方法
----

+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetShaderMaterial<class_ContourRender_method_SetShaderMaterial>` **(** :ref:`String<class_String>` url **)**                                        |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetShaderMaterial<class_ContourRender_method_SetShaderMaterial>` **(** :ref:`Shader<class_Shader>` shader **)**                                     |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetValueTexture<class_ContourRender_method_SetValueTexture>` **(** :ref:`Texture<class_Texture>` texture **)**                                      |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetValueTexture<class_ContourRender_method_SetValueTexture>` **(** :ref:`Image<class_Image>` img **)**                                              |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetColorTexture<class_ContourRender_method_SetColorTexture>` **(** :ref:`Texture<class_Texture>` colorTexture **)**                                 |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetMinMaxValue<class_ContourRender_method_SetMinMaxValue>` **(** :ref:`Single<class_Single>` min_speed, :ref:`Single<class_Single>` max_speed **)** |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_ContourRender_property_ColorTexture:

- :ref:`Texture<class_Texture>` **ColorTexture**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

渲染色带

----

.. _class_ContourRender_property_Count:

- :ref:`Int32<class_Int32>` **Count**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

渲染值划分个数

----


方法说明
-------

.. _class_ContourRender_method_SetShaderMaterial:

- :ref:`Void<class_Void>` **SetShaderMaterial** **(** :ref:`String<class_String>` url **)**



----

.. _class_ContourRender_method_SetShaderMaterial:

- :ref:`Void<class_Void>` **SetShaderMaterial** **(** :ref:`Shader<class_Shader>` shader **)**



----

.. _class_ContourRender_method_SetValueTexture:

- :ref:`Void<class_Void>` **SetValueTexture** **(** :ref:`Texture<class_Texture>` texture **)**



----

.. _class_ContourRender_method_SetValueTexture:

- :ref:`Void<class_Void>` **SetValueTexture** **(** :ref:`Image<class_Image>` img **)**



----

.. _class_ContourRender_method_SetColorTexture:

- :ref:`Void<class_Void>` **SetColorTexture** **(** :ref:`Texture<class_Texture>` colorTexture **)**



----

.. _class_ContourRender_method_SetMinMaxValue:

- :ref:`Void<class_Void>` **SetMinMaxValue** **(** :ref:`Single<class_Single>` min_speed, :ref:`Single<class_Single>` max_speed **)**



----

