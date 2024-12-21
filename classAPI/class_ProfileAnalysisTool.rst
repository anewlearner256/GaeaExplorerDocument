.. _class_ProfileAnalysisTool:

ProfileAnalysisTool 
===================

**Inherits:** :ref:`DrawSquareTool<class_DrawSquareTool>` **<** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制横坡面工具

示例
----

属性
----

+-------------------------------+--------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`   | :ref:`HoleDepth<class_ProfileAnalysisTool_property_HoleDepth>`                 |
+-------------------------------+--------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`MeterOfUV<class_ProfileAnalysisTool_property_MeterOfUV>`                 |
+-------------------------------+--------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`NeedNormalTexture<class_ProfileAnalysisTool_property_NeedNormalTexture>` |
+-------------------------------+--------------------------------------------------------------------------------+

方法
----

+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Ready<class_ProfileAnalysisTool_method__Ready>` **(** **)**                                                                                  |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnMouseDown<class_ProfileAnalysisTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnMouseMove<class_ProfileAnalysisTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Process<class_ProfileAnalysisTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                            |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_ProfileAnalysisTool_property_HoleDepth:

- :ref:`Double<class_Double>` **HoleDepth**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

横坡面深度

----

.. _class_ProfileAnalysisTool_property_MeterOfUV:

- :ref:`Single<class_Single>` **MeterOfUV**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

多少米重复一次贴图

----

.. _class_ProfileAnalysisTool_property_NeedNormalTexture:

- :ref:`Boolean<class_Boolean>` **NeedNormalTexture**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否加载法线贴图

----


方法说明
-------

.. _class_ProfileAnalysisTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_ProfileAnalysisTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_ProfileAnalysisTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_ProfileAnalysisTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

