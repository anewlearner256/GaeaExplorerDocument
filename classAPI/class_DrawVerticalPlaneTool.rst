.. _class_DrawVerticalPlaneTool:

DrawVerticalPlaneTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制垂直平面工具

示例
----

属性
----

+-----------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`MeshInstance<class_MeshInstance>` | :ref:`VerticalPlaneMeshinstance<class_DrawVerticalPlaneTool_property_VerticalPlaneMeshinstance>` |
+-----------------------------------------+--------------------------------------------------------------------------------------------------+

方法
----

+-----------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Ready<class_DrawVerticalPlaneTool_method__Ready>` **(** **)**                                                                                  |
+-----------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseDown<class_DrawVerticalPlaneTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-----------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`OnMouseMove<class_DrawVerticalPlaneTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-----------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Process<class_DrawVerticalPlaneTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                            |
+-----------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`ArrayMesh<class_ArrayMesh>` | :ref:`GetArrayMesh<class_DrawVerticalPlaneTool_method_GetArrayMesh>` **(** **)**                                                                      |
+-----------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawVerticalPlaneTool_property_VerticalPlaneMeshinstance:

- :ref:`MeshInstance<class_MeshInstance>` **VerticalPlaneMeshinstance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_DrawVerticalPlaneTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_DrawVerticalPlaneTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件

----

.. _class_DrawVerticalPlaneTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。

----

.. _class_DrawVerticalPlaneTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

.. _class_DrawVerticalPlaneTool_method_GetArrayMesh:

- :ref:`ArrayMesh<class_ArrayMesh>` **GetArrayMesh** **(** **)**

将水平面转换为ArrayMesh对象

----

