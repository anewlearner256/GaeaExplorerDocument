.. _class_GeometryElement:

GeometryElement 
===================

**Inherits:** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

几何Element

示例
----

属性
----

+---------------------------------+------------------------------------------------------------------------------------+
| :ref:`Feature<class_Feature>`   | :ref:`Feature<class_GeometryElement_property_Feature>`                             |
+---------------------------------+------------------------------------------------------------------------------------+
| :ref:`Symbol<class_Symbol>`     | :ref:`Symbol<class_GeometryElement_property_Symbol>`                               |
+---------------------------------+------------------------------------------------------------------------------------+
| :ref:`Geometry<class_Geometry>` | :ref:`Shape<class_GeometryElement_property_Shape>`                                 |
+---------------------------------+------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`   | :ref:`EnableEdit<class_GeometryElement_property_EnableEdit>`                       |
+---------------------------------+------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`   | :ref:`NeedIntersectWithMesh<class_GeometryElement_property_NeedIntersectWithMesh>` |
+---------------------------------+------------------------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`       | :ref:`PixelsThresholds<class_GeometryElement_property_PixelsThresholds>`           |
+---------------------------------+------------------------------------------------------------------------------------+

方法
----

+-------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Deselected<class_GeometryElement_method_Deselected>` **(** **)**                                                           |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`SetNeedUpdate<class_GeometryElement_method_SetNeedUpdate>` **(** **)**                                                     |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`OnDelete<class_GeometryElement_method_OnDelete>` **(** **)**                                                               |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`PullBoxSelection<class_GeometryElement_method_PullBoxSelection>` **(** :ref:`Vector3[]<class_Vector3[]>` polygonData **)** |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_GeometryElement_property_Feature:

- :ref:`Feature<class_Feature>` **Feature**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

GeometryElement包含的要素

----

.. _class_GeometryElement_property_Symbol:

- :ref:`Symbol<class_Symbol>` **Symbol**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

样式

----

.. _class_GeometryElement_property_Shape:

- :ref:`Geometry<class_Geometry>` **Shape**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

几何包含得Shape

----

.. _class_GeometryElement_property_EnableEdit:

- :ref:`Boolean<class_Boolean>` **EnableEdit**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

能否编辑

----

.. _class_GeometryElement_property_NeedIntersectWithMesh:

- :ref:`Boolean<class_Boolean>` **NeedIntersectWithMesh**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否与其他网格交互，默认为false

----

.. _class_GeometryElement_property_PixelsThresholds:

- :ref:`Int32<class_Int32>` **PixelsThresholds**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

点击事件的像素阈值

----


方法说明
-------

.. _class_GeometryElement_method_Deselected:

- :ref:`Void<class_Void>` **Deselected** **(** **)**

开放接口取消当前被选中的Element

----

.. _class_GeometryElement_method_SetNeedUpdate:

- :ref:`Void<class_Void>` **SetNeedUpdate** **(** **)**

改变相关属性之后，需要调用该函数进行更新

----

.. _class_GeometryElement_method_OnDelete:

- :ref:`Void<class_Void>` **OnDelete** **(** **)**

对多边形进行选中删除

----

.. _class_GeometryElement_method_PullBoxSelection:

- :ref:`Void<class_Void>` **PullBoxSelection** **(** :ref:`Vector3[]<class_Vector3[]>` polygonData **)**

框选 geometry

----

