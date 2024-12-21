.. _class_DigTool:

DigTool 
===================

**Inherits:** :ref:`DrawPolygonTool<class_DrawPolygonTool>` **<** :ref:`BaseTool<class_BaseTool>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

描述
----

挖方工具

示例
----

属性
----

+---------------------------------+--------------------------------------------------------------------+
| :ref:`Double<class_Double>`     | :ref:`HoleDepth<class_DigTool_property_HoleDepth>`                 |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Single<class_Single>`     | :ref:`MeterOfUV<class_DigTool_property_MeterOfUV>`                 |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`   | :ref:`NeedNormalTexture<class_DigTool_property_NeedNormalTexture>` |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`HoleItem<class_HoleItem>` | :ref:`HoleItem<class_DigTool_property_HoleItem>`                   |
+---------------------------------+--------------------------------------------------------------------+

方法
----

+-------------------------+--------------------------------------------------------+
| :ref:`Void<class_Void>` | :ref:`_Ready<class_DigTool_method__Ready>` **(** **)** |
+-------------------------+--------------------------------------------------------+

属性说明
-------

.. _class_DigTool_property_HoleDepth:

- :ref:`Double<class_Double>` **HoleDepth**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

挖方深度，默认为100

----

.. _class_DigTool_property_MeterOfUV:

- :ref:`Single<class_Single>` **MeterOfUV**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

多少米重复一次贴图

----

.. _class_DigTool_property_NeedNormalTexture:

- :ref:`Boolean<class_Boolean>` **NeedNormalTexture**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否加载法线贴图

----

.. _class_DigTool_property_HoleItem:

- :ref:`HoleItem<class_HoleItem>` **HoleItem**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

未知

----


方法说明
-------

.. _class_DigTool_method__Ready:

- :ref:`Void<class_Void>` **_Ready** **(** **)**

对象被添加到场景中时执行一些初始化操作

----

