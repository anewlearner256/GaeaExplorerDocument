.. _class_WorldCamera:

WorldCamera 
===================

**Inherits:** :ref:`CameraBase<class_CameraBase>` **<** :ref:`Camera<class_Camera>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`               | :ref:`SlerpPercent<class_WorldCamera_property_SlerpPercent>`                                     |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`GEAngle<class_GEAngle>`             | :ref:`Heading<class_WorldCamera_property_Heading>`                                               |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`             | :ref:`UseUniformLinearInterpolation<class_WorldCamera_property_UseUniformLinearInterpolation>`   |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`Single<class_Single>`               | :ref:`UniformLinearInterpolationTime<class_WorldCamera_property_UniformLinearInterpolationTime>` |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`               | :ref:`TargetAltitude<class_WorldCamera_property_TargetAltitude>`                                 |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`GEAngle<class_GEAngle>`             | :ref:`TargetHeading<class_WorldCamera_property_TargetHeading>`                                   |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`GEAngle<class_GEAngle>`             | :ref:`TargetLatitude<class_WorldCamera_property_TargetLatitude>`                                 |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`GEAngle<class_GEAngle>`             | :ref:`TargetLongitude<class_WorldCamera_property_TargetLongitude>`                               |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`GEQuaternionD<class_GEQuaternionD>` | :ref:`TargetOrientation<class_WorldCamera_property_TargetOrientation>`                           |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`GEAngle<class_GEAngle>`             | :ref:`FovGEAngle<class_WorldCamera_property_FovGEAngle>`                                         |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`GEAngle<class_GEAngle>`             | :ref:`Bank<class_WorldCamera_property_Bank>`                                                     |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`GEAngle<class_GEAngle>`             | :ref:`Tilt<class_WorldCamera_property_Tilt>`                                                     |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`               | :ref:`TargetDistance<class_WorldCamera_property_TargetDistance>`                                 |
+-------------------------------------------+--------------------------------------------------------------------------------------------------+

方法
----

+-----------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`SetPosition<class_WorldCamera_method_SetPosition>` **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon, :ref:`Double<class_Double>` heading, :ref:`Double<class_Double>` altitude, :ref:`Double<class_Double>` tilt, :ref:`Double<class_Double>` bank **)** |
+-----------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`Update<class_WorldCamera_method_Update>` **(** :ref:`Single<class_Single>` deltaTime **)**                                                                                                                                                                                     |
+-----------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>` | :ref:`ToString<class_WorldCamera_method_ToString>` **(** **)**                                                                                                                                                                                                                       |
+-----------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`RotationYawPitchRoll<class_WorldCamera_method_RotationYawPitchRoll>` **(** :ref:`GEAngle<class_GEAngle>` yaw, :ref:`GEAngle<class_GEAngle>` pitch, :ref:`GEAngle<class_GEAngle>` roll **)**                                                                                    |
+-----------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`Zoom<class_WorldCamera_method_Zoom>` **(** :ref:`Single<class_Single>` percent **)**                                                                                                                                                                                           |
+-----------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`Zoomjs<class_WorldCamera_method_Zoomjs>` **(** :ref:`Single<class_Single>` percent **)**                                                                                                                                                                                       |
+-----------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`Pan<class_WorldCamera_method_Pan>` **(** :ref:`GEAngle<class_GEAngle>` lat, :ref:`GEAngle<class_GEAngle>` lon **)**                                                                                                                                                            |
+-----------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`     | :ref:`UpdateCameraAnimations<class_WorldCamera_method_UpdateCameraAnimations>` **(** :ref:`Single<class_Single>` d **)**                                                                                                                                                             |
+-----------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_WorldCamera_property_SlerpPercent:

- :ref:`Double<class_Double>` **SlerpPercent**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

Slerp百分比，控制飞行速度

----

.. _class_WorldCamera_property_Heading:

- :ref:`GEAngle<class_GEAngle>` **Heading**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

相机的偏北角

----

.. _class_WorldCamera_property_UseUniformLinearInterpolation:

- :ref:`Boolean<class_Boolean>` **UseUniformLinearInterpolation**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

飞行时使用均匀线性插值

----

.. _class_WorldCamera_property_UniformLinearInterpolationTime:

- :ref:`Single<class_Single>` **UniformLinearInterpolationTime**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

均匀线性插值时间

----

.. _class_WorldCamera_property_TargetAltitude:

- :ref:`Double<class_Double>` **TargetAltitude**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

相机移动的目标海拔高度（米）

----

.. _class_WorldCamera_property_TargetHeading:

- :ref:`GEAngle<class_GEAngle>` **TargetHeading**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

相机旋转后的目标偏北角

----

.. _class_WorldCamera_property_TargetLatitude:

- :ref:`GEAngle<class_GEAngle>` **TargetLatitude**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

相机移动后的目标纬度

----

.. _class_WorldCamera_property_TargetLongitude:

- :ref:`GEAngle<class_GEAngle>` **TargetLongitude**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

相机移动后的目标经度

----

.. _class_WorldCamera_property_TargetOrientation:

- :ref:`GEQuaternionD<class_GEQuaternionD>` **TargetOrientation**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

相机移动后的目标姿态，四元数形式

----

.. _class_WorldCamera_property_FovGEAngle:

- :ref:`GEAngle<class_GEAngle>` **FovGEAngle**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

相机的FOV

----

.. _class_WorldCamera_property_Bank:

- :ref:`GEAngle<class_GEAngle>` **Bank**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

相机的翻滚角

----

.. _class_WorldCamera_property_Tilt:

- :ref:`GEAngle<class_GEAngle>` **Tilt**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

相机的俯仰角

----

.. _class_WorldCamera_property_TargetDistance:

- :ref:`Double<class_Double>` **TargetDistance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

相机到观察点的目标距离

----


方法说明
-------

.. _class_WorldCamera_method_SetPosition:

- :ref:`Void<class_Void>` **SetPosition** **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon, :ref:`Double<class_Double>` heading, :ref:`Double<class_Double>` altitude, :ref:`Double<class_Double>` tilt, :ref:`Double<class_Double>` bank **)**

设置相机位置。

----

.. _class_WorldCamera_method_Update:

- :ref:`Void<class_Void>` **Update** **(** :ref:`Single<class_Single>` deltaTime **)**

逐帧更新状态

----

.. _class_WorldCamera_method_ToString:

- :ref:`String<class_String>` **ToString** **(** **)**

将相机参数格式化为字符串

----

.. _class_WorldCamera_method_RotationYawPitchRoll:

- :ref:`Void<class_Void>` **RotationYawPitchRoll** **(** :ref:`GEAngle<class_GEAngle>` yaw, :ref:`GEAngle<class_GEAngle>` pitch, :ref:`GEAngle<class_GEAngle>` roll **)**

调整相机姿态

----

.. _class_WorldCamera_method_Zoom:

- :ref:`Void<class_Void>` **Zoom** **(** :ref:`Single<class_Single>` percent **)**

摄像机变焦

----

.. _class_WorldCamera_method_Zoomjs:

- :ref:`Void<class_Void>` **Zoomjs** **(** :ref:`Single<class_Single>` percent **)**

摄像机变焦

----

.. _class_WorldCamera_method_Pan:

- :ref:`Void<class_Void>` **Pan** **(** :ref:`GEAngle<class_GEAngle>` lat, :ref:`GEAngle<class_GEAngle>` lon **)**

使用增量值平移相机

----

.. _class_WorldCamera_method_UpdateCameraAnimations:

- :ref:`Void<class_Void>` **UpdateCameraAnimations** **(** :ref:`Single<class_Single>` d **)**



----

