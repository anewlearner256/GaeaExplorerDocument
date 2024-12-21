.. _class_BaseTool:

BaseTool 
===================

**Inherits:** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

工具基类

示例
----

属性
----

+-------------------------------+-----------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`HeightOffset<class_BaseTool_property_HeightOffset>`                         |
+-------------------------------+-----------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`isPressed<class_BaseTool_property_isPressed>`                               |
+-------------------------------+-----------------------------------------------------------------------------------+
| :ref:`Color<class_Color>`     | :ref:`Color<class_BaseTool_property_Color>`                                       |
+-------------------------------+-----------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`DeleteElementOnDispose<class_BaseTool_property_DeleteElementOnDispose>`     |
+-------------------------------+-----------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`CreateElementOnCompleted<class_BaseTool_property_CreateElementOnCompleted>` |
+-------------------------------+-----------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`ShowMessage<class_BaseTool_property_ShowMessage>`                           |
+-------------------------------+-----------------------------------------------------------------------------------+
| :ref:`Action<class_Action>`   | :ref:`OverDraw<class_BaseTool_property_OverDraw>`                                 |
+-------------------------------+-----------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`NeedIntersectWithMesh<class_BaseTool_property_NeedIntersectWithMesh>`       |
+-------------------------------+-----------------------------------------------------------------------------------+

方法
----

+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_UnhandledInput<class_BaseTool_method__UnhandledInput>` **(** :ref:`InputEvent<class_InputEvent>` inputEvent **)**                               |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`SetCurrentTool<class_BaseTool_method_SetCurrentTool>` **(** :ref:`BaseTool<class_BaseTool>` baseTool **)**                                       |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseDoubleClick<class_BaseTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseMove<class_BaseTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseDown<class_BaseTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseUp<class_BaseTool_method_OnMouseUp>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**                   |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseWheel<class_BaseTool_method_OnMouseWheel>` **(** :ref:`Single<class_Single>` delta **)**                                                  |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`Message<class_BaseTool_method_Message>` **(** :ref:`Label<class_Label>` message **)**                                                            |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`MessagePosition<class_BaseTool_method_MessagePosition>` **(** :ref:`Label<class_Label>` message **)**                                            |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`StyleOverride<class_BaseTool_method_StyleOverride>` **(** :ref:`Label<class_Label>` label **)**                                                  |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_BaseTool_property_HeightOffset:

- :ref:`Single<class_Single>` **HeightOffset**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

偏移高度

----

.. _class_BaseTool_property_isPressed:

- :ref:`Boolean<class_Boolean>` **isPressed**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否被按下

----

.. _class_BaseTool_property_Color:

- :ref:`Color<class_Color>` **Color**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

工具颜色，默认为Color(0.5f, 0.77f, 0.45f, 0.6f)

----

.. _class_BaseTool_property_DeleteElementOnDispose:

- :ref:`Boolean<class_Boolean>` **DeleteElementOnDispose**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

销毁工具时是否删除Element，默认为true

----

.. _class_BaseTool_property_CreateElementOnCompleted:

- :ref:`Boolean<class_Boolean>` **CreateElementOnCompleted**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

绘制完成后是否创建Element，默认为true

----

.. _class_BaseTool_property_ShowMessage:

- :ref:`Boolean<class_Boolean>` **ShowMessage**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否显示信息

----

.. _class_BaseTool_property_OverDraw:

- :ref:`Action<class_Action>` **OverDraw**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

绘制完成的回调事件

----

.. _class_BaseTool_property_NeedIntersectWithMesh:

- :ref:`Boolean<class_Boolean>` **NeedIntersectWithMesh**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否与其他模型交互，默认为true

----


方法说明
-------

.. _class_BaseTool_method__UnhandledInput:

- :ref:`Void<class_Void>` **_UnhandledInput** **(** :ref:`InputEvent<class_InputEvent>` inputEvent **)**

处理鼠标事件

----

.. _class_BaseTool_method_SetCurrentTool:

- :ref:`Void<class_Void>` **SetCurrentTool** **(** :ref:`BaseTool<class_BaseTool>` baseTool **)**

将当前工具设置为指定的工具。

----

.. _class_BaseTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标双击事件。

----

.. _class_BaseTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_BaseTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_BaseTool_method_OnMouseUp:

- :ref:`Void<class_Void>` **OnMouseUp** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

鼠标按键释放事件

----

.. _class_BaseTool_method_OnMouseWheel:

- :ref:`Void<class_Void>` **OnMouseWheel** **(** :ref:`Single<class_Single>` delta **)**

处理鼠标滚轮事件

----

.. _class_BaseTool_method_Message:

- :ref:`Void<class_Void>` **Message** **(** :ref:`Label<class_Label>` message **)**

提示信息文字标签

----

.. _class_BaseTool_method_MessagePosition:

- :ref:`Void<class_Void>` **MessagePosition** **(** :ref:`Label<class_Label>` message **)**

计算提示信息文字标签的位置

----

.. _class_BaseTool_method_StyleOverride:

- :ref:`Void<class_Void>` **StyleOverride** **(** :ref:`Label<class_Label>` label **)**

修改标签的样式

----

