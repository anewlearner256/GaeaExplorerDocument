.. _class_Curve:

Curve 
===================

**Inherits:** :ref:`Reference<class_Reference>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------------------------+--------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`LengthAfterInterpolation<class_Curve_property_LengthAfterInterpolation>` |
+-----------------------------------+--------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`         | :ref:`Step<class_Curve_property_Step>`                                         |
+-----------------------------------+--------------------------------------------------------------------------------+
| :ref:`Vector3[]<class_Vector3[]>` | :ref:`InterpolationPoint<class_Curve_property_InterpolationPoint>`             |
+-----------------------------------+--------------------------------------------------------------------------------+
| :ref:`Quat[]<class_Quat[]>`       | :ref:`InterpolationRotation<class_Curve_property_InterpolationRotation>`       |
+-----------------------------------+--------------------------------------------------------------------------------+
| :ref:`Double[]<class_Double[]>`   | :ref:`DistanceToStartPoint<class_Curve_property_DistanceToStartPoint>`         |
+-----------------------------------+--------------------------------------------------------------------------------+
| :ref:`Double[]<class_Double[]>`   | :ref:`InterpolationTime<class_Curve_property_InterpolationTime>`               |
+-----------------------------------+--------------------------------------------------------------------------------+

方法
----

+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`         | :ref:`AddValue<class_Curve_method_AddValue>` **(** :ref:`Double<class_Double>` time, :ref:`Vector3<class_Vector3>` value **)**                                                                                                       |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`RemoveValue<class_Curve_method_RemoveValue>` **(** :ref:`Int32<class_Int32>` index **)**                                                                                                                                       |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`Clear<class_Curve_method_Clear>` **(** **)**                                                                                                                                                                                   |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`CalculateValueByTime<class_Curve_method_CalculateValueByTime>` **(** :ref:`Double<class_Double>` time **)**                                                                                                                    |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Quat<class_Quat>`           | :ref:`CalculateRotationByTime<class_Curve_method_CalculateRotationByTime>` **(** :ref:`Double<class_Double>` time, :ref:`Boolean<class_Boolean>` isParalleledToSurface **)**                                                         |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`Interpolate<class_Curve_method_Interpolate>` **(** :ref:`Boolean<class_Boolean>` isParalleledToSurface **)**                                                                                                                   |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`CalculateLengthAfterInterpolation<class_Curve_method_CalculateLengthAfterInterpolation>` **(** **)**                                                                                                                           |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`GetCurrentFirstDerivative<class_Curve_method_GetCurrentFirstDerivative>` **(** :ref:`Double<class_Double>` time **)**                                                                                                          |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`GetLenth<class_Curve_method_GetLenth>` **(** **)**                                                                                                                                                                             |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Animation<class_Animation>` | :ref:`ToAnimationBySpeed<class_Curve_method_ToAnimationBySpeed>` **(** :ref:`String<class_String>` animationName, :ref:`Single<class_Single>` speed, :ref:`Vector3<class_Vector3>` scale **)**                                       |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Animation<class_Animation>` | :ref:`ToAnimationByTime<class_Curve_method_ToAnimationByTime>` **(** :ref:`String<class_String>` animationName, :ref:`Boolean<class_Boolean>` isAverage, :ref:`Single<class_Single>` time, :ref:`Vector3<class_Vector3>` scale **)** |
+-----------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Curve_property_LengthAfterInterpolation:

- :ref:`Double<class_Double>` **LengthAfterInterpolation**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

插值后的长度

----

.. _class_Curve_property_Step:

- :ref:`Int32<class_Int32>` **Step**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

插值的步数

----

.. _class_Curve_property_InterpolationPoint:

- :ref:`Vector3[]<class_Vector3[]>` **InterpolationPoint**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

记录插值点

----

.. _class_Curve_property_InterpolationRotation:

- :ref:`Quat[]<class_Quat[]>` **InterpolationRotation**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

记录每个插值点的旋转

----

.. _class_Curve_property_DistanceToStartPoint:

- :ref:`Double[]<class_Double[]>` **DistanceToStartPoint**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

记录每个插值点到起点的距离

----

.. _class_Curve_property_InterpolationTime:

- :ref:`Double[]<class_Double[]>` **InterpolationTime**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

记录每个插值点的时间

----


方法说明
-------

.. _class_Curve_method_AddValue:

- :ref:`Int32<class_Int32>` **AddValue** **(** :ref:`Double<class_Double>` time, :ref:`Vector3<class_Vector3>` value **)**



----

.. _class_Curve_method_RemoveValue:

- :ref:`Void<class_Void>` **RemoveValue** **(** :ref:`Int32<class_Int32>` index **)**



----

.. _class_Curve_method_Clear:

- :ref:`Void<class_Void>` **Clear** **(** **)**



----

.. _class_Curve_method_CalculateValueByTime:

- :ref:`Vector3<class_Vector3>` **CalculateValueByTime** **(** :ref:`Double<class_Double>` time **)**



----

.. _class_Curve_method_CalculateRotationByTime:

- :ref:`Quat<class_Quat>` **CalculateRotationByTime** **(** :ref:`Double<class_Double>` time, :ref:`Boolean<class_Boolean>` isParalleledToSurface **)**

计算曲线上某一点的方向相对于平行地表/射线的旋转

----

.. _class_Curve_method_Interpolate:

- :ref:`Void<class_Void>` **Interpolate** **(** :ref:`Boolean<class_Boolean>` isParalleledToSurface **)**

对控制点进行插值，保存每个插值点的坐标，旋转和时间

----

.. _class_Curve_method_CalculateLengthAfterInterpolation:

- :ref:`Void<class_Void>` **CalculateLengthAfterInterpolation** **(** **)**

计算插值后的长度，并记录每个插值点到到起点的距离

----

.. _class_Curve_method_GetCurrentFirstDerivative:

- :ref:`Vector3<class_Vector3>` **GetCurrentFirstDerivative** **(** :ref:`Double<class_Double>` time **)**



----

.. _class_Curve_method_GetLenth:

- :ref:`Double<class_Double>` **GetLenth** **(** **)**



----

.. _class_Curve_method_ToAnimationBySpeed:

- :ref:`Animation<class_Animation>` **ToAnimationBySpeed** **(** :ref:`String<class_String>` animationName, :ref:`Single<class_Single>` speed, :ref:`Vector3<class_Vector3>` scale **)**

以插值点作为关键帧生成动画，关键帧的时刻由插值点到起点的路程和给定的速度确定

----

.. _class_Curve_method_ToAnimationByTime:

- :ref:`Animation<class_Animation>` **ToAnimationByTime** **(** :ref:`String<class_String>` animationName, :ref:`Boolean<class_Boolean>` isAverage, :ref:`Single<class_Single>` time, :ref:`Vector3<class_Vector3>` scale **)**

以插值点作为关键帧生成动画，关键帧的时刻由插值点到起点的路程占曲线总长的比例和给定的时间确定
如果isAverage为false,关键帧的时刻采用插值点的时刻

----

