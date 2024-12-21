.. _class_BuildingSymbol:

BuildingSymbol 
===================

**Inherits:** :ref:`Symbol<class_Symbol>` **<** :ref:`Object<class_Object>`

描述
----

建筑体样式，继承自Symbol

示例
----

属性
----

+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                 | :ref:`IsNeedNormal<class_BuildingSymbol_property_IsNeedNormal>`   |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                 | :ref:`IsClose<class_BuildingSymbol_property_IsClose>`             |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`UnitScale<class_BuildingSymbol_property_UnitScale>`         |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                 | :ref:`UVRepeat<class_BuildingSymbol_property_UVRepeat>`           |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`                 | :ref:`UvScale<class_BuildingSymbol_property_UvScale>`             |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`                 | :ref:`ExtrudeDir<class_BuildingSymbol_property_ExtrudeDir>`       |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`String<class_String>`                   | :ref:`HeightField<class_BuildingSymbol_property_HeightField>`     |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`Int32<class_Int32>`                     | :ref:`HeightScale<class_BuildingSymbol_property_HeightScale>`     |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`Boolean<class_Boolean>`                 | :ref:`RandomHeight<class_BuildingSymbol_property_RandomHeight>`   |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`Single<class_Single>`                   | :ref:`ExtrudeHeight<class_BuildingSymbol_property_ExtrudeHeight>` |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`SpatialMaterial<class_SpatialMaterial>` | :ref:`WallMaterial<class_BuildingSymbol_property_WallMaterial>`   |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`SpatialMaterial<class_SpatialMaterial>` | :ref:`RoofMaterial<class_BuildingSymbol_property_RoofMaterial>`   |
+-----------------------------------------------+-------------------------------------------------------------------+
| :ref:`Color<class_Color>`                     | :ref:`SymbolColor<class_BuildingSymbol_property_SymbolColor>`     |
+-----------------------------------------------+-------------------------------------------------------------------+

方法
----

+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`DrawMesh<class_BuildingSymbol_method_DrawMesh>` **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**                                                                                     |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh[]<class_SymbolMesh[]>` | :ref:`CreateMeshData<class_BuildingSymbol_method_CreateMeshData>` **(** :ref:`Geometry<class_Geometry>` geometry, :ref:`Transform<class_Transform>` localorigin, :ref:`Single<class_Single>` height, :ref:`Int32<class_Int32>` level **)** |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`SymbolMesh<class_SymbolMesh>`     | :ref:`CreatePolygonSingleMesh<class_BuildingSymbol_method_CreatePolygonSingleMesh>` **(** :ref:`List`1<class_List`1>` polygon, :ref:`Single<class_Single>` height **)**                                                                    |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Void<class_Void>`                 | :ref:`Dispose<class_BuildingSymbol_method_Dispose>` **(** **)**                                                                                                                                                                            |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_Object>`             | :ref:`Clone<class_BuildingSymbol_method_Clone>` **(** **)**                                                                                                                                                                                |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------

.. _class_BuildingSymbol_property_IsNeedNormal:

- :ref:`Boolean<class_Boolean>` **IsNeedNormal**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否需要法线，默认为false

----

.. _class_BuildingSymbol_property_IsClose:

- :ref:`Boolean<class_Boolean>` **IsClose**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否闭合,默认为true

----

.. _class_BuildingSymbol_property_UnitScale:

- :ref:`Single<class_Single>` **UnitScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

UV缩放,默认为1米重复一次

----

.. _class_BuildingSymbol_property_UVRepeat:

- :ref:`Boolean<class_Boolean>` **UVRepeat**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

是否使用UnitScale对UV进行缩放

----

.. _class_BuildingSymbol_property_UvScale:

- :ref:`Vector2<class_Vector2>` **UvScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

UV缩放值，默认为vector2（1,1）

----

.. _class_BuildingSymbol_property_ExtrudeDir:

- :ref:`Vector3<class_Vector3>` **ExtrudeDir**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

高度延伸方向，默认为Vector3.Up（0,1,0）

----

.. _class_BuildingSymbol_property_HeightField:

- :ref:`String<class_String>` **HeightField**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

高度字段，默认为null

----

.. _class_BuildingSymbol_property_HeightScale:

- :ref:`Int32<class_Int32>` **HeightScale**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

高度缩放值，默认为3

----

.. _class_BuildingSymbol_property_RandomHeight:

- :ref:`Boolean<class_Boolean>` **RandomHeight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

高度是否随机产生，默认为true

----

.. _class_BuildingSymbol_property_ExtrudeHeight:

- :ref:`Single<class_Single>` **ExtrudeHeight**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

高度值，默认为30

----

.. _class_BuildingSymbol_property_WallMaterial:

- :ref:`SpatialMaterial<class_SpatialMaterial>` **WallMaterial**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

墙面材质

----

.. _class_BuildingSymbol_property_RoofMaterial:

- :ref:`SpatialMaterial<class_SpatialMaterial>` **RoofMaterial**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

屋顶材质

----

.. _class_BuildingSymbol_property_SymbolColor:

- :ref:`Color<class_Color>` **SymbolColor**

+----------+---+
| *Setter* |   |
+----------+---+
| *Getter* |   |
+----------+---+

BuildingSymbol的颜色

----


方法说明
-------

.. _class_BuildingSymbol_method_DrawMesh:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **DrawMesh** **(** :ref:`Feature<class_Feature>` feature, :ref:`Transform<class_Transform>` localorigin **)**

根据传入的要素构建出模型数组

----

.. _class_BuildingSymbol_method_CreateMeshData:

- :ref:`SymbolMesh[]<class_SymbolMesh[]>` **CreateMeshData** **(** :ref:`Geometry<class_Geometry>` geometry, :ref:`Transform<class_Transform>` localorigin, :ref:`Single<class_Single>` height, :ref:`Int32<class_Int32>` level **)**

根据传入的几何数据构建出SymbolMesh

----

.. _class_BuildingSymbol_method_CreatePolygonSingleMesh:

- :ref:`SymbolMesh<class_SymbolMesh>` **CreatePolygonSingleMesh** **(** :ref:`List`1<class_List`1>` polygon, :ref:`Single<class_Single>` height **)**

根据底面多边形挤压出侧面

----

.. _class_BuildingSymbol_method_Dispose:

- :ref:`Void<class_Void>` **Dispose** **(** **)**

释放当前对象

----

.. _class_BuildingSymbol_method_Clone:

- :ref:`Object<class_Object>` **Clone** **(** **)**

拷贝当前的对象

----

