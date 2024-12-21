.. _class_DrawSphereTool:

DrawSphereTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制球工具

示例
----

属性
----

+-------------------------------------------------------+-----------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                         | :ref:`IsInteractive<class_DrawSphereTool_property_IsInteractive>`                       |
+-------------------------------------------------------+-----------------------------------------------------------------------------------------+
| :ref:`SphereVolumeElement<class_SphereVolumeElement>` | :ref:`SphereObject<class_DrawSphereTool_property_SphereObject>`                         |
+-------------------------------------------------------+-----------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                         | :ref:`InCenterPosition<class_DrawSphereTool_property_InCenterPosition>`                 |
+-------------------------------------------------------+-----------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                         | :ref:`InNowboundary<class_DrawSphereTool_property_InNowboundary>`                       |
+-------------------------------------------------------+-----------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>`                     | :ref:`VertexInLocalInteractive<class_DrawSphereTool_property_VertexInLocalInteractive>` |
+-------------------------------------------------------+-----------------------------------------------------------------------------------------+
| :ref:`SpatialMaterial<class_SpatialMaterial>`         | :ref:`Material<class_DrawSphereTool_property_Material>`                                 |
+-------------------------------------------------------+-----------------------------------------------------------------------------------------+
| :ref:`ImmedType<class_ImmedType>`                     | :ref:`DrawMethod<class_DrawSphereTool_property_DrawMethod>`                             |
+-------------------------------------------------------+-----------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                             | :ref:`RadialSegments<class_DrawSphereTool_property_RadialSegments>`                     |
+-------------------------------------------------------+-----------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                             | :ref:`RingSegments<class_DrawSphereTool_property_RingSegments>`                         |
+-------------------------------------------------------+-----------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                         | :ref:`norml<class_DrawSphereTool_property_norml>`                                       |
+-------------------------------------------------------+-----------------------------------------------------------------------------------------+

方法
----

+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Ready<class_DrawSphereTool_method__Ready>` **(** **)**                                                                                                |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseDown<class_DrawSphereTool_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnMouseMove<class_DrawSphereTool_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseDoubleClick<class_DrawSphereTool_method_OnMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Process<class_DrawSphereTool_method__Process>` **(** :ref:`Single<class_Single>` delta **)**                                                          |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_DrawSphereTool_property_IsInteractive:

- :ref:`Boolean<class_Boolean>` **IsInteractive**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否开启交互

----

.. _class_DrawSphereTool_property_SphereObject:

- :ref:`SphereVolumeElement<class_SphereVolumeElement>` **SphereObject**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

VolumeElement

----

.. _class_DrawSphereTool_property_InCenterPosition:

- :ref:`Vector3<class_Vector3>` **InCenterPosition**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

输入起点

----

.. _class_DrawSphereTool_property_InNowboundary:

- :ref:`Vector3<class_Vector3>` **InNowboundary**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

输入终点

----

.. _class_DrawSphereTool_property_VertexInLocalInteractive:

- :ref:`Vector3[]<class_Vector3[]>` **VertexInLocalInteractive**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

用于绘制点集合

----

.. _class_DrawSphereTool_property_Material:

- :ref:`SpatialMaterial<class_SpatialMaterial>` **Material**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

材质

----

.. _class_DrawSphereTool_property_DrawMethod:

- :ref:`ImmedType<class_ImmedType>` **DrawMethod**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

绘制方式

----

.. _class_DrawSphereTool_property_RadialSegments:

- :ref:`Int32<class_Int32>` **RadialSegments**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

段数

----

.. _class_DrawSphereTool_property_RingSegments:

- :ref:`Int32<class_Int32>` **RingSegments**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

高度段数

----

.. _class_DrawSphereTool_property_norml:

- :ref:`Vector3<class_Vector3>` **norml**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_DrawSphereTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

.. _class_DrawSphereTool_method_OnMouseDown:

- :ref:`Void<class_Void>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标按键事件（绘制球）

----

.. _class_DrawSphereTool_method_OnMouseMove:

- :ref:`Void<class_Void>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标移动事件。（绘制球）

----

.. _class_DrawSphereTool_method_OnMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **OnMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

处理鼠标双击事件

----

.. _class_DrawSphereTool_method__Process:

- :ref:`Void<class_Void>` **_Process** **(** :ref:`Single<class_Single>` delta **)**

处理逻辑

----

