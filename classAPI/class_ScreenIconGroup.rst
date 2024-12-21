.. _class_ScreenIconGroup:

ScreenIconGroup 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+---------------------------------+--------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`   | :ref:`VisibleRange<class_ScreenIconGroup_property_VisibleRange>`         |
+---------------------------------+--------------------------------------------------------------------------+
| :ref:`String<class_String>`     | :ref:`groupName<class_ScreenIconGroup_property_groupName>`               |
+---------------------------------+--------------------------------------------------------------------------+
| :ref:`FontItem<class_FontItem>` | :ref:`currentFontStyle<class_ScreenIconGroup_property_currentFontStyle>` |
+---------------------------------+--------------------------------------------------------------------------+
| :ref:`MarkItem<class_MarkItem>` | :ref:`currentMarkStyle<class_ScreenIconGroup_property_currentMarkStyle>` |
+---------------------------------+--------------------------------------------------------------------------+

方法
----

+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`AddScreenIcon<class_ScreenIconGroup_method_AddScreenIcon>` **(** :ref:`ScreenIcon<class_ScreenIcon>` si **)**                                         |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`AddScreenIcons<class_ScreenIconGroup_method_AddScreenIcons>` **(** :ref:`ScreenIcon[]<class_ScreenIcon[]>` si **)**                                   |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`AddFontItem<class_ScreenIconGroup_method_AddFontItem>` **(** **)**                                                                                    |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`AddMarkItem<class_ScreenIconGroup_method_AddMarkItem>` **(** :ref:`String<class_String>` imgPath **)**                                                |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`AddBgItem<class_ScreenIconGroup_method_AddBgItem>` **(** **)**                                                                                        |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`Update<class_ScreenIconGroup_method_Update>` **(** **)**                                                                                              |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`RemoveChild<class_ScreenIconGroup_method_RemoveChild>` **(** **)**                                                                                    |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`RemoveFontItem<class_ScreenIconGroup_method_RemoveFontItem>` **(** **)**                                                                              |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`RemoveMarkItem<class_ScreenIconGroup_method_RemoveMarkItem>` **(** **)**                                                                              |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`RemoveBgItem<class_ScreenIconGroup_method_RemoveBgItem>` **(** **)**                                                                                  |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`ChangeFontColor<class_ScreenIconGroup_method_ChangeFontColor>` **(** :ref:`Color<class_Color>` color **)**                                            |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`ChangeFontStyle<class_ScreenIconGroup_method_ChangeFontStyle>` **(** :ref:`String<class_String>` fontName, :ref:`String<class_String>` fontPath **)** |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`ChangeMarkStyle<class_ScreenIconGroup_method_ChangeMarkStyle>` **(** :ref:`String<class_String>` imgPath **)**                                        |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`ClearFontItem<class_ScreenIconGroup_method_ClearFontItem>` **(** **)**                                                                                |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`ClearMarkItem<class_ScreenIconGroup_method_ClearMarkItem>` **(** **)**                                                                                |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`ClearBgItem<class_ScreenIconGroup_method_ClearBgItem>` **(** **)**                                                                                    |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`ClearByStyle<class_ScreenIconGroup_method_ClearByStyle>` **(** :ref:`Type<class_Type>` type **)**                                                     |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`Clear<class_ScreenIconGroup_method_Clear>` **(** **)**                                                                                                |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`SetFontAnchor<class_ScreenIconGroup_method_SetFontAnchor>` **(** :ref:`AnchorType<class_AnchorType>` fontAnchor **)**                                 |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`SetMarkAnchor<class_ScreenIconGroup_method_SetMarkAnchor>` **(** :ref:`AnchorType<class_AnchorType>` markAnchor **)**                                 |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`SetBgAnchor<class_ScreenIconGroup_method_SetBgAnchor>` **(** :ref:`AnchorType<class_AnchorType>` backgroundAnchor **)**                               |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`SetMarkSize<class_ScreenIconGroup_method_SetMarkSize>` **(** :ref:`Single<class_Single>` mark_size **)**                                              |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`SetTextSize<class_ScreenIconGroup_method_SetTextSize>` **(** :ref:`Single<class_Single>` text_size **)**                                              |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>` | :ref:`GetIconCount<class_ScreenIconGroup_method_GetIconCount>` **(** **)**                                                                                  |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`   | :ref:`ShowPolygonsInfo<class_ScreenIconGroup_method_ShowPolygonsInfo>` **(** **)**                                                                          |
+---------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_ScreenIconGroup_property_VisibleRange:

- :ref:`Vector2<class_Vector2>` **VisibleRange**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ScreenIconGroup_property_groupName:

- :ref:`String<class_String>` **groupName**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_ScreenIconGroup_property_currentFontStyle:

- :ref:`FontItem<class_FontItem>` **currentFontStyle**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

当前数据组使用的字体样式

----

.. _class_ScreenIconGroup_property_currentMarkStyle:

- :ref:`MarkItem<class_MarkItem>` **currentMarkStyle**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

当前数据组使用的图标样式

----


方法说明
-------

.. _class_ScreenIconGroup_method_AddScreenIcon:

- :ref:`Void<class_Void>` **AddScreenIcon** **(** :ref:`ScreenIcon<class_ScreenIcon>` si **)**



----

.. _class_ScreenIconGroup_method_AddScreenIcons:

- :ref:`Void<class_Void>` **AddScreenIcons** **(** :ref:`ScreenIcon[]<class_ScreenIcon[]>` si **)**

向IconGroup中添加数据

----

.. _class_ScreenIconGroup_method_AddFontItem:

- :ref:`Void<class_Void>` **AddFontItem** **(** **)**



----

.. _class_ScreenIconGroup_method_AddMarkItem:

- :ref:`Void<class_Void>` **AddMarkItem** **(** :ref:`String<class_String>` imgPath **)**



----

.. _class_ScreenIconGroup_method_AddBgItem:

- :ref:`Void<class_Void>` **AddBgItem** **(** **)**



----

.. _class_ScreenIconGroup_method_Update:

- :ref:`Void<class_Void>` **Update** **(** **)**



----

.. _class_ScreenIconGroup_method_RemoveChild:

- :ref:`Void<class_Void>` **RemoveChild** **(** **)**



----

.. _class_ScreenIconGroup_method_RemoveFontItem:

- :ref:`Void<class_Void>` **RemoveFontItem** **(** **)**



----

.. _class_ScreenIconGroup_method_RemoveMarkItem:

- :ref:`Void<class_Void>` **RemoveMarkItem** **(** **)**



----

.. _class_ScreenIconGroup_method_RemoveBgItem:

- :ref:`Void<class_Void>` **RemoveBgItem** **(** **)**



----

.. _class_ScreenIconGroup_method_ChangeFontColor:

- :ref:`Void<class_Void>` **ChangeFontColor** **(** :ref:`Color<class_Color>` color **)**

切换字体颜色

----

.. _class_ScreenIconGroup_method_ChangeFontStyle:

- :ref:`Void<class_Void>` **ChangeFontStyle** **(** :ref:`String<class_String>` fontName, :ref:`String<class_String>` fontPath **)**

字体样式切换

----

.. _class_ScreenIconGroup_method_ChangeMarkStyle:

- :ref:`Void<class_Void>` **ChangeMarkStyle** **(** :ref:`String<class_String>` imgPath **)**

图标样式切换

----

.. _class_ScreenIconGroup_method_ClearFontItem:

- :ref:`Void<class_Void>` **ClearFontItem** **(** **)**



----

.. _class_ScreenIconGroup_method_ClearMarkItem:

- :ref:`Void<class_Void>` **ClearMarkItem** **(** **)**



----

.. _class_ScreenIconGroup_method_ClearBgItem:

- :ref:`Void<class_Void>` **ClearBgItem** **(** **)**



----

.. _class_ScreenIconGroup_method_ClearByStyle:

- :ref:`Void<class_Void>` **ClearByStyle** **(** :ref:`Type<class_Type>` type **)**

按照样式类型清除Polygon数据

----

.. _class_ScreenIconGroup_method_Clear:

- :ref:`Void<class_Void>` **Clear** **(** **)**

清除数据组中所有样式

----

.. _class_ScreenIconGroup_method_SetFontAnchor:

- :ref:`Void<class_Void>` **SetFontAnchor** **(** :ref:`AnchorType<class_AnchorType>` fontAnchor **)**



----

.. _class_ScreenIconGroup_method_SetMarkAnchor:

- :ref:`Void<class_Void>` **SetMarkAnchor** **(** :ref:`AnchorType<class_AnchorType>` markAnchor **)**



----

.. _class_ScreenIconGroup_method_SetBgAnchor:

- :ref:`Void<class_Void>` **SetBgAnchor** **(** :ref:`AnchorType<class_AnchorType>` backgroundAnchor **)**



----

.. _class_ScreenIconGroup_method_SetMarkSize:

- :ref:`Void<class_Void>` **SetMarkSize** **(** :ref:`Single<class_Single>` mark_size **)**



----

.. _class_ScreenIconGroup_method_SetTextSize:

- :ref:`Void<class_Void>` **SetTextSize** **(** :ref:`Single<class_Single>` text_size **)**



----

.. _class_ScreenIconGroup_method_GetIconCount:

- :ref:`Int32<class_Int32>` **GetIconCount** **(** **)**



----

.. _class_ScreenIconGroup_method_ShowPolygonsInfo:

- :ref:`Void<class_Void>` **ShowPolygonsInfo** **(** **)**



----

