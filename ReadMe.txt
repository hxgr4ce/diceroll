===================
FINAL PROJECT: DICE
Author: Hadley Lim
Date: 14 Dec 2021
===================

This program simulates a four-sided, six-sided, 8-sided, and 20-sided die which can be rolled across a surface by the user, created with the intention of being used during a session of Dungeons and Dragons. Die is rolled once upon the page loading, and can be rolled again by pressing the "Roll" button or by changing the shape of the die. 
NOTE: To read the d4, use the number printed in the upper corner of the die.

Techniques Used:
- Created simple objects– a tetrahedron and an icosahedron– directly, using primitives.
- Created objects– a cube, an octahedron, and an icosahedron– using Three.js built in geometrical functions.
- Uses colors several times in conjunction with textures to give the scene the desired atmosphere.
- Uses cameras and lights, ambient and directional, to illuminate the scene. Camera set up through the TW library.
- Textures were made by hand using a drawing program and used to create markings on the die faces.
- Uses animation through the physics engine to simulate the die rolling.

Difficulties Encountered:
	I initially attempted to try and crate the icosahedron in a "smart" way but ended up creating it manually. As it was difficult to convert a complex, custom geometry such as the icosahedron into a cannon-compatible form, the Three.js icosahedron function was used instead. However, the construction for an icosahedron's geometry remains in the program, for possible further work and really just proof that I made an icosahedron from scratch.


Known Bugs:
	Runtime is a little slow for more complex objects, presumably because I made them rather large, but as a matter of personal preference, seeing the result of the roll is more important than a split second pause.
	
Resources:
Tetrahedron, Wikipedia.
Regular Icosahedron, Wikipedia.
Cannon by schteppe, Github.
Learning THREE.js and CANNON.js by javascriptjamie, http://javascriptjamie.weebly.com/.
Color-hex, www.Color-Hex.com.
Falling Spheres by Douglas Duhaime, https://bl.ocks.org/duhaime.

Permission:
I don't mind having this posted on the Group Projects page with my name on it.