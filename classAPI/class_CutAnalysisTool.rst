.. _class_CutAnalysisTool:

CutAnalysisTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------------------------+------------------------------------------------------------------------+
| :ref:`CutModeEnum<class_CutModeEnum>`           | :ref:`CutAnalysisMode<class_CutAnalysisTool_property_CutAnalysisMode>` |
+-------------------------------------------------+------------------------------------------------------------------------+
| :ref:`CutAxisEnum<class_CutAxisEnum>`           | :ref:`CutAnalysisAxis<class_CutAnalysisTool_property_CutAnalysisAxis>` |
+-------------------------------------------------+------------------------------------------------------------------------+
| :ref:`MeshInstance<class_MeshInstance>`         | :ref:`ClipPlane<class_CutAnalysisTool_property_ClipPlane>`             |
+-------------------------------------------------+------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                       | :ref:`HoverColor<class_CutAnalysisTool_property_HoverColor>`           |
+-------------------------------------------------+------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                       | :ref:`DeafaultColor<class_CutAnalysisTool_property_DeafaultColor>`     |
+-------------------------------------------------+------------------------------------------------------------------------+
| :ref:`CutDirectionEnum<class_CutDirectionEnum>` | :ref:`CutDirection<class_CutAnalysisTool_property_CutDirection>`       |
+-------------------------------------------------+------------------------------------------------------------------------+

方法
----

+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Ready<class_CutAnalysisTool_method__Ready>` **(** **)**                                                                                  |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`CreateCutPlaneData<class_CutAnalysisTool_method_CreateCutPlaneData>` **(** :ref:`String<class_String>` targetname **)**                   |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnMouseDown<class_CutAnalysisTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnMouseUp<class_CutAnalysisTool_method_OnMouseUp>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**     |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnMouseMove<class_CutAnalysisTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_PhysicsProcess<class_CutAnalysisTool_method__PhysicsProcess>` **(** :ref:`Single<class_Single>` delta **)**                              |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_CutAnalysisTool_property_CutAnalysisMode:

- :ref:`CutModeEnum<class_CutModeEnum>` **CutAnalysisMode**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

裁剪模式

----

.. _class_CutAnalysisTool_property_CutAnalysisAxis:

- :ref:`CutAxisEnum<class_CutAxisEnum>` **CutAnalysisAxis**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

裁剪轴

----

.. _class_CutAnalysisTool_property_ClipPlane:

- :ref:`MeshInstance<class_MeshInstance>` **ClipPlane**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

裁剪平面

----

.. _class_CutAnalysisTool_property_HoverColor:

- :ref:`Color<class_Color>` **HoverColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

鼠标悬浮时颜色

----

.. _class_CutAnalysisTool_property_DeafaultColor:

- :ref:`Color<class_Color>` **DeafaultColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_CutAnalysisTool_property_CutDirection:

- :ref:`CutDirectionEnum<class_CutDirectionEnum>` **CutDirection**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_CutAnalysisTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**



----

.. _class_CutAnalysisTool_method_CreateCutPlaneData:

- :ref:`Void<class_Void>` **CreateCutPlaneData** **(** :ref:`String<class_String>` targetname **)**



----

.. _class_CutAnalysisTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**



----

.. _class_CutAnalysisTool_method_OnMouseUp:

- :ref:`Void<class_Void>` **OnMouseUp** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**



----

.. _class_CutAnalysisTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**



----

.. _class_CutAnalysisTool_method__PhysicsProcess:

- :ref:`Void<class_Void>` **_PhysicsProcess** **(** :ref:`Single<class_Single>` delta **)**



----

