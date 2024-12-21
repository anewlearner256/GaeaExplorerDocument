.. _class_BaseConvertVolumeTool:

BaseConvertVolumeTool 
===================

**Inherits:** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

绘制面转体

示例
----

属性
----

+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                               | :ref:`IsStart<class_BaseConvertVolumeTool_property_IsStart>`                                   |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                               | :ref:`IsInteractive<class_BaseConvertVolumeTool_property_IsInteractive>`                       |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                               | :ref:`IsClick<class_BaseConvertVolumeTool_property_IsClick>`                                   |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                               | :ref:`CenterPoint<class_BaseConvertVolumeTool_property_CenterPoint>`                           |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                               | :ref:`BoundaryPoint<class_BaseConvertVolumeTool_property_BoundaryPoint>`                       |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                                 | :ref:`OffsetHeight<class_BaseConvertVolumeTool_property_OffsetHeight>`                         |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`                                 | :ref:`Width<class_BaseConvertVolumeTool_property_Width>`                                       |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`                               | :ref:`Sp0<class_BaseConvertVolumeTool_property_Sp0>`                                           |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                                   | :ref:`Btnindex<class_BaseConvertVolumeTool_property_Btnindex>`                                 |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`ImmedType<class_ImmedType>`                           | :ref:`DrawMethod<class_BaseConvertVolumeTool_property_DrawMethod>`                             |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`SpatialMaterial<class_SpatialMaterial>`               | :ref:`Material<class_BaseConvertVolumeTool_property_Material>`                                 |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Action<class_Action>`                                 | :ref:`OverDrawVol<class_BaseConvertVolumeTool_property_OverDrawVol>`                           |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>`                           | :ref:`VertexInLocalInteractive<class_BaseConvertVolumeTool_property_VertexInLocalInteractive>` |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`CommonlyVolumeElement<class_CommonlyVolumeElement>`   | :ref:`VolumeElementObject<class_BaseConvertVolumeTool_property_VolumeElementObject>`           |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+
| :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` | :ref:`Element<class_BaseConvertVolumeTool_property_Element>`                                   |
+-------------------------------------------------------------+------------------------------------------------------------------------------------------------+

方法
----

+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`UpdateMouseDown<class_BaseConvertVolumeTool_method_UpdateMouseDown>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`UpdateMouseMove<class_BaseConvertVolumeTool_method_UpdateMouseMove>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**               |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`UpdateMouseDoubleClick<class_BaseConvertVolumeTool_method_UpdateMouseDoubleClick>` **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_UpdateProcess<class_BaseConvertVolumeTool_method__UpdateProcess>` **(** :ref:`Single<class_Single>` delta, :ref:`Int32<class_Int32>` type **)**                      |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`AutoDraw<class_BaseConvertVolumeTool_method_AutoDraw>` **(** :ref:`Single<class_Single>` delta, :ref:`Int32<class_Int32>` type **)**                                  |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`UpdateDispose<class_BaseConvertVolumeTool_method_UpdateDispose>` **(** :ref:`Boolean<class_Boolean>` disposing **)**                                                  |
+-------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_BaseConvertVolumeTool_property_IsStart:

- :ref:`Boolean<class_Boolean>` **IsStart**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否开启挤压

----

.. _class_BaseConvertVolumeTool_property_IsInteractive:

- :ref:`Boolean<class_Boolean>` **IsInteractive**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否开启交互

----

.. _class_BaseConvertVolumeTool_property_IsClick:

- :ref:`Boolean<class_Boolean>` **IsClick**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否开启点击事件

----

.. _class_BaseConvertVolumeTool_property_CenterPoint:

- :ref:`Vector3<class_Vector3>` **CenterPoint**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

起始点（笛卡尔）

----

.. _class_BaseConvertVolumeTool_property_BoundaryPoint:

- :ref:`Vector3<class_Vector3>` **BoundaryPoint**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

终止点（笛卡尔）

----

.. _class_BaseConvertVolumeTool_property_OffsetHeight:

- :ref:`Double<class_Double>` **OffsetHeight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

高度设置

----

.. _class_BaseConvertVolumeTool_property_Width:

- :ref:`Double<class_Double>` **Width**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

宽度

----

.. _class_BaseConvertVolumeTool_property_Sp0:

- :ref:`Vector2<class_Vector2>` **Sp0**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

存储点（用来创建面）

----

.. _class_BaseConvertVolumeTool_property_Btnindex:

- :ref:`Int32<class_Int32>` **Btnindex**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

步骤索引（ENMUM）

----

.. _class_BaseConvertVolumeTool_property_DrawMethod:

- :ref:`ImmedType<class_ImmedType>` **DrawMethod**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

绘制方式

----

.. _class_BaseConvertVolumeTool_property_Material:

- :ref:`SpatialMaterial<class_SpatialMaterial>` **Material**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

材质

----

.. _class_BaseConvertVolumeTool_property_OverDrawVol:

- :ref:`Action<class_Action>` **OverDrawVol**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

回调

----

.. _class_BaseConvertVolumeTool_property_VertexInLocalInteractive:

- :ref:`Vector3[]<class_Vector3[]>` **VertexInLocalInteractive**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

用于绘制点集合

----

.. _class_BaseConvertVolumeTool_property_VolumeElementObject:

- :ref:`CommonlyVolumeElement<class_CommonlyVolumeElement>` **VolumeElementObject**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

体对象

----

.. _class_BaseConvertVolumeTool_property_Element:

- :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` **Element**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

面Element要素

----


方法说明
-------

.. _class_BaseConvertVolumeTool_method_UpdateMouseDown:

- :ref:`Void<class_Void>` **UpdateMouseDown** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

绘制面转体（点击）

----

.. _class_BaseConvertVolumeTool_method_UpdateMouseMove:

- :ref:`Void<class_Void>` **UpdateMouseMove** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

绘制面转体（移动）

----

.. _class_BaseConvertVolumeTool_method_UpdateMouseDoubleClick:

- :ref:`Boolean<class_Boolean>` **UpdateMouseDoubleClick** **(** :ref:`Vector2<class_Vector2>` screenpos, :ref:`Int32<class_Int32>` btn **)**

双击事件

----

.. _class_BaseConvertVolumeTool_method__UpdateProcess:

- :ref:`Void<class_Void>` **_UpdateProcess** **(** :ref:`Single<class_Single>` delta, :ref:`Int32<class_Int32>` type **)**

处理逻辑

----

.. _class_BaseConvertVolumeTool_method_AutoDraw:

- :ref:`Void<class_Void>` **AutoDraw** **(** :ref:`Single<class_Single>` delta, :ref:`Int32<class_Int32>` type **)**

绘制

----

.. _class_BaseConvertVolumeTool_method_UpdateDispose:

- :ref:`Void<class_Void>` **UpdateDispose** **(** :ref:`Boolean<class_Boolean>` disposing **)**

Dispose

----

