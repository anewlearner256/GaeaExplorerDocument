.. _class_ModelElement:

ModelElement 
===================

**Inherits:** :ref:`Geography3DRenderableObject<class_Geography3DRenderableObject>` **<** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

模型要素

示例
----

属性
----

+-------------------------------+-----------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`EnablePick<class_ModelElement_property_EnablePick>` |
+-------------------------------+-----------------------------------------------------------+
| :ref:`Spatial<class_Spatial>` | :ref:`Root<class_ModelElement_property_Root>`             |
+-------------------------------+-----------------------------------------------------------+
| :ref:`Mesh<class_Mesh>`       | :ref:`Mesh<class_ModelElement_property_Mesh>`             |
+-------------------------------+-----------------------------------------------------------+

方法
----

+-----------------------------------------+---------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                 | :ref:`Delete<class_ModelElement_method_Delete>` **(** **)**                                                                     |
+-----------------------------------------+---------------------------------------------------------------------------------------------------------------------------------+
| :ref:`MeshInstance<class_MeshInstance>` | :ref:`GetMeshInstanceByName<class_ModelElement_method_GetMeshInstanceByName>` **(** :ref:`String<class_String>` name **)**      |
+-----------------------------------------+---------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                 | :ref:`SetDisplayViewport<class_ModelElement_method_SetDisplayViewport>` **(** :ref:`UInt32<class_UInt32>` displayViewport **)** |
+-----------------------------------------+---------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_ModelElement_property_EnablePick:

- :ref:`Boolean<class_Boolean>` **EnablePick**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

模型是否能点击，默认为false

----

.. _class_ModelElement_property_Root:

- :ref:`Spatial<class_Spatial>` **Root**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

模型所挂载的节点

----

.. _class_ModelElement_property_Mesh:

- :ref:`Mesh<class_Mesh>` **Mesh**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

模型所在的网格

----


方法说明
-------

.. _class_ModelElement_method_Delete:

- :ref:`Void<class_Void>` **Delete** **(** **)**

删除当前的模型

----

.. _class_ModelElement_method_GetMeshInstanceByName:

- :ref:`MeshInstance<class_MeshInstance>` **GetMeshInstanceByName** **(** :ref:`String<class_String>` name **)**

通过名字获取MeshInstance

----

.. _class_ModelElement_method_SetDisplayViewport:

- :ref:`Void<class_Void>` **SetDisplayViewport** **(** :ref:`UInt32<class_UInt32>` displayViewport **)**



----

