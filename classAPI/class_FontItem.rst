.. _class_FontItem:

FontItem 
===================

**Inherits:** :ref:`IconItem<class_IconItem>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+-------------------------------------------------------+
| :ref:`Vector2<class_Vector2>` | :ref:`TextOffset<class_FontItem_property_TextOffset>` |
+-------------------------------+-------------------------------------------------------+

方法
----

+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`ChangeStyle<class_FontItem_method_ChangeStyle>` **(** :ref:`List`1<class_List`1>` p **)**                                                |
+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`ChangeStyle<class_FontItem_method_ChangeStyle>` **(** :ref:`String<class_String>` fontPath, :ref:`List`1<class_List`1>` p **)**          |
+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`List`1<class_List`1>` | :ref:`Draw<class_FontItem_method_Draw>` **(** :ref:`List`1<class_List`1>` data **)**                                                           |
+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`SetParamter<class_FontItem_method_SetParamter>` **(** **)**                                                                              |
+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`SetItemSize<class_FontItem_method_SetItemSize>` **(** :ref:`Single<class_Single>` text_size, :ref:`Single<class_Single>` mark_size **)** |
+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`SetTexture<class_FontItem_method_SetTexture>` **(** :ref:`Polygon2D<class_Polygon2D>` p **)**                                            |
+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`SetFontColor<class_FontItem_method_SetFontColor>` **(** :ref:`Color<class_Color>` color **)**                                            |
+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`SetOutlineColor<class_FontItem_method_SetOutlineColor>` **(** :ref:`Color<class_Color>` color **)**                                      |
+-----------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_FontItem_property_TextOffset:

- :ref:`Vector2<class_Vector2>` **TextOffset**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_FontItem_method_ChangeStyle:

- :ref:`Void<class_Void>` **ChangeStyle** **(** :ref:`List`1<class_List`1>` p **)**



----

.. _class_FontItem_method_ChangeStyle:

- :ref:`Void<class_Void>` **ChangeStyle** **(** :ref:`String<class_String>` fontPath, :ref:`List`1<class_List`1>` p **)**



----

.. _class_FontItem_method_Draw:

- :ref:`List`1<class_List`1>` **Draw** **(** :ref:`List`1<class_List`1>` data **)**

FontItem Draw. 
根据ScreenIcon绘制Polygon2D

----

.. _class_FontItem_method_SetParamter:

- :ref:`Void<class_Void>` **SetParamter** **(** **)**

设置TextShaderMaterial的参数

----

.. _class_FontItem_method_SetItemSize:

- :ref:`Void<class_Void>` **SetItemSize** **(** :ref:`Single<class_Single>` text_size, :ref:`Single<class_Single>` mark_size **)**

设置TextShaderMaterial的Item参数

----

.. _class_FontItem_method_SetTexture:

- :ref:`Void<class_Void>` **SetTexture** **(** :ref:`Polygon2D<class_Polygon2D>` p **)**

FontItem为指定Polgon2D设置Texture

----

.. _class_FontItem_method_SetFontColor:

- :ref:`Void<class_Void>` **SetFontColor** **(** :ref:`Color<class_Color>` color **)**



----

.. _class_FontItem_method_SetOutlineColor:

- :ref:`Void<class_Void>` **SetOutlineColor** **(** :ref:`Color<class_Color>` color **)**



----

