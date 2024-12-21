.. _class_EquivocalRenderingMaterial:

EquivocalRenderingMaterial 
===================

**Inherits:** :ref:`ShaderMaterial<class_ShaderMaterial>` **<** :ref:`Material<class_Material>` **<** :ref:`Resource<class_Resource>` **<** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

描述
----

三角网索引材质

示例
----

属性
----

+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                               | :ref:`SrgbToLinear<class_EquivocalRenderingMaterial_property_SrgbToLinear>`                               |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                                 | :ref:`Transparency<class_EquivocalRenderingMaterial_property_Transparency>`                               |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`                               | :ref:`ColorTexture<class_EquivocalRenderingMaterial_property_ColorTexture>`                               |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`EquivocalRenderingType<class_EquivocalRenderingType>` | :ref:`RenderingType<class_EquivocalRenderingMaterial_property_RenderingType>`                             |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                                 | :ref:`TrianglesInterpolationValue<class_EquivocalRenderingMaterial_property_TrianglesInterpolationValue>` |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                               | :ref:`UseUV<class_EquivocalRenderingMaterial_property_UseUV>`                                             |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                                   | :ref:`LinesColor<class_EquivocalRenderingMaterial_property_LinesColor>`                                   |
+-------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------+

方法
----

+-------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32[]<class_Int32[]>` | :ref:`CreateValueImageByJson<class_EquivocalRenderingMaterial_method_CreateValueImageByJson>` **(** :ref:`String<class_String>` valueJson, :ref:`Vector2<class_Vector2>` minMax **)** |
+-------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`     | :ref:`CreateValueImage<class_EquivocalRenderingMaterial_method_CreateValueImage>` **(** :ref:`Single[]<class_Single[]>` CustomValue, :ref:`Vector2<class_Vector2>` MinMax **)**       |
+-------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`ValueTextureIdx<class_EquivocalRenderingMaterial_method_ValueTextureIdx>` **(** :ref:`Int32<class_Int32>` idx **)**                                                             |
+-------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`DeduceValueTextureIdx<class_EquivocalRenderingMaterial_method_DeduceValueTextureIdx>` **(** :ref:`Int32<class_Int32>` idx1, :ref:`Int32<class_Int32>` idx2 **)**                |
+-------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`ClearValueTexture<class_EquivocalRenderingMaterial_method_ClearValueTexture>` **(** **)**                                                                                       |
+-------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_EquivocalRenderingMaterial_property_SrgbToLinear:

- :ref:`Boolean<class_Boolean>` **SrgbToLinear**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否进行色彩空间转换

----

.. _class_EquivocalRenderingMaterial_property_Transparency:

- :ref:`Single<class_Single>` **Transparency**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

透明度设置

----

.. _class_EquivocalRenderingMaterial_property_ColorTexture:

- :ref:`Texture<class_Texture>` **ColorTexture**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

色卡纹理

----

.. _class_EquivocalRenderingMaterial_property_RenderingType:

- :ref:`EquivocalRenderingType<class_EquivocalRenderingType>` **RenderingType**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

三角索引渲染模式

----

.. _class_EquivocalRenderingMaterial_property_TrianglesInterpolationValue:

- :ref:`Single<class_Single>` **TrianglesInterpolationValue**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

插值系数从 0 ~ 1

----

.. _class_EquivocalRenderingMaterial_property_UseUV:

- :ref:`Boolean<class_Boolean>` **UseUV**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

使用UV，默认使用的UV2

----

.. _class_EquivocalRenderingMaterial_property_LinesColor:

- :ref:`Color<class_Color>` **LinesColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

三角网的线的颜色

----


方法说明
-------

.. _class_EquivocalRenderingMaterial_method_CreateValueImageByJson:

- :ref:`Int32[]<class_Int32[]>` **CreateValueImageByJson** **(** :ref:`String<class_String>` valueJson, :ref:`Vector2<class_Vector2>` minMax **)**

通过JSON文本创建纹理值图

----

.. _class_EquivocalRenderingMaterial_method_CreateValueImage:

- :ref:`Int32<class_Int32>` **CreateValueImage** **(** :ref:`Single[]<class_Single[]>` CustomValue, :ref:`Vector2<class_Vector2>` MinMax **)**

通过自定义数据数组创建纹理值图

----

.. _class_EquivocalRenderingMaterial_method_ValueTextureIdx:

- :ref:`Void<class_Void>` **ValueTextureIdx** **(** :ref:`Int32<class_Int32>` idx **)**

应用纹理图

----

.. _class_EquivocalRenderingMaterial_method_DeduceValueTextureIdx:

- :ref:`Void<class_Void>` **DeduceValueTextureIdx** **(** :ref:`Int32<class_Int32>` idx1, :ref:`Int32<class_Int32>` idx2 **)**

推演纹理图

----

.. _class_EquivocalRenderingMaterial_method_ClearValueTexture:

- :ref:`Void<class_Void>` **ClearValueTexture** **(** **)**

清除纹理图

----

