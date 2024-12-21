.. _class_GLTFElement:

GLTFElement 
===================

**Inherits:** :ref:`ModelElement<class_ModelElement>` **<** :ref:`Geography3DRenderableObject<class_Geography3DRenderableObject>` **<** :ref:`GeographyRenderableObject<class_GeographyRenderableObject>` **<** :ref:`RenderableObject<class_RenderableObject>` **<** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

GLTF要素

示例
----

属性
----

+-------------------------------+--------------------------------------------------------------+
| :ref:`String<class_String>`   | :ref:`ResourceName<class_GLTFElement_property_ResourceName>` |
+-------------------------------+--------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>` | :ref:`UseLight<class_GLTFElement_property_UseLight>`         |
+-------------------------------+--------------------------------------------------------------+

方法
----

+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Initialize<class_GLTFElement_method_Initialize>` **(** **)**                                                                                                                                                                                                                                                      |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`ModelPop<class_GLTFElement_method_ModelPop>` **(** :ref:`Int32<class_Int32>` index, :ref:`Vector3<class_Vector3>` final_val, :ref:`Single<class_Single>` duration, :ref:`TransitionType<class_TransitionType>` trans_type, :ref:`EaseType<class_EaseType>` ease_type, :ref:`Action<class_Action>` completed **)** |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`Delete<class_GLTFElement_method_Delete>` **(** **)**                                                                                                                                                                                                                                                              |
+-------------------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_GLTFElement_property_ResourceName:

- :ref:`String<class_String>` **ResourceName**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

资源名称

----

.. _class_GLTFElement_property_UseLight:

- :ref:`Boolean<class_Boolean>` **UseLight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+



----


方法说明
-------

.. _class_GLTFElement_method_Initialize:

- :ref:`Void<class_Void>` **Initialize** **(** **)**

初始化

----

.. _class_GLTFElement_method_ModelPop:

- :ref:`Void<class_Void>` **ModelPop** **(** :ref:`Int32<class_Int32>` index, :ref:`Vector3<class_Vector3>` final_val, :ref:`Single<class_Single>` duration, :ref:`TransitionType<class_TransitionType>` trans_type, :ref:`EaseType<class_EaseType>` ease_type, :ref:`Action<class_Action>` completed **)**

未知

----

.. _class_GLTFElement_method_Delete:

- :ref:`Void<class_Void>` **Delete** **(** **)**

清除当前的GLTF模型

----

