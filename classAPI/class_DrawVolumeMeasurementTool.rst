.. _class_DrawVolumeMeasurementTool:

DrawVolumeMeasurementTool 
===================

**Inherits:** :ref:`MeasureTool<class_MeasureTool>` **<** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制体积测量

示例
----

属性
----

+-------------------------------------------------------------+------------------------------------------------------------------------------------+
| :ref:`Action<class_Action>`                                 | :ref:`OverDrawCallback<class_DrawVolumeMeasurementTool_property_OverDrawCallback>` |
+-------------------------------------------------------------+------------------------------------------------------------------------------------+
| :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` | :ref:`Element<class_DrawVolumeMeasurementTool_property_Element>`                   |
+-------------------------------------------------------------+------------------------------------------------------------------------------------+
| :ref:`HoleItem<class_HoleItem>`                             | :ref:`_Holeitem<class_DrawVolumeMeasurementTool_property__Holeitem>`               |
+-------------------------------------------------------------+------------------------------------------------------------------------------------+
| :ref:`MeshInstance<class_MeshInstance>`                     | :ref:`_box<class_DrawVolumeMeasurementTool_property__box>`                         |
+-------------------------------------------------------------+------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`                                 | :ref:`holeDepth<class_DrawVolumeMeasurementTool_property_holeDepth>`               |
+-------------------------------------------------------------+------------------------------------------------------------------------------------+

方法
----

+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Ready<class_DrawVolumeMeasurementTool_method__Ready>` **(** **)**                                                                                                |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseDown<class_DrawVolumeMeasurementTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseMove<class_DrawVolumeMeasurementTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseDoubleClick<class_DrawVolumeMeasurementTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Process<class_DrawVolumeMeasurementTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                          |
+-------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawVolumeMeasurementTool_property_OverDrawCallback:

- :ref:`Action<class_Action>` **OverDrawCallback**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

回调

----

.. _class_DrawVolumeMeasurementTool_property_Element:

- :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面要素

----

.. _class_DrawVolumeMeasurementTool_property__Holeitem:

- :ref:`HoleItem<class_HoleItem>` **_Holeitem**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

挖方

----

.. _class_DrawVolumeMeasurementTool_property__box:

- :ref:`MeshInstance<class_MeshInstance>` **_box**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

材质

----

.. _class_DrawVolumeMeasurementTool_property_holeDepth:

- :ref:`Single<class_Single>` **holeDepth**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

深度

----


方法说明
-------

.. _class_DrawVolumeMeasurementTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_DrawVolumeMeasurementTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件（绘制体积测量）

----

.. _class_DrawVolumeMeasurementTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。（绘制体积测量）

----

.. _class_DrawVolumeMeasurementTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标双击事件

----

.. _class_DrawVolumeMeasurementTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

