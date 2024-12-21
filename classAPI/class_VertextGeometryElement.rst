.. _class_VertextGeometryElement:

VertextGeometryElement 
===================

**Inherits:** :ref:`ModelElement<class_ModelElement>` **<** :ref:`Geography3DRenderableObject<class_Geography3DRenderableObject>` **<** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

三角索引Element

示例
----

属性
----

+-----------------------------------------------------------------------------------+-------------------------------------------------------------------------------------+
| :ref:`VertextGeometryElementDisplayType<class_VertextGeometryElementDisplayType>` | :ref:`DisplayType<class_VertextGeometryElement_property_DisplayType>`               |
+-----------------------------------------------------------------------------------+-------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                                                     | :ref:`NeedCalcNormal<class_VertextGeometryElement_property_NeedCalcNormal>`         |
+-----------------------------------------------------------------------------------+-------------------------------------------------------------------------------------+
| :ref:`VertextType<class_VertextType>`                                             | :ref:`VertextCoordinates<class_VertextGeometryElement_property_VertextCoordinates>` |
+-----------------------------------------------------------------------------------+-------------------------------------------------------------------------------------+

方法
----

+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`ParseJsonToObject<class_VertextGeometryElement_method_ParseJsonToObject>` **(** :ref:`String<class_String>` JsonContent **)**                                                        |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`CalcUV<class_VertextGeometryElement_method_CalcUV>` **(** :ref:`Vector2<class_Vector2>` uvScale, :ref:`Single<class_Single>` unitScale, :ref:`Boolean<class_Boolean>` UVRepeat **)** |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`Commit<class_VertextGeometryElement_method_Commit>` **(** **)**                                                                                                                      |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`Begin<class_VertextGeometryElement_method_Begin>` **(** **)**                                                                                                                        |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`AddVertex<class_VertextGeometryElement_method_AddVertex>` **(** :ref:`Vector3<class_Vector3>` vertex **)**                                                                           |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`       | :ref:`AddIndex<class_VertextGeometryElement_method_AddIndex>` **(** :ref:`Int32<class_Int32>` idx **)**                                                                                    |
+-------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_VertextGeometryElement_property_DisplayType:

- :ref:`VertextGeometryElementDisplayType<class_VertextGeometryElementDisplayType>` **DisplayType**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

顶点显示模式，默认为以线的方式显示

----

.. _class_VertextGeometryElement_property_NeedCalcNormal:

- :ref:`Boolean<class_Boolean>` **NeedCalcNormal**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否需要程序计算法线，默认为false

----

.. _class_VertextGeometryElement_property_VertextCoordinates:

- :ref:`VertextType<class_VertextType>` **VertextCoordinates**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

顶点模式，经纬度或者相对模式，默认是经纬度

----


方法说明
-------

.. _class_VertextGeometryElement_method_ParseJsonToObject:

- :ref:`Boolean<class_Boolean>` **ParseJsonToObject** **(** :ref:`String<class_String>` JsonContent **)**

解析Json文本是否成功

----

.. _class_VertextGeometryElement_method_CalcUV:

- :ref:`Void<class_Void>` **CalcUV** **(** :ref:`Vector2<class_Vector2>` uvScale, :ref:`Single<class_Single>` unitScale, :ref:`Boolean<class_Boolean>` UVRepeat **)**

使用QuadMode的方式计算UV （该方法的调用需要在Commit()之前，在Line模型中不起作用）

----

.. _class_VertextGeometryElement_method_Commit:

- :ref:`Void<class_Void>` **Commit** **(** **)**

构建Mesh

----

.. _class_VertextGeometryElement_method_Begin:

- :ref:`Void<class_Void>` **Begin** **(** **)**

初始化

----

.. _class_VertextGeometryElement_method_AddVertex:

- :ref:`Void<class_Void>` **AddVertex** **(** :ref:`Vector3<class_Vector3>` vertex **)**

添加顶点，顶点数据为经纬度加地形高度

----

.. _class_VertextGeometryElement_method_AddIndex:

- :ref:`Void<class_Void>` **AddIndex** **(** :ref:`Int32<class_Int32>` idx **)**

添加索引

----

