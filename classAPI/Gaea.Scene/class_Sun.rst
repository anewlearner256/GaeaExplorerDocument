.. _class_Sun:

Sun 
===================

**Inherits:** :ref:`DirectionalLight<class_DirectionalLight>` **<** :ref:`Light<class_Light>` **<** :ref:`VisualInstance<class_VisualInstance>` **<** :ref:`CullInstance<class_CullInstance>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

定义太阳节点

示例
----

属性
----

+-------------------------------+------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`IsSettingByUser<class_Sun_property_IsSettingByUser>`             |
+-------------------------------+------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`TimeScale<class_Sun_property_TimeScale>`                         |
+-------------------------------+------------------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`TimeString<class_Sun_property_TimeString>`                       |
+-------------------------------+------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`IsOn<class_Sun_property_IsOn>`                                   |
+-------------------------------+------------------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`Power<class_Sun_property_Power>`                                 |
+-------------------------------+------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`Shadow<class_Sun_property_Shadow>`                               |
+-------------------------------+------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`UseAutoShadowDistance<class_Sun_property_UseAutoShadowDistance>` |
+-------------------------------+------------------------------------------------------------------------+

方法
----

+-------------------------------+------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Ready<class_Sun_method__Ready>` **(** **)**                                                                           |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_PhysicsProcess<class_Sun_method__PhysicsProcess>` **(** :ref:`Single<class_Single>` delta **)**                       |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`GetGeocentricPosition<class_Sun_method_GetGeocentricPosition>` **(** :ref:`DateTime<class_DateTime>` utcDateTime **)** |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Sun_property_IsSettingByUser:

- :ref:`Boolean<class_Boolean>` **IsSettingByUser**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

为true时，时间由用户手动设置，否则自动获取系统时间

----

.. _class_Sun_property_TimeScale:

- :ref:`Single<class_Single>` **TimeScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

时间流逝速率

----

.. _class_Sun_property_TimeString:

- :ref:`String<class_String>` **TimeString**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

时间，格式yyyy-MM-dd HH:mm:ss

----

.. _class_Sun_property_IsOn:

- :ref:`Boolean<class_Boolean>` **IsOn**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

为true时，时间会流逝，否则时间不变

----

.. _class_Sun_property_Power:

- :ref:`Single<class_Single>` **Power**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

光的强度

----

.. _class_Sun_property_Shadow:

- :ref:`Boolean<class_Boolean>` **Shadow**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否开启阴影

----

.. _class_Sun_property_UseAutoShadowDistance:

- :ref:`Boolean<class_Boolean>` **UseAutoShadowDistance**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

使用自动阴影距离,用于解决阴影的锯齿以及条纹问题

----


方法说明
-------

.. _class_Sun_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**



----

.. _class_Sun_method__PhysicsProcess:

- :ref:`Void<class_Void>` **_PhysicsProcess** **(** :ref:`Single<class_Single>` delta **)**



----

.. _class_Sun_method_GetGeocentricPosition:

- :ref:`Vector3<class_Vector3>` **GetGeocentricPosition** **(** :ref:`DateTime<class_DateTime>` utcDateTime **)**

计算出某个时刻的太阳位置（笛卡尔坐标）

----

