.. _class_ScreenGUIElement:

ScreenGUIElement 
===================

**Inherits:** :ref:`Geography2DRenderableObject<class_Geography2DRenderableObject>` **<** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

图标Element

示例
----

属性
----

+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`AnchorType<class_AnchorType>` | :ref:`ConnectAnchor<class_ScreenGUIElement_property_ConnectAnchor>`         |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`AnchorType<class_AnchorType>` | :ref:`PositionAnchor<class_ScreenGUIElement_property_PositionAnchor>`       |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Control<class_Control>`       | :ref:`Root<class_ScreenGUIElement_property_Root>`                           |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`String<class_String>`         | :ref:`DivID<class_ScreenGUIElement_property_DivID>`                         |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`       | :ref:`ScreenOffset<class_ScreenGUIElement_property_ScreenOffset>`           |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`       | :ref:`UseScreenPosition<class_ScreenGUIElement_property_UseScreenPosition>` |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Action<class_Action>`         | :ref:`OnHitElement<class_ScreenGUIElement_property_OnHitElement>`           |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`       | :ref:`DrawLine<class_ScreenGUIElement_property_DrawLine>`                   |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Color<class_Color>`           | :ref:`LineColor<class_ScreenGUIElement_property_LineColor>`                 |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Single<class_Single>`         | :ref:`LineWidth<class_ScreenGUIElement_property_LineWidth>`                 |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Color<class_Color>`           | :ref:`AnchorPointColor<class_ScreenGUIElement_property_AnchorPointColor>`   |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Single<class_Single>`         | :ref:`AnchorPointSize<class_ScreenGUIElement_property_AnchorPointSize>`     |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`       | :ref:`RectSize<class_ScreenGUIElement_property_RectSize>`                   |
+-------------------------------------+-----------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`       | :ref:`RectPosition<class_ScreenGUIElement_property_RectPosition>`           |
+-------------------------------------+-----------------------------------------------------------------------------+

方法
----

+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`Initialize<class_ScreenGUIElement_method_Initialize>` **(** **)**                                                                |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`Render<class_ScreenGUIElement_method_Render>` **(** **)**                                                                        |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>` | :ref:`ComputeAnchor<class_ScreenGUIElement_method_ComputeAnchor>` **(** :ref:`AnchorType<class_AnchorType>` type **)**                 |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`HitTest<class_ScreenGUIElement_method_HitTest>` **(** :ref:`Vector2<class_Vector2>` position **)**                               |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseUp<class_ScreenGUIElement_method_OnMouseUp>` **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_ScreenGUIElement_property_ConnectAnchor:

- :ref:`AnchorType<class_AnchorType>` **ConnectAnchor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_ScreenGUIElement_property_PositionAnchor:

- :ref:`AnchorType<class_AnchorType>` **PositionAnchor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_ScreenGUIElement_property_Root:

- :ref:`Control<class_Control>` **Root**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_ScreenGUIElement_property_DivID:

- :ref:`String<class_String>` **DivID**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

网页div的id名字

----

.. _class_ScreenGUIElement_property_ScreenOffset:

- :ref:`Vector2<class_Vector2>` **ScreenOffset**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

屏幕偏移位置

----

.. _class_ScreenGUIElement_property_UseScreenPosition:

- :ref:`Boolean<class_Boolean>` **UseScreenPosition**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否使用屏幕位置

----

.. _class_ScreenGUIElement_property_OnHitElement:

- :ref:`Action<class_Action>` **OnHitElement**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

选中Element事件

----

.. _class_ScreenGUIElement_property_DrawLine:

- :ref:`Boolean<class_Boolean>` **DrawLine**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否绘制锚点与标注框的连线

----

.. _class_ScreenGUIElement_property_LineColor:

- :ref:`Color<class_Color>` **LineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

锚点与标注框的连线的颜色

----

.. _class_ScreenGUIElement_property_LineWidth:

- :ref:`Single<class_Single>` **LineWidth**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

锚点与标注框的连线的宽度

----

.. _class_ScreenGUIElement_property_AnchorPointColor:

- :ref:`Color<class_Color>` **AnchorPointColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

锚点的颜色

----

.. _class_ScreenGUIElement_property_AnchorPointSize:

- :ref:`Single<class_Single>` **AnchorPointSize**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

锚点的大小

----

.. _class_ScreenGUIElement_property_RectSize:

- :ref:`Vector2<class_Vector2>` **RectSize**

+----------+---+
| *Getter* |   |
+----------+---+

标注框的大小

----

.. _class_ScreenGUIElement_property_RectPosition:

- :ref:`Vector2<class_Vector2>` **RectPosition**

+----------+---+
| *Getter* |   |
+----------+---+

标注框的位置

----


方法说明
-------

.. _class_ScreenGUIElement_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** **)**

初始化函数

----

.. _class_ScreenGUIElement_method_Render:

- :ref:`Void<class_Void>` **Render** **(** **)**

渲染函数

----

.. _class_ScreenGUIElement_method_ComputeAnchor:

- :ref:`Vector2<class_Vector2>` **ComputeAnchor** **(** :ref:`AnchorType<class_AnchorType>` type **)**

未知

----

.. _class_ScreenGUIElement_method_HitTest:

- :ref:`Boolean<class_Boolean>` **HitTest** **(** :ref:`Vector2<class_Vector2>` position **)**

碰撞检测

----

.. _class_ScreenGUIElement_method_OnMouseUp:

- :ref:`Boolean<class_Boolean>` **OnMouseUp** **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**

鼠标是否弹起

----

