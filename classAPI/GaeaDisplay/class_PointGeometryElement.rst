.. _class_PointGeometryElement:

PointGeometryElement 
===================

**Inherits:** :ref:`GeometryElement<class_GeometryElement>` **<** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

点Element

示例
----

属性
----

+-----------------+-----------------------------------------------+

方法
----

+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseDown<class_PointGeometryElement_method_OnMouseDown>` **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseUp<class_PointGeometryElement_method_OnMouseUp>` **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**     |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`OnMouseMove<class_PointGeometryElement_method_OnMouseMove>` **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)** |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`GetPointData<class_PointGeometryElement_method_GetPointData>` **(** **)**                                                                |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`_Notification<class_PointGeometryElement_method__Notification>` **(** :ref:`Int32<class_Int32>` what **)**                               |
+-------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------


方法说明
-------

.. _class_PointGeometryElement_method_OnMouseDown:

- :ref:`Boolean<class_Boolean>` **OnMouseDown** **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**

鼠标是否左击点中

----

.. _class_PointGeometryElement_method_OnMouseUp:

- :ref:`Boolean<class_Boolean>` **OnMouseUp** **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**

鼠标按键释放事件

----

.. _class_PointGeometryElement_method_OnMouseMove:

- :ref:`Boolean<class_Boolean>` **OnMouseMove** **(** :ref:`Vector2<class_Vector2>` pos, :ref:`Int32<class_Int32>` btn **)**

返回 false：表示地球也能移动，true：表示地球不可移动

----

.. _class_PointGeometryElement_method_GetPointData:

- :ref:`Vector3<class_Vector3>` **GetPointData** **(** **)**

获取点的坐标数据

----

.. _class_PointGeometryElement_method__Notification:

- :ref:`Void<class_Void>` **_Notification** **(** :ref:`Int32<class_Int32>` what **)**

QueueFree触发该信号

----

