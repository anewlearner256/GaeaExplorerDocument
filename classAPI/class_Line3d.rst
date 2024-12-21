.. _class_Line3d:

Line3d 
===================

**Inherits:** :ref:`MeshInstance<class_MeshInstance>` **<** :ref:`GeometryInstance<class_GeometryInstance>` **<** :ref:`VisualInstance<class_VisualInstance>` **<** :ref:`CullInstance<class_CullInstance>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+---------------------------------------------------+
| :ref:`Single<class_Single>`   | :ref:`LineWidth<class_Line3d_property_LineWidth>` |
+-------------------------------+---------------------------------------------------+
| :ref:`Vector3<class_Vector3>` | :ref:`LineColor<class_Line3d_property_LineColor>` |
+-------------------------------+---------------------------------------------------+

方法
----

+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`_Ready<class_Line3d_method__Ready>` **(** **)**                                                                                                               |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`Init<class_Line3d_method_Init>` **(** :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Vector3<class_Vector3>` color, :ref:`Single<class_Single>` width **)** |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`SetLineWidth<class_Line3d_method_SetLineWidth>` **(** :ref:`Single<class_Single>` width **)**                                                                 |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`ArrayMesh<class_ArrayMesh>` | :ref:`CreateLineSingleMesh<class_Line3d_method_CreateLineSingleMesh>` **(** **)**                                                                                   |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`AddPoint<class_Line3d_method_AddPoint>` **(** :ref:`Vector3<class_Vector3>` point **)**                                                                       |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`           | :ref:`RemovePoint<class_Line3d_method_RemovePoint>` **(** :ref:`Int32<class_Int32>` index **)**                                                                     |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_Line3d_property_LineWidth:

- :ref:`Single<class_Single>` **LineWidth**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线的宽度

----

.. _class_Line3d_property_LineColor:

- :ref:`Vector3<class_Vector3>` **LineColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

线的颜色

----


方法说明
-------

.. _class_Line3d_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

当线进入场景树准备就绪后执行

----

.. _class_Line3d_method_Init:

- :ref:`Void<class_Void>` **Init** **(** :ref:`Vector3[]<class_Vector3[]>` vertexs, :ref:`Vector3<class_Vector3>` color, :ref:`Single<class_Single>` width **)**

初始化线参数

----

.. _class_Line3d_method_SetLineWidth:

- :ref:`Void<class_Void>` **SetLineWidth** **(** :ref:`Single<class_Single>` width **)**

设置线的宽度

----

.. _class_Line3d_method_CreateLineSingleMesh:

- :ref:`ArrayMesh<class_ArrayMesh>` **CreateLineSingleMesh** **(** **)**

构造宽度线的网格对象

----

.. _class_Line3d_method_AddPoint:

- :ref:`Void<class_Void>` **AddPoint** **(** :ref:`Vector3<class_Vector3>` point **)**

添加线顶点

----

.. _class_Line3d_method_RemovePoint:

- :ref:`Void<class_Void>` **RemovePoint** **(** :ref:`Int32<class_Int32>` index **)**

移除线顶点

----

