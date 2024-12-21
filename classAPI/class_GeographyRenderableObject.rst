.. _class_GeographyRenderableObject:

GeographyRenderableObject 
===================

**Inherits:** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

地理渲染对象

示例
----

属性
----

+-------------------------------+--------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`UseAbsoluteHeight<class_GeographyRenderableObject_property_UseAbsoluteHeight>` |
+-------------------------------+--------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`Scale<class_GeographyRenderableObject_property_Scale>`                         |
+-------------------------------+--------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`GeographyPosition<class_GeographyRenderableObject_property_GeographyPosition>` |
+-------------------------------+--------------------------------------------------------------------------------------+

方法
----

+-------------------------+------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`ForceUpdateTransform<class_GeographyRenderableObject_method_ForceUpdateTransform>` **(** **)** |
+-------------------------+------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Update<class_GeographyRenderableObject_method_Update>` **(** **)**                             |
+-------------------------+------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_GeographyRenderableObject_property_UseAbsoluteHeight:

- :ref:`Boolean<class_Boolean>` **UseAbsoluteHeight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否使用绝对高度

----

.. _class_GeographyRenderableObject_property_Scale:

- :ref:`Vector3<class_Vector3>` **Scale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

对象的缩放系数

----

.. _class_GeographyRenderableObject_property_GeographyPosition:

- :ref:`Vector3<class_Vector3>` **GeographyPosition**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

对象的地理坐标 x纬度，y经度， z高度

----


方法说明
-------

.. _class_GeographyRenderableObject_method_ForceUpdateTransform:

- :ref:`Void<class_Void>` **ForceUpdateTransform** **(** **)**

及时更新地理坐标

----

.. _class_GeographyRenderableObject_method_Update:

- :ref:`Void<class_Void>` **Update** **(** **)**

当渲染对象发生变化时进行更新

----

