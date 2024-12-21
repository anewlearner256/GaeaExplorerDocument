.. _class_Geography3DRenderableObject:

Geography3DRenderableObject 
===================

**Inherits:** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

地理三维渲染对象

示例
----

属性
----

+-------------------------------+----------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`TiltHeadingBank<class_Geography3DRenderableObject_property_TiltHeadingBank>`                 |
+-------------------------------+----------------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`CaptureCameraInDistance<class_Geography3DRenderableObject_property_CaptureCameraInDistance>` |
+-------------------------------+----------------------------------------------------------------------------------------------------+

方法
----

+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnModelInit<class_Geography3DRenderableObject_method_OnModelInit>` **(** :ref:`Action<class_Action>` onhit **)**                     |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnCaptureCamera<class_Geography3DRenderableObject_method_OnCaptureCamera>` **(** :ref:`Action`1<class_Action`1>` captureCamera **)** |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Update<class_Geography3DRenderableObject_method_Update>` **(** **)**                                                                 |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnHitElement<class_Geography3DRenderableObject_method_OnHitElement>` **(** :ref:`Action`1<class_Action`1>` onhit **)**               |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnHitChildElement<class_Geography3DRenderableObject_method_OnHitChildElement>` **(** :ref:`Action`2<class_Action`2>` onhit **)**     |
+-------------------------+--------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Geography3DRenderableObject_property_TiltHeadingBank:

- :ref:`Vector3<class_Vector3>` **TiltHeadingBank**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

渲染对象的俯仰角，偏北角和翻滚角

----

.. _class_Geography3DRenderableObject_property_CaptureCameraInDistance:

- :ref:`Single<class_Single>` **CaptureCameraInDistance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

设置一个距离，当渲染对象到相机的距离小于此距离时，可执行一些额外操作

----


方法说明
-------

.. _class_Geography3DRenderableObject_method_OnModelInit:

- :ref:`Void<class_Void>` **OnModelInit** **(** :ref:`Action<class_Action>` onhit **)**

设置当渲染对象初始化完成时的回调事件

----

.. _class_Geography3DRenderableObject_method_OnCaptureCamera:

- :ref:`Void<class_Void>` **OnCaptureCamera** **(** :ref:`Action`1<class_Action`1>` captureCamera **)**

设置当相机到该可渲染对象的距离小于CaptureCameraInDistance时的回调事件

----

.. _class_Geography3DRenderableObject_method_Update:

- :ref:`Void<class_Void>` **Update** **(** **)**

更新可渲染对象

----

.. _class_Geography3DRenderableObject_method_OnHitElement:

- :ref:`Void<class_Void>` **OnHitElement** **(** :ref:`Action`1<class_Action`1>` onhit **)**

设置当渲染对象被点击时的回调事件

----

.. _class_Geography3DRenderableObject_method_OnHitChildElement:

- :ref:`Void<class_Void>` **OnHitChildElement** **(** :ref:`Action`2<class_Action`2>` onhit **)**

设置当可渲染对象的子对象被点击时的回调事件

----

