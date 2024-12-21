.. _class_GeometryElementHelperPoint:

GeometryElementHelperPoint 
===================

**Inherits:** :ref:`GeometryElement<class_GeometryElement>` **<** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-------------------------------+---------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`VirtualHelperIcon<class_GeometryElementHelperPoint_property_VirtualHelperIcon>` |
+-------------------------------+---------------------------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`TakeOutLine<class_GeometryElementHelperPoint_property_TakeOutLine>`             |
+-------------------------------+---------------------------------------------------------------------------------------+

方法
----

+-------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`ClearCurrentHelperIcon<class_GeometryElementHelperPoint_method_ClearCurrentHelperIcon>` **(** **)**                        |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`HelperCallBack<class_GeometryElementHelperPoint_method_HelperCallBack>` **(** :ref:`Action`5<class_Action`5>` action **)** |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`ClearTakeOutSegment<class_GeometryElementHelperPoint_method_ClearTakeOutSegment>` **(** **)**                              |
+-------------------------+----------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_GeometryElementHelperPoint_property_VirtualHelperIcon:

- :ref:`Boolean<class_Boolean>` **VirtualHelperIcon**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否显示虚拟点，显示为true,默认为false

----

.. _class_GeometryElementHelperPoint_property_TakeOutLine:

- :ref:`Boolean<class_Boolean>` **TakeOutLine**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

提取出边界线

----


方法说明
-------

.. _class_GeometryElementHelperPoint_method_ClearCurrentHelperIcon:

- :ref:`Void<class_Void>` **ClearCurrentHelperIcon** **(** **)**

删除几何中被选中的点

----

.. _class_GeometryElementHelperPoint_method_HelperCallBack:

- :ref:`Void<class_Void>` **HelperCallBack** **(** :ref:`Action`5<class_Action`5>` action **)**

辅助点回调，将创建的辅助点点通过回调函数传递出来
<param name="action">回调函数</param>

----

.. _class_GeometryElementHelperPoint_method_ClearTakeOutSegment:

- :ref:`Void<class_Void>` **ClearTakeOutSegment** **(** **)**

清除选中线、多边形中的线段，使用完此方法后用户需要自行打开显示边线

----

