.. _class_QueryServer:

QueryServer 
===================

**Inherits:** :ref:`Object<class_Object>`

描述
----

查询服务
约定: 
2层作为拾取层
3层作为裁剪层

示例
----

属性
----

+-----------------------------------------------+----------------------------------------------------------------------------+
| :ref:`QueryServer<class_QueryServer>`         | :ref:`Instance<class_QueryServer_property_Instance>`                       |
+-----------------------------------------------+----------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                 | :ref:`Enable<class_QueryServer_property_Enable>`                           |
+-----------------------------------------------+----------------------------------------------------------------------------+
| :ref:`MeshInstance<class_MeshInstance>`       | :ref:`ClipBox<class_QueryServer_property_ClipBox>`                         |
+-----------------------------------------------+----------------------------------------------------------------------------+
| :ref:`SpatialMaterial<class_SpatialMaterial>` | :ref:`CurrentMaterial<class_QueryServer_property_CurrentMaterial>`         |
+-----------------------------------------------+----------------------------------------------------------------------------+
| :ref:`SpatialMaterial<class_SpatialMaterial>` | :ref:`ClipBoxMaterial<class_QueryServer_property_ClipBoxMaterial>`         |
+-----------------------------------------------+----------------------------------------------------------------------------+
| :ref:`ChildrenItem<class_ChildrenItem>`       | :ref:`CurrentSceneElement<class_QueryServer_property_CurrentSceneElement>` |
+-----------------------------------------------+----------------------------------------------------------------------------+

方法
----

+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`AddHitFeatureLayer<class_QueryServer_method_AddHitFeatureLayer>` **(** :ref:`FeatureLayer<class_FeatureLayer>` featureLayer **)**                                                                                                    |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`AddHitIconElement<class_QueryServer_method_AddHitIconElement>` **(** :ref:`Element<class_Element>` element **)**                                                                                                                     |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`ClearClip<class_QueryServer_method_ClearClip>` **(** :ref:`MeshInstance<class_MeshInstance>` meshins **)**                                                                                                                           |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`UpdateClipBox4MeshInstance<class_QueryServer_method_UpdateClipBox4MeshInstance>` **(** :ref:`MeshInstance<class_MeshInstance>` meshins **)**                                                                                         |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`AddHitMeshInstance<class_QueryServer_method_AddHitMeshInstance>` **(** :ref:`ModelElement<class_ModelElement>` model, :ref:`MeshInstance<class_MeshInstance>` hitableMeshInstance, :ref:`Action`2<class_Action`2>` hitCallback **)** |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnGeometryHit<class_QueryServer_method_OnGeometryHit>` **(** :ref:`UInt64<class_UInt64>` id, :ref:`Vector3<class_Vector3>` pos **)**                                                                                                 |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`OnElementHit<class_QueryServer_method_OnElementHit>` **(** :ref:`Feature<class_Feature>` feature **)**                                                                                                                               |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`RayIntersectsTriangle<class_QueryServer_method_RayIntersectsTriangle>` **(** :ref:`UInt64<class_UInt64>` id, :ref:`Vector3<class_Vector3>` origin, :ref:`Vector3<class_Vector3>` hitpoint **)**                                      |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`GetCurrentPositionByMouse<class_QueryServer_method_GetCurrentPositionByMouse>` **(** :ref:`Boolean<class_Boolean>` needIntersectWithMesh **)**                                                                                       |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_QueryServer_property_Instance:

- :ref:`QueryServer<class_QueryServer>` **Instance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_QueryServer_property_Enable:

- :ref:`Boolean<class_Boolean>` **Enable**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_QueryServer_property_ClipBox:

- :ref:`MeshInstance<class_MeshInstance>` **ClipBox**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_QueryServer_property_CurrentMaterial:

- :ref:`SpatialMaterial<class_SpatialMaterial>` **CurrentMaterial**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_QueryServer_property_ClipBoxMaterial:

- :ref:`SpatialMaterial<class_SpatialMaterial>` **ClipBoxMaterial**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_QueryServer_property_CurrentSceneElement:

- :ref:`ChildrenItem<class_ChildrenItem>` **CurrentSceneElement**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_QueryServer_method_AddHitFeatureLayer:

- :ref:`Void<class_Void>` **AddHitFeatureLayer** **(** :ref:`FeatureLayer<class_FeatureLayer>` featureLayer **)**



----

.. _class_QueryServer_method_AddHitIconElement:

- :ref:`Void<class_Void>` **AddHitIconElement** **(** :ref:`Element<class_Element>` element **)**



----

.. _class_QueryServer_method_ClearClip:

- :ref:`Void<class_Void>` **ClearClip** **(** :ref:`MeshInstance<class_MeshInstance>` meshins **)**



----

.. _class_QueryServer_method_UpdateClipBox4MeshInstance:

- :ref:`Void<class_Void>` **UpdateClipBox4MeshInstance** **(** :ref:`MeshInstance<class_MeshInstance>` meshins **)**

设置裁剪参数

----

.. _class_QueryServer_method_AddHitMeshInstance:

- :ref:`Void<class_Void>` **AddHitMeshInstance** **(** :ref:`ModelElement<class_ModelElement>` model, :ref:`MeshInstance<class_MeshInstance>` hitableMeshInstance, :ref:`Action`2<class_Action`2>` hitCallback **)**



----

.. _class_QueryServer_method_OnGeometryHit:

- :ref:`Void<class_Void>` **OnGeometryHit** **(** :ref:`UInt64<class_UInt64>` id, :ref:`Vector3<class_Vector3>` pos **)**



----

.. _class_QueryServer_method_OnElementHit:

- :ref:`Void<class_Void>` **OnElementHit** **(** :ref:`Feature<class_Feature>` feature **)**



----

.. _class_QueryServer_method_RayIntersectsTriangle:

- :ref:`Vector3<class_Vector3>` **RayIntersectsTriangle** **(** :ref:`UInt64<class_UInt64>` id, :ref:`Vector3<class_Vector3>` origin, :ref:`Vector3<class_Vector3>` hitpoint **)**



----

.. _class_QueryServer_method_GetCurrentPositionByMouse:

- :ref:`Vector3<class_Vector3>` **GetCurrentPositionByMouse** **(** :ref:`Boolean<class_Boolean>` needIntersectWithMesh **)**

获取当前鼠标的点

----

