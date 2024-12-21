.. _class_HoleItem:

HoleItem 
===================

**Inherits:** :ref:`PolygonGeometryElement<class_PolygonGeometryElement>` **<** :ref:`GeometryElementHelperPoint<class_GeometryElementHelperPoint>` **<** :ref:`GeometryElement<class_GeometryElement>` **<** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+-------------------------------------------------------------+
| :ref:`Double<class_Double>`   | :ref:`HoleDepth<class_HoleItem_property_HoleDepth>`         |
+-------------------------------+-------------------------------------------------------------+
| :ref:`Texture<class_Texture>` | :ref:`SideTex<class_HoleItem_property_SideTex>`             |
+-------------------------------+-------------------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`MeterOfUV<class_HoleItem_property_MeterOfUV>`         |
+-------------------------------+-------------------------------------------------------------+
| :ref:`Texture<class_Texture>` | :ref:`BottomTex<class_HoleItem_property_BottomTex>`         |
+-------------------------------+-------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>` | :ref:`SideTexScale<class_HoleItem_property_SideTexScale>`   |
+-------------------------------+-------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`SideTexPath<class_HoleItem_property_SideTexPath>`     |
+-------------------------------+-------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`BottomTexPath<class_HoleItem_property_BottomTexPath>` |
+-------------------------------+-------------------------------------------------------------+

方法
----

+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`ChangeRange<class_HoleItem_method_ChangeRange>` **(** :ref:`Vector3[]<class_Vector3[]>` poly **)**                                                                                                              |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Generate<class_HoleItem_method_Generate>` **(** :ref:`Vector3[]<class_Vector3[]>` polygon, :ref:`Double<class_Double>` depth **)**                                                                              |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Generate<class_HoleItem_method_Generate>` **(** :ref:`Vector3[]<class_Vector3[]>` polygon, :ref:`Double<class_Double>` depth, :ref:`Single<class_Single>` distance, :ref:`Single<class_Single>` meterOfUV **)** |
+-------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_HoleItem_property_HoleDepth:

- :ref:`Double<class_Double>` **HoleDepth**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_HoleItem_property_SideTex:

- :ref:`Texture<class_Texture>` **SideTex**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_HoleItem_property_MeterOfUV:

- :ref:`Single<class_Single>` **MeterOfUV**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

多少米重复一次贴图

----

.. _class_HoleItem_property_BottomTex:

- :ref:`Texture<class_Texture>` **BottomTex**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_HoleItem_property_SideTexScale:

- :ref:`Vector2<class_Vector2>` **SideTexScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_HoleItem_property_SideTexPath:

- :ref:`String<class_String>` **SideTexPath**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----

.. _class_HoleItem_property_BottomTexPath:

- :ref:`String<class_String>` **BottomTexPath**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_HoleItem_method_ChangeRange:

- :ref:`Void<class_Void>` **ChangeRange** **(** :ref:`Vector3[]<class_Vector3[]>` poly **)**



----

.. _class_HoleItem_method_Generate:

- :ref:`Void<class_Void>` **Generate** **(** :ref:`Vector3[]<class_Vector3[]>` polygon, :ref:`Double<class_Double>` depth **)**



----

.. _class_HoleItem_method_Generate:

- :ref:`Void<class_Void>` **Generate** **(** :ref:`Vector3[]<class_Vector3[]>` polygon, :ref:`Double<class_Double>` depth, :ref:`Single<class_Single>` distance, :ref:`Single<class_Single>` meterOfUV **)**



----

