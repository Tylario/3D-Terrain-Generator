ThreeJS Terrain Generator
-------------------------

## Summary
Every time you run the code it generates a visual terrain 200 x 200 using Three.JS

[Try it out](https://tylario.github.io/3D-Terrain-Generator/index.html)

## Information
The land is a green wireframe 
The ocean is a blue rectangular prism

lines 92 - 98 have variebles that might can be changed.

	var detail = 80;
	var mapSize = 200;
	var choppiness = 2;
	var geometry = new THREE.PlaneGeometry(mapSize, (mapSize), detail, detail);
	var o = 0;
	var a = 0;
	var b=false;

## Controls
Click and drag to rotate around the center
Zoom in to Zoom in
