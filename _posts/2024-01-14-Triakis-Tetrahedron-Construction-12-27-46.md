---
title: Triakis Tetrahedron Construction
description: A 3D design created in vZome.  Use your mouse or touch to interact.
image: https://John-Kostick.github.io/vzome-sharing/2024/01/14/12-27-46-Triakis-Tetrahedron-Construction/Triakis-Tetrahedron-Construction.png
published: true
layout: vzome
description:
  This is a description of how to construct a Triakis Tetrahedron with vZome
---

{% comment %}
 - [***web page generated from this source***](<https://John-Kostick.github.io/vzome-sharing/2024/01/14/Triakis-Tetrahedron-Construction-12-27-46.html>)
 - [data assets and more info](<https://github.com/John-Kostick/vzome-sharing/tree/main/2024/01/14/12-27-46-Triakis-Tetrahedron-Construction/>)
 
{% endcomment %}
 This is a description of how to construct a Triakis Tetrahedron, a [Catalan Solid](https://en.wikipedia.org/wiki/Catalan_solid) with vZome. The steps, as described, are illustrated in Scenes.  The steps in this example can be applied to construct all of the Catalan Solids.  The first step is to identify and construct the Archimedean Dual of the Catalan to be built.  


  Thus, here Step 1 is to construct a Truncated Tetrahedron, with midpoints of edges indicated.  These midpoints are generally equidistant from the origin, which can be verified.  


  Step 2 is to connect the origin to the center of each type of edge with a strut, as shown in Scene titled  "Cross Products."


  Step 3 is to build a strut that is perpendicular both to the edge and to the radial strut from the origin to the strut midpoint.  This can be seen as constructing a tangent to a sphere that all the midpoints lie on the surface of.  The simplest way to do this is to use the Cross Product tool in the Construct menu.  


  Step 4 is to apply symmetry tool to the Cross Products, and find intersection points centered above each indicated face of the Archimedean Dual.  This is illustrated in Scene titled "Cross Products intersecting."


  Step 5 is to generate panels from these intersection points.  This can be done one at a time, or by using Select> Balls, and Construct> 3D Convex Hull tools.  


  It should be noted that there may be other polyhedra that can be constructed within the same Archimedean frameworks which have the same number and type of faces, but do not meet the definition of true Catalan Solids. One characteristic that is easy to check is that all the dihedral angles between adjoining faces in a model should be the same.  One can also check face angles against those listed.  



<figure style="width: 87%; margin: 5%">
  <vzome-viewer style="width: 100%; height: 60vh"  show-scenes="true"
       src="https://John-Kostick.github.io/vzome-sharing/2024/01/14/12-27-46-Triakis-Tetrahedron-Construction/Triakis-Tetrahedron-Construction.vZome" >
    <img  style="width: 100%"
       src="https://John-Kostick.github.io/vzome-sharing/2024/01/14/12-27-46-Triakis-Tetrahedron-Construction/Triakis-Tetrahedron-Construction.png" >
  </vzome-viewer>
  <figcaption style="text-align: center; font-style: italic;">
    Triakis Tetrahedron Construction
  </figcaption>
</figure>
