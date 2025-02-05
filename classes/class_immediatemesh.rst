:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the ImmediateMesh.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_ImmediateMesh:

ImmediateMesh
=============

**Inherits:** :ref:`Mesh<class_Mesh>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Mesh optimized for creating geometry manually.

Description
-----------

Mesh optimized for creating geometry manually, similar to OpenGL1.x immediate mode.

Methods
-------

+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void | :ref:`clear_surfaces<class_ImmediateMesh_method_clear_surfaces>` **(** **)**                                                                                                      |
+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void | :ref:`surface_add_vertex<class_ImmediateMesh_method_surface_add_vertex>` **(** :ref:`Vector3<class_Vector3>` vertex **)**                                                         |
+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void | :ref:`surface_add_vertex_2d<class_ImmediateMesh_method_surface_add_vertex_2d>` **(** :ref:`Vector2<class_Vector2>` vertex **)**                                                   |
+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void | :ref:`surface_begin<class_ImmediateMesh_method_surface_begin>` **(** :ref:`PrimitiveType<enum_Mesh_PrimitiveType>` primitive, :ref:`Material<class_Material>` material=null **)** |
+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void | :ref:`surface_end<class_ImmediateMesh_method_surface_end>` **(** **)**                                                                                                            |
+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void | :ref:`surface_set_color<class_ImmediateMesh_method_surface_set_color>` **(** :ref:`Color<class_Color>` color **)**                                                                |
+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void | :ref:`surface_set_normal<class_ImmediateMesh_method_surface_set_normal>` **(** :ref:`Vector3<class_Vector3>` normal **)**                                                         |
+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void | :ref:`surface_set_tangent<class_ImmediateMesh_method_surface_set_tangent>` **(** :ref:`Plane<class_Plane>` tangent **)**                                                          |
+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void | :ref:`surface_set_uv<class_ImmediateMesh_method_surface_set_uv>` **(** :ref:`Vector2<class_Vector2>` uv **)**                                                                     |
+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void | :ref:`surface_set_uv2<class_ImmediateMesh_method_surface_set_uv2>` **(** :ref:`Vector2<class_Vector2>` uv2 **)**                                                                  |
+------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Method Descriptions
-------------------

.. _class_ImmediateMesh_method_clear_surfaces:

- void **clear_surfaces** **(** **)**

Clear all surfaces.

----

.. _class_ImmediateMesh_method_surface_add_vertex:

- void **surface_add_vertex** **(** :ref:`Vector3<class_Vector3>` vertex **)**

Add a 3D vertex using the current attributes previously set.

----

.. _class_ImmediateMesh_method_surface_add_vertex_2d:

- void **surface_add_vertex_2d** **(** :ref:`Vector2<class_Vector2>` vertex **)**

Add a 2D vertex using the current attributes previously set.

----

.. _class_ImmediateMesh_method_surface_begin:

- void **surface_begin** **(** :ref:`PrimitiveType<enum_Mesh_PrimitiveType>` primitive, :ref:`Material<class_Material>` material=null **)**

Begin a new surface.

----

.. _class_ImmediateMesh_method_surface_end:

- void **surface_end** **(** **)**

End and commit current surface. Note that surface being created will not be visible until this function is called.

----

.. _class_ImmediateMesh_method_surface_set_color:

- void **surface_set_color** **(** :ref:`Color<class_Color>` color **)**

Set the color attribute that will be pushed with the next vertex.

----

.. _class_ImmediateMesh_method_surface_set_normal:

- void **surface_set_normal** **(** :ref:`Vector3<class_Vector3>` normal **)**

Set the normal attribute that will be pushed with the next vertex.

----

.. _class_ImmediateMesh_method_surface_set_tangent:

- void **surface_set_tangent** **(** :ref:`Plane<class_Plane>` tangent **)**

Set the tangent attribute that will be pushed with the next vertex.

----

.. _class_ImmediateMesh_method_surface_set_uv:

- void **surface_set_uv** **(** :ref:`Vector2<class_Vector2>` uv **)**

Set the UV attribute that will be pushed with the next vertex.

----

.. _class_ImmediateMesh_method_surface_set_uv2:

- void **surface_set_uv2** **(** :ref:`Vector2<class_Vector2>` uv2 **)**

Set the UV2 attribute that will be pushed with the next vertex.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
