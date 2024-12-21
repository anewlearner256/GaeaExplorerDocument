.. _class_GaeaMath:

GaeaMath 
===================

**Inherits:** :ref:`Object<class_Object>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------+-----------------------------------+

方法
----

+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`Azimuth<class_GaeaMath_method_Azimuth>` **(** :ref:`Double<class_Double>` latA, :ref:`Double<class_Double>` lonA, :ref:`Double<class_Double>` latB, :ref:`Double<class_Double>` lonB **)**                                                                    |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Transform<class_Transform>` | :ref:`SphericalToGlobeTransform<class_GaeaMath_method_SphericalToGlobeTransform>` **(** :ref:`Vector3<class_Vector3>` latlonalt, :ref:`Boolean<class_Boolean>` useAbsoluteHeight **)**                                                                              |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`SphericalToGlobeRoationYZX<class_GaeaMath_method_SphericalToGlobeRoationYZX>` **(** :ref:`Vector3<class_Vector3>` latlonalt **)**                                                                                                                             |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`     | :ref:`IsEqualApprox<class_GaeaMath_method_IsEqualApprox>` **(** :ref:`Double<class_Double>` num1, :ref:`Double<class_Double>` num2, :ref:`Double<class_Double>` approx **)**                                                                                        |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Transform<class_Transform>` | :ref:`SphericalToGlobeTransform<class_GaeaMath_method_SphericalToGlobeTransform>` **(** :ref:`Vector3<class_Vector3>` latlonalt, :ref:`Vector3<class_Vector3>` rotation, :ref:`Vector3<class_Vector3>` scale, :ref:`Boolean<class_Boolean>` useAbsoluteHeight **)** |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Transform<class_Transform>` | :ref:`SphericalToGlobeTransform<class_GaeaMath_method_SphericalToGlobeTransform>` **(** :ref:`Vector3<class_Vector3>` latlonalt, :ref:`Vector3<class_Vector3>` rotation, :ref:`Vector3<class_Vector3>` scale **)**                                                  |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Transform<class_Transform>` | :ref:`SphericalToGlobeTransform<class_GaeaMath_method_SphericalToGlobeTransform>` **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon, :ref:`Boolean<class_Boolean>` useAbsoluteHeight **)**                                                     |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`SphericalToCartesianRad<class_GaeaMath_method_SphericalToCartesianRad>` **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude, :ref:`Double<class_Double>` radius **)**                                                           |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`SphericalToCartesianRad<class_GaeaMath_method_SphericalToCartesianRad>` **(** :ref:`Vector3<class_Vector3>` latlonalt **)**                                                                                                                                   |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`SphericalToCartesianDeg<class_GaeaMath_method_SphericalToCartesianDeg>` **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude, :ref:`Double<class_Double>` radius **)**                                                           |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`SphericalToCartesianDeg<class_GaeaMath_method_SphericalToCartesianDeg>` **(** :ref:`Vector3<class_Vector3>` latlonalt **)**                                                                                                                                   |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`CartesianToSphericalDeg<class_GaeaMath_method_CartesianToSphericalDeg>` **(** :ref:`Double<class_Double>` x, :ref:`Double<class_Double>` y, :ref:`Double<class_Double>` z **)**                                                                               |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`CartesianToSphericalDeg<class_GaeaMath_method_CartesianToSphericalDeg>` **(** :ref:`Vector3<class_Vector3>` cartesian **)**                                                                                                                                   |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`CartesianToSphericalRad<class_GaeaMath_method_CartesianToSphericalRad>` **(** :ref:`Vector3<class_Vector3>` cartesian **)**                                                                                                                                   |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`CartesianToSphericalRad<class_GaeaMath_method_CartesianToSphericalRad>` **(** :ref:`Double<class_Double>` x, :ref:`Double<class_Double>` y, :ref:`Double<class_Double>` z **)**                                                                               |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`ProjectLatlonPosition<class_GaeaMath_method_ProjectLatlonPosition>` **(** :ref:`Vector2<class_Vector2>` pos **)**                                                                                                                                             |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`ProjectPosition<class_GaeaMath_method_ProjectPosition>` **(** :ref:`Vector2<class_Vector2>` pos **)**                                                                                                                                                         |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`     | :ref:`ProjectLatlon<class_GaeaMath_method_ProjectLatlon>` **(** :ref:`Vector2<class_Vector2>` pos **)**                                                                                                                                                             |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`     | :ref:`UnProjectPosition<class_GaeaMath_method_UnProjectPosition>` **(** :ref:`Vector3<class_Vector3>` pos **)**                                                                                                                                                     |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Quat<class_Quat>`           | :ref:`RotationFromCartesianToSpherical<class_GaeaMath_method_RotationFromCartesianToSpherical>` **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon **)**                                                                                        |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`SurfaceTiltHeadingBank<class_GaeaMath_method_SurfaceTiltHeadingBank>` **(** :ref:`Transform<class_Transform>` transform **)**                                                                                                                                 |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Quat<class_Quat>`           | :ref:`RotationFromCartesianToSpherical1<class_GaeaMath_method_RotationFromCartesianToSpherical1>` **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon **)**                                                                                      |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Quat<class_Quat>`           | :ref:`RotationFromDirectionZAxisUp<class_GaeaMath_method_RotationFromDirectionZAxisUp>` **(** :ref:`Vector3<class_Vector3>` direction **)**                                                                                                                         |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`ToDouble<class_GaeaMath_method_ToDouble>` **(** :ref:`String<class_String>` str **)**                                                                                                                                                                         |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Plane<class_Plane>`         | :ref:`PlaneFromPointNormal<class_GaeaMath_method_PlaneFromPointNormal>` **(** :ref:`Vector3<class_Vector3>` point, :ref:`Vector3<class_Vector3>` normal **)**                                                                                                       |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`DistanceToPlane<class_GaeaMath_method_DistanceToPlane>` **(** :ref:`Plane<class_Plane>` plane, :ref:`Vector3<class_Vector3>` point **)**                                                                                                                      |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`NegativePiToPi<class_GaeaMath_method_NegativePiToPi>` **(** :ref:`Double<class_Double>` angle **)**                                                                                                                                                           |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`ZeroToTwoPi<class_GaeaMath_method_ZeroToTwoPi>` **(** :ref:`Double<class_Double>` angle **)**                                                                                                                                                                 |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Double<class_Double>`       | :ref:`Mod<class_GaeaMath_method_Mod>` **(** :ref:`Double<class_Double>` m, :ref:`Double<class_Double>` n **)**                                                                                                                                                      |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------


方法说明
-------

.. _class_GaeaMath_method_Azimuth:

- :ref:`Double<class_Double>` **Azimuth** **(** :ref:`Double<class_Double>` latA, :ref:`Double<class_Double>` lonA, :ref:`Double<class_Double>` latB, :ref:`Double<class_Double>` lonB **)**

计算地表上两点连线的偏北角

----

.. _class_GaeaMath_method_SphericalToGlobeTransform:

- :ref:`Transform<class_Transform>` **SphericalToGlobeTransform** **(** :ref:`Vector3<class_Vector3>` latlonalt, :ref:`Boolean<class_Boolean>` useAbsoluteHeight **)**

根据经纬度计算出模型的Transform，该transform会使模型垂直与地表

----

.. _class_GaeaMath_method_SphericalToGlobeRoationYZX:

- :ref:`Vector3<class_Vector3>` **SphericalToGlobeRoationYZX** **(** :ref:`Vector3<class_Vector3>` latlonalt **)**

根据经纬度计算出模型的垂直地表放置时欧拉角（YZX）

----

.. _class_GaeaMath_method_IsEqualApprox:

- :ref:`Boolean<class_Boolean>` **IsEqualApprox** **(** :ref:`Double<class_Double>` num1, :ref:`Double<class_Double>` num2, :ref:`Double<class_Double>` approx **)**

比较两个double类型的值是否近似相等

----

.. _class_GaeaMath_method_SphericalToGlobeTransform:

- :ref:`Transform<class_Transform>` **SphericalToGlobeTransform** **(** :ref:`Vector3<class_Vector3>` latlonalt, :ref:`Vector3<class_Vector3>` rotation, :ref:`Vector3<class_Vector3>` scale, :ref:`Boolean<class_Boolean>` useAbsoluteHeight **)**

根据经纬度, 旋转（ZXY欧拉角）， 缩放计算出模型的Transform

----

.. _class_GaeaMath_method_SphericalToGlobeTransform:

- :ref:`Transform<class_Transform>` **SphericalToGlobeTransform** **(** :ref:`Vector3<class_Vector3>` latlonalt, :ref:`Vector3<class_Vector3>` rotation, :ref:`Vector3<class_Vector3>` scale **)**

根据经纬度, 旋转（ZXY欧拉角）， 缩放计算出模型的Transform,考虑地形

----

.. _class_GaeaMath_method_SphericalToGlobeTransform:

- :ref:`Transform<class_Transform>` **SphericalToGlobeTransform** **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon, :ref:`Boolean<class_Boolean>` useAbsoluteHeight **)**

根据经纬度计算出模型的Transform,该transform会使模型垂直与地表,考虑地形

----

.. _class_GaeaMath_method_SphericalToCartesianRad:

- :ref:`Vector3<class_Vector3>` **SphericalToCartesianRad** **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude, :ref:`Double<class_Double>` radius **)**

地理坐标纬经度（弧度制）转为笛卡尔坐标

----

.. _class_GaeaMath_method_SphericalToCartesianRad:

- :ref:`Vector3<class_Vector3>` **SphericalToCartesianRad** **(** :ref:`Vector3<class_Vector3>` latlonalt **)**

地理坐标纬经度（弧度制）转为笛卡尔坐标(弧度)

----

.. _class_GaeaMath_method_SphericalToCartesianDeg:

- :ref:`Vector3<class_Vector3>` **SphericalToCartesianDeg** **(** :ref:`Double<class_Double>` latitude, :ref:`Double<class_Double>` longitude, :ref:`Double<class_Double>` radius **)**

纬经度（角度制）转笛卡尔坐标

----

.. _class_GaeaMath_method_SphericalToCartesianDeg:

- :ref:`Vector3<class_Vector3>` **SphericalToCartesianDeg** **(** :ref:`Vector3<class_Vector3>` latlonalt **)**

纬经度（角度制）转笛卡尔坐标

----

.. _class_GaeaMath_method_CartesianToSphericalDeg:

- :ref:`Vector3<class_Vector3>` **CartesianToSphericalDeg** **(** :ref:`Double<class_Double>` x, :ref:`Double<class_Double>` y, :ref:`Double<class_Double>` z **)**

笛卡尔坐标转纬经度（角度制）

----

.. _class_GaeaMath_method_CartesianToSphericalDeg:

- :ref:`Vector3<class_Vector3>` **CartesianToSphericalDeg** **(** :ref:`Vector3<class_Vector3>` cartesian **)**

笛卡尔坐标转纬经度（角度制）

----

.. _class_GaeaMath_method_CartesianToSphericalRad:

- :ref:`Vector3<class_Vector3>` **CartesianToSphericalRad** **(** :ref:`Vector3<class_Vector3>` cartesian **)**

笛卡尔坐标转纬经度(弧度制)

----

.. _class_GaeaMath_method_CartesianToSphericalRad:

- :ref:`Vector3<class_Vector3>` **CartesianToSphericalRad** **(** :ref:`Double<class_Double>` x, :ref:`Double<class_Double>` y, :ref:`Double<class_Double>` z **)**

笛卡尔坐标转纬经度(弧度制)

----

.. _class_GaeaMath_method_ProjectLatlonPosition:

- :ref:`Vector3<class_Vector3>` **ProjectLatlonPosition** **(** :ref:`Vector2<class_Vector2>` pos **)**

根据屏幕坐标计算对应点的纬度经度和高度（考虑地形）

----

.. _class_GaeaMath_method_ProjectPosition:

- :ref:`Vector3<class_Vector3>` **ProjectPosition** **(** :ref:`Vector2<class_Vector2>` pos **)**

根据屏幕坐标计算对应点的笛卡尔坐标（考虑地形）

----

.. _class_GaeaMath_method_ProjectLatlon:

- :ref:`Vector2<class_Vector2>` **ProjectLatlon** **(** :ref:`Vector2<class_Vector2>` pos **)**

根据屏幕坐标计算对应点的纬度经度

----

.. _class_GaeaMath_method_UnProjectPosition:

- :ref:`Vector2<class_Vector2>` **UnProjectPosition** **(** :ref:`Vector3<class_Vector3>` pos **)**

根据笛卡尔坐标计算屏幕坐标

----

.. _class_GaeaMath_method_RotationFromCartesianToSpherical:

- :ref:`Quat<class_Quat>` **RotationFromCartesianToSpherical** **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon **)**

根据经纬度计算该点的旋转，该旋转可使位于该点的物体的局部y轴垂直于地表

----

.. _class_GaeaMath_method_SurfaceTiltHeadingBank:

- :ref:`Vector3<class_Vector3>` **SurfaceTiltHeadingBank** **(** :ref:`Transform<class_Transform>` transform **)**

根据变换矩阵计算对应的姿态角（俯仰角，偏北角，翻滚角）

----

.. _class_GaeaMath_method_RotationFromCartesianToSpherical1:

- :ref:`Quat<class_Quat>` **RotationFromCartesianToSpherical1** **(** :ref:`Double<class_Double>` lat, :ref:`Double<class_Double>` lon **)**

根据经纬度计算旋转，该旋转可使位于该点的物体的局部y轴垂直于地表

----

.. _class_GaeaMath_method_RotationFromDirectionZAxisUp:

- :ref:`Quat<class_Quat>` **RotationFromDirectionZAxisUp** **(** :ref:`Vector3<class_Vector3>` direction **)**

计算从Z轴向上的方向旋转到给定方向所需的旋转

----

.. _class_GaeaMath_method_ToDouble:

- :ref:`Double<class_Double>` **ToDouble** **(** :ref:`String<class_String>` str **)**

string类型转为double

----

.. _class_GaeaMath_method_PlaneFromPointNormal:

- :ref:`Plane<class_Plane>` **PlaneFromPointNormal** **(** :ref:`Vector3<class_Vector3>` point, :ref:`Vector3<class_Vector3>` normal **)**



----

.. _class_GaeaMath_method_DistanceToPlane:

- :ref:`Double<class_Double>` **DistanceToPlane** **(** :ref:`Plane<class_Plane>` plane, :ref:`Vector3<class_Vector3>` point **)**



----

.. _class_GaeaMath_method_NegativePiToPi:

- :ref:`Double<class_Double>` **NegativePiToPi** **(** :ref:`Double<class_Double>` angle **)**



----

.. _class_GaeaMath_method_ZeroToTwoPi:

- :ref:`Double<class_Double>` **ZeroToTwoPi** **(** :ref:`Double<class_Double>` angle **)**



----

.. _class_GaeaMath_method_Mod:

- :ref:`Double<class_Double>` **Mod** **(** :ref:`Double<class_Double>` m, :ref:`Double<class_Double>` n **)**



----

