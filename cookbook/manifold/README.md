<span style=display:none; >[You are now in a GitHub source code view - click this link to view Read Me file as a web page]( https://jaanga.github.io/cookbook-threejs/examples/0-templates/ "View file as a web page." ) </span>


<div><input type=button onclick="window.location.href='https://github.com/jaanga/jaanga.github.io/tree/master/cookbook-threejs/0-templates/README.md'";
value='You are now in a GitHub web page view - Click this button to view this read me file as source code' ></div>


# [Manifold Read Me]( #cookbook-threejs/examples/editing/manifold/README.md )

<!--
<iframe src=https://jaanga.github.io/cookbook/examples/xxxxxx/xxxxxx.html width=100% height=500px >Iframes are not viewable in GitHub source code view</iframe>
_basic-html.html_
-->

### Full Screen: [Manifold]( https://jaanga.github.io/cookbook-threejs/examples/editing/manifold/ )

<details open >
<summary>Concept</summary>

Given: arbitrary geometry object in 3D space composed of triangles - in other words any Three.js Mesh object)

Task 1: Poke a hole or any number of holesin the geometry by moving any vertex at any arbitrary location in the geometry to any distance away from its given position
Task 2: By algorithm only, identify the moved vertices - the errant ones making the holes - and display the positions of the errant vertices
Task 3: Repair the geometry


### Define "Manifold"

Manifold: a collection of points forming a certain kind of set, such as those of a topologically closed surface or an analog of this in three or more dimensions.

https://en.wikipedia.org/wiki/Manifold

"watertight"

* closely sealed, fastened, or fitted so that no water enters or passes through.


### Triangular faces check

Three.js meshes are composed of triangular faces. This script checks the edges of every face and establish whether or not there is a duplicate edge occurring in another face. The absence of a duplicate indicates a non-manifold mesh.


</details>

<details open >
<summary>To do and wish list </summary>

* 2019-12-12 ~ Theo ~ Support any imported object - such as STL files

</details>

<details open >
<summary>Links of interest</summary>

* https://discourse.threejs.org/t/how-to-find-wall-thickness-of-3d-models-stl-files/5719/20
* https://jsfiddle.net/prisoner849/L0ecxuk4/
* https://threejs.org/examples/models/stl/ascii/slotted_disk.stl



</details>

<details open >
<summary>Change log </summary>

### 2019-12-12 ~ Theo

Manifold v.0.04.01

* Making progress

* Task 2 looks like could be accomplished with next version

Lesson learned

* Comparing index numbers is better than comparing Three.js vertices

### 2019-12-06

* First commit read me

</details>

***

# <center title="hello!" ><a href=javascript:window.scrollTo(0,0); style=text-decoration:none; > ❦ </a></center>