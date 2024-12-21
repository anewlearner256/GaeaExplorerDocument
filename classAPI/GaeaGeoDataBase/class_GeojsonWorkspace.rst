.. _class_GeojsonWorkspace:

GeojsonWorkspace 
===================

**Inherits:** :ref:`Workspace<class_Workspace>` **<** :ref:`Object<class_Object>`

描述
----



示例
----

属性
----

+-----------------+-------------------------------------------+

方法
----

+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`FeatureClass<class_FeatureClass>` | :ref:`OpenFeatureClass<class_GeojsonWorkspace_method_OpenFeatureClass>` **(** :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`Boolean<class_Boolean>` readProp **)**                                                                                |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`IEnumerator<class_IEnumerator>`   | :ref:`OpenFeatureClassCo<class_GeojsonWorkspace_method_OpenFeatureClassCo>` **(** :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`Boolean<class_Boolean>` readProp **)**                                                                            |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`FeatureClass<class_FeatureClass>` | :ref:`CreateFeatureClass<class_GeojsonWorkspace_method_CreateFeatureClass>` **(** :ref:`String<class_String>` geojson, :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`FeatureLayer<class_FeatureLayer>` featureLayer **)**                         |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`FeatureClass<class_FeatureClass>` | :ref:`OpenFeatureClassWithGeoJsonStr<class_GeojsonWorkspace_method_OpenFeatureClassWithGeoJsonStr>` **(** :ref:`String<class_String>` geojson, :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`FeatureLayer<class_FeatureLayer>` featureLayer **)** |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`FeatureClass<class_FeatureClass>` | :ref:`OpenFeatureClassWithBuffer<class_GeojsonWorkspace_method_OpenFeatureClassWithBuffer>` **(** :ref:`Byte[]<class_Byte[]>` buffer, :ref:`Boolean<class_Boolean>` inverseLatLon **)**                                                                |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Feature<class_Feature>`           | :ref:`ParseFeatureItem<class_GeojsonWorkspace_method_ParseFeatureItem>` **(** :ref:`Dictionary<class_Dictionary>` data, :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`String<class_String>` shapeFieldName **)**                                  |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Feature<class_Feature>`           | :ref:`ParseGeometryItem<class_GeojsonWorkspace_method_ParseGeometryItem>` **(** :ref:`Dictionary<class_Dictionary>` data, :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`String<class_String>` shapeFieldName **)**                                |
+-----------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

属性说明
-------


方法说明
-------

.. _class_GeojsonWorkspace_method_OpenFeatureClass:

- :ref:`FeatureClass<class_FeatureClass>` **OpenFeatureClass** **(** :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`Boolean<class_Boolean>` readProp **)**

读取并解析GeoJSON文件

----

.. _class_GeojsonWorkspace_method_OpenFeatureClassCo:

- :ref:`IEnumerator<class_IEnumerator>` **OpenFeatureClassCo** **(** :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`Boolean<class_Boolean>` readProp **)**

打开一个地理信息数据文件（如shp,GeoJson）

----

.. _class_GeojsonWorkspace_method_CreateFeatureClass:

- :ref:`FeatureClass<class_FeatureClass>` **CreateFeatureClass** **(** :ref:`String<class_String>` geojson, :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`FeatureLayer<class_FeatureLayer>` featureLayer **)**

根据geojson创建要素类

----

.. _class_GeojsonWorkspace_method_OpenFeatureClassWithGeoJsonStr:

- :ref:`FeatureClass<class_FeatureClass>` **OpenFeatureClassWithGeoJsonStr** **(** :ref:`String<class_String>` geojson, :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`FeatureLayer<class_FeatureLayer>` featureLayer **)**

接受一个GeoJSON字符串，将其解析为FeatureClass对象，并将该对象返回。

----

.. _class_GeojsonWorkspace_method_OpenFeatureClassWithBuffer:

- :ref:`FeatureClass<class_FeatureClass>` **OpenFeatureClassWithBuffer** **(** :ref:`Byte[]<class_Byte[]>` buffer, :ref:`Boolean<class_Boolean>` inverseLatLon **)**

函数的作用是接收一个字节数组，将其解析为FeatureClass对象，并将该对象返回。

----

.. _class_GeojsonWorkspace_method_ParseFeatureItem:

- :ref:`Feature<class_Feature>` **ParseFeatureItem** **(** :ref:`Dictionary<class_Dictionary>` data, :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`String<class_String>` shapeFieldName **)**

解析Godot.Collections.Dictionary数据，并转换为Feature对象

----

.. _class_GeojsonWorkspace_method_ParseGeometryItem:

- :ref:`Feature<class_Feature>` **ParseGeometryItem** **(** :ref:`Dictionary<class_Dictionary>` data, :ref:`Boolean<class_Boolean>` inverseLatLon, :ref:`String<class_String>` shapeFieldName **)**

根据输入的data字典获取几何形状的类型和坐标等信息。然后，根据几何形状的类型创建相应的Geometry对象，并将其添加到Feature对象中。最后，返回解析得到的Feature对象。

----

