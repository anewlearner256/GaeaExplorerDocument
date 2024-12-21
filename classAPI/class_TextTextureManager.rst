.. _class_TextTextureManager:

TextTextureManager 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------------------------+-------------------------------------------------------------------------+
| :ref:`TextTextureManager<class_TextTextureManager>` | :ref:`Instance<class_TextTextureManager_property_Instance>`             |
+-----------------------------------------------------+-------------------------------------------------------------------------+
| :ref:`FontTexture<class_FontTexture>`               | :ref:`currentTexture<class_TextTextureManager_property_currentTexture>` |
+-----------------------------------------------------+-------------------------------------------------------------------------+

方法
----

+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`InitFontTexture<class_TextTextureManager_method_InitFontTexture>` **(** **)**                                                          |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnInitFontTexture<class_TextTextureManager_method_OnInitFontTexture>` **(** :ref:`Boolean<class_Boolean>` isok **)**                   |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Update<class_TextTextureManager_method_Update>` **(** **)**                                                                            |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`ChangeFont<class_TextTextureManager_method_ChangeFont>` **(** :ref:`String<class_String>` fontname, :ref:`Font<class_Font>` font **)** |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`ChangeFont<class_TextTextureManager_method_ChangeFont>` **(** :ref:`String<class_String>` fontname **)**                               |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Save<class_TextTextureManager_method_Save>` **(** :ref:`String<class_String>` path **)**                                               |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_TextTextureManager_property_Instance:

- :ref:`TextTextureManager<class_TextTextureManager>` **Instance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_TextTextureManager_property_currentTexture:

- :ref:`FontTexture<class_FontTexture>` **currentTexture**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

当前使用的纹理

----


方法说明
-------

.. _class_TextTextureManager_method_InitFontTexture:

- :ref:`Void<class_Void>` **InitFontTexture** **(** **)**

绘制128-32个字符

----

.. _class_TextTextureManager_method_OnInitFontTexture:

- :ref:`Void<class_Void>` **OnInitFontTexture** **(** :ref:`Boolean<class_Boolean>` isok **)**



----

.. _class_TextTextureManager_method_Update:

- :ref:`Void<class_Void>` **Update** **(** **)**

手动控制更新纹理

----

.. _class_TextTextureManager_method_ChangeFont:

- :ref:`Void<class_Void>` **ChangeFont** **(** :ref:`String<class_String>` fontname, :ref:`Font<class_Font>` font **)**

切换字体，并传入新字体

----

.. _class_TextTextureManager_method_ChangeFont:

- :ref:`Void<class_Void>` **ChangeFont** **(** :ref:`String<class_String>` fontname **)**

切换字体

----

.. _class_TextTextureManager_method_Save:

- :ref:`Void<class_Void>` **Save** **(** :ref:`String<class_String>` path **)**



----

