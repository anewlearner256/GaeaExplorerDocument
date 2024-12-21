.. _class_RenderableObject:

RenderableObject 
===================

**Inherits:** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`               | :ref:`VisibleRange<class_RenderableObject_property_VisibleRange>`       |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`String<class_String>`                 | :ref:`Key<class_RenderableObject_property_Key>`                         |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`               | :ref:`IsInitialized<class_RenderableObject_property_IsInitialized>`     |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`               | :ref:`EnablePick<class_RenderableObject_property_EnablePick>`           |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`               | :ref:`Enable<class_RenderableObject_property_Enable>`                   |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`RenderPriority<class_RenderPriority>` | :ref:`Priority<class_RenderableObject_property_Priority>`               |
+---------------------------------------------+-------------------------------------------------------------------------+
| :ref:`UInt32<class_UInt32>`                 | :ref:`DisplayViewport<class_RenderableObject_property_DisplayViewport>` |
+---------------------------------------------+-------------------------------------------------------------------------+

方法
----

+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`SetEnablePick<class_RenderableObject_method_SetEnablePick>` **(** :ref:`Boolean<class_Boolean>` value **)**                          |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`SetEnableProcess<class_RenderableObject_method_SetEnableProcess>` **(** :ref:`Boolean<class_Boolean>` value **)**                    |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`_Ready<class_RenderableObject_method__Ready>` **(** **)**                                                                            |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`Delete<class_RenderableObject_method_Delete>` **(** **)**                                                                            |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`OnDelete<class_RenderableObject_method_OnDelete>` **(** **)**                                                                        |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                   | :ref:`OnMouseWheel<class_RenderableObject_method_OnMouseWheel>` **(** :ref:`Single<class_Single>` delta **)**                              |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                   | :ref:`OnMouseDown<class_RenderableObject_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                   | :ref:`OnMouseMove<class_RenderableObject_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                   | :ref:`OnMouseUp<class_RenderableObject_method_OnMouseUp>` **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**     |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`Update<class_RenderableObject_method_Update>` **(** **)**                                                                            |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`ForceSetVisible<class_RenderableObject_method_ForceSetVisible>` **(** :ref:`Boolean<class_Boolean>` visible **)**                    |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`UseAutoVisible<class_RenderableObject_method_UseAutoVisible>` **(** **)**                                                            |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`_Notification<class_RenderableObject_method__Notification>` **(** :ref:`Int32<class_Int32>` what **)**                               |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`Render<class_RenderableObject_method_Render>` **(** **)**                                                                            |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`Initialize<class_RenderableObject_method_Initialize>` **(** **)**                                                                    |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                       | :ref:`CompareTo<class_RenderableObject_method_CompareTo>` **(** :ref:`RenderableObject<class_RenderableObject>` other **)**                |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`_Process<class_RenderableObject_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                      |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`_UnhandledInput<class_RenderableObject_method__UnhandledInput>` **(** :ref:`InputEvent<class_InputEvent>` inputEvent **)**           |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`AddLast<class_RenderableObject_method_AddLast>` **(** :ref:`RenderableObject<class_RenderableObject>` defaultPyramidTileSet **)**    |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`Remove<class_RenderableObject_method_Remove>` **(** :ref:`RenderableObject<class_RenderableObject>` currentTile **)**                |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`RenderableObject<class_RenderableObject>` | :ref:`GetByName<class_RenderableObject_method_GetByName>` **(** :ref:`String<class_String>` name **)**                                     |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`SelectedCallBack<class_RenderableObject_method_SelectedCallBack>` **(** :ref:`Action`6<class_Action`6>` action **)**                 |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`SetDisplayViewport<class_RenderableObject_method_SetDisplayViewport>` **(** :ref:`UInt32<class_UInt32>` displayViewport **)**        |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                         | :ref:`ResetStatus<class_RenderableObject_method_ResetStatus>` **(** **)**                                                                  |
+-------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_RenderableObject_property_VisibleRange:

- :ref:`Vector2<class_Vector2>` **VisibleRange**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

可见范围

----

.. _class_RenderableObject_property_Key:

- :ref:`String<class_String>` **Key**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_RenderableObject_property_IsInitialized:

- :ref:`Boolean<class_Boolean>` **IsInitialized**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否已初始化

----

.. _class_RenderableObject_property_EnablePick:

- :ref:`Boolean<class_Boolean>` **EnablePick**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

设置为true后可通过鼠标点击拾取

----

.. _class_RenderableObject_property_Enable:

- :ref:`Boolean<class_Boolean>` **Enable**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----

.. _class_RenderableObject_property_Priority:

- :ref:`RenderPriority<class_RenderPriority>` **Priority**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

渲染优先级

----

.. _class_RenderableObject_property_DisplayViewport:

- :ref:`UInt32<class_UInt32>` **DisplayViewport**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_RenderableObject_method_SetEnablePick:

- :ref:`Void<class_Void>` **SetEnablePick** **(** :ref:`Boolean<class_Boolean>` value **)**

未知

----

.. _class_RenderableObject_method_SetEnableProcess:

- :ref:`Void<class_Void>` **SetEnableProcess** **(** :ref:`Boolean<class_Boolean>` value **)**

未知

----

.. _class_RenderableObject_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

当节点“准备好”时调用，即当节点及其子节点都已进入场景树时

----

.. _class_RenderableObject_method_Delete:

- :ref:`Void<class_Void>` **Delete** **(** **)**

释放函数

----

.. _class_RenderableObject_method_OnDelete:

- :ref:`Void<class_Void>` **OnDelete** **(** **)**

当触发释放事件时调用

----

.. _class_RenderableObject_method_OnMouseWheel:

- :ref:`Boolean<class_Boolean>` **OnMouseWheel** **(** :ref:`Single<class_Single>` delta **)**

当触发鼠标滚轮事件时调用

----

.. _class_RenderableObject_method_OnMouseDown:

- :ref:`Boolean<class_Boolean>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**

当鼠标按下被调用

----

.. _class_RenderableObject_method_OnMouseMove:

- :ref:`Boolean<class_Boolean>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**

当鼠标移动时触发

----

.. _class_RenderableObject_method_OnMouseUp:

- :ref:`Boolean<class_Boolean>` **OnMouseUp** **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**

当鼠标按键被释放时调用

----

.. _class_RenderableObject_method_Update:

- :ref:`Void<class_Void>` **Update** **(** **)**

当渲染对象发生变化时进行更新

----

.. _class_RenderableObject_method_ForceSetVisible:

- :ref:`Void<class_Void>` **ForceSetVisible** **(** :ref:`Boolean<class_Boolean>` visible **)**

强制指定可见性，不再受VisibleRange影响

----

.. _class_RenderableObject_method_UseAutoVisible:

- :ref:`Void<class_Void>` **UseAutoVisible** **(** **)**

取消强制指定的可见性，由程序自动根据VisibleRange判断可见性

----

.. _class_RenderableObject_method__Notification:

- :ref:`Void<class_Void>` **_Notification** **(** :ref:`Int32<class_Int32>` what **)**

未知

----

.. _class_RenderableObject_method_Render:

- :ref:`Void<class_Void>` **Render** **(** **)**

对象渲染在这个函数中进行

----

.. _class_RenderableObject_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** **)**

初始化对象

----

.. _class_RenderableObject_method_CompareTo:

- :ref:`Int32<class_Int32>` **CompareTo** **(** :ref:`RenderableObject<class_RenderableObject>` other **)**

与另一个可渲染对象比较渲染优先级

----

.. _class_RenderableObject_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

在主循环的处理步骤中调用.处理发生在每一帧并且尽可能快

----

.. _class_RenderableObject_method__UnhandledInput:

- :ref:`Void<class_Void>` **_UnhandledInput** **(** :ref:`InputEvent<class_InputEvent>` inputEvent **)**

处理没有被其他控件拦截的输入

----

.. _class_RenderableObject_method_AddLast:

- :ref:`Void<class_Void>` **AddLast** **(** :ref:`RenderableObject<class_RenderableObject>` defaultPyramidTileSet **)**

将某个可渲染对象挂载到此对象上，作为子节点

----

.. _class_RenderableObject_method_Remove:

- :ref:`Void<class_Void>` **Remove** **(** :ref:`RenderableObject<class_RenderableObject>` currentTile **)**

移除某个子节点

----

.. _class_RenderableObject_method_GetByName:

- :ref:`RenderableObject<class_RenderableObject>` **GetByName** **(** :ref:`String<class_String>` name **)**

通过名字获取对应子节点

----

.. _class_RenderableObject_method_SelectedCallBack:

- :ref:`Void<class_Void>` **SelectedCallBack** **(** :ref:`Action`6<class_Action`6>` action **)**

被点击后的回调

----

.. _class_RenderableObject_method_SetDisplayViewport:

- :ref:`Void<class_Void>` **SetDisplayViewport** **(** :ref:`UInt32<class_UInt32>` displayViewport **)**

设置该对象要显示在哪些视口中

----

.. _class_RenderableObject_method_ResetStatus:

- :ref:`Void<class_Void>` **ResetStatus** **(** **)**



----

